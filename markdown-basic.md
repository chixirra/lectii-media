# FIȘĂ DE LUCRU – MARKDOWN DE BAZĂ

**Nume și prenume:** popa cristian

## 1\. Ce este Markdown?

Markdown este un **limbaj de marcare ușoară** folosit pentru scrierea și structurarea textelor cu ajutorul unor simboluri simple (`#`, `*`, `-`, `>` etc.).

- **Text simplu** – text format doar din caractere, fără fonturi, culori sau dimensiuni speciale.
- **Text formatat** – text care conține titluri, liste, imagini, evidențieri etc.
- **Limbaj de marcare** – sistem de simboluri care indică structura unui document.
- **Randare** – transformarea textului Markdown în text formatat.
- **Previzualizare** – fereastra în care putem vedea cum va arăta documentul final.

Markdown a fost creat în anul 2004 de John Gruber.

Fișierele Markdown au extensia **`.md`**.

### Unde se folosește?

- Pagini web și GitHub.
- Notițe în Obsidian.
- Documentație și articole.
- Mesaje în Discord și Teams.
- Documente realizate cu ajutorul asistenților AI.

## 2\. Markdown vs. Word

| Caracteristică | Markdown (.md) | Word (.docx) |
| --- | --- | --- |
| Conținut | Text și simboluri | Text formatat |
| Editare | Cu ajutorul simbolurilor | Cu ajutorul butoanelor |
| Dimensiune | De obicei mică | De obicei mai mare |
| Aspect | Se stabilește la afișare | Se stabilește în document |
| Deschidere | Orice editor de text | Word sau program compatibil |

**Ideea principală:** În Markdown, conținutul este separat de aspect. Același fișier poate fi transformat în pagină web, document Word sau carte electronică.

## 3\. Programe pentru lucrul cu Markdown

| Program | Caracteristici |
| --- | --- |
| Visual Studio Code | Editor gratuit, cu previzualizare |
| Obsidian | Program pentru notițe |
| StackEdit | Editor online, fără instalare |
| Notepad | Editor simplu de text, fără previzualizare |

### Crearea unui fișier în Visual Studio Code

1. Se creează un folder de lucru.
2. Se deschide folderul în VS Code (File → Open Folder).
3. Se creează un fișier nou.
4. Se salvează cu extensia `.md`, de exemplu `primul-fisier.md`.
5. Se deschide previzualizarea cu `Ctrl + K`, apoi `V`.
6. Se salvează documentul cu `Ctrl + S`.

**Atenție:** Un fișier salvat greșit poate avea numele `articol.md.txt`. Trebuie verificată extensia reală a fișierului.

## 4\. Simboluri importante pe tastatură

| Simbol | Denumire | Utilizare |
| --- | --- | --- |
| `#` | Diez | Titluri |
| `*` | Asterisc | Text cursiv și îngroșat |
| `-` | Liniuță | Liste |
| `>` | Mai mare | Citate |
| `[ ]` | Paranteze drepte | Linkuri și imagini |
| `!` | Semnul exclamării | Imagini |
| `` ` `` | Accent grav | Cod |
| `\` | Bară oblică inversă | Caractere speciale și rând nou |

## 5\. Paragrafe și rânduri noi

### Paragrafe

Două paragrafe se separă printr-un rând gol.

Exemplu:

text

```text
Primul paragraf.

Al doilea paragraf.
```

**Important:** O singură apăsare Enter nu produce obligatoriu un rând nou la afișare. Rândurile pot fi unite în același paragraf.

### Rând nou în același paragraf

Se folosește bara oblică inversă `\` la finalul rândului sau două spații.

Exemplu:

text

```text
Redacția revistei\
Clasa a XII-a Media\
Buzău
```

## 6\. Titluri

Titlurile se scriu folosind simbolul `#`, urmat de un spațiu.

| Sintaxă | Nivel |
| --- | --- |
| `# Titlu` | Nivelul 1 |
| `## Titlu` | Nivelul 2 |
| `### Titlu` | Nivelul 3 |
| `#### Titlu` | Nivelul 4 |
| `##### Titlu` | Nivelul 5 |
| `###### Titlu` | Nivelul 6 |

### Reguli:

- Un document trebuie să aibă un singur titlu de nivel 1.
- Nivelurile nu trebuie sărite.
- Titlurile se scriu fără punct la final.
- Se lasă un rând gol înainte și după titlu.
- Titlurile trebuie alese în funcție de structura documentului, nu de mărimea dorită a literelor.

## 7\. Evidențierea textului

| Tip | Sintaxă Markdown | Rezultat |
| --- | --- | --- |
| Îngroșat (aldin) | `**important**` | **important** |
| Cursiv (italic) | `*important*` | _important_ |
| Îngroșat și cursiv | `***important***` | **_important_** |
| Cod în rând | `` `fisier.pdf` `` | `fisier.pdf` |

Reguli:

- Simbolurile trebuie lipite de text.
- Fiecare evidențiere trebuie închisă cu aceleași simboluri.
- Pentru cursiv se poate folosi și `_text_`.
- Pentru îngroșat se poate folosi și `__text__`.
- Evidențierea trebuie utilizată cu măsură.
- Markdown de bază nu oferă direct funcția de subliniere.

## 8\. Liste

### Listă cu buline

Se folosește atunci când ordinea elementelor nu contează.

text

```text
- Photoshop
- Illustrator
- Premiere Pro
```

### Listă numerotată

Se folosește atunci când ordinea elementelor contează.

text

```text
1. Deschiderea programului.
2. Editarea documentului.
3. Salvarea fișierului.
```

### Liste imbricate (liste în liste)

O listă poate conține o altă listă. Elementele interioare se retrag cu patru spații.

text

```text
1. Programe:
    - Photoshop
    - Illustrator
2. Formate:
    - JPG
    - PNG
```

Reguli:

- Se lasă un rând gol înaintea listei.
- După liniuță sau număr se pune un spațiu.
- Se păstrează același simbol pentru elementele unei liste.
- Numerotarea se continuă automat.

## 9\. Legături (linkuri)

Un link permite accesarea unei pagini web, a unui fișier sau a unei secțiuni din document.

**Sintaxa generală:**

text

```text
[textul afișat](adresa)
```

Exemple:

Link către o pagină web:

text

```text
[Google](https://www.google.com)
```

Link cu explicație la trecerea cursorului:

text

```text
[Google](https://www.google.com "Motor de căutare")
```

Adresă afișată direct:

text

```text
<https://www.google.com>
```

Link către un fișier:

text

```text
[Fișa de lucru](fise/fisa-1.md)
```

Link către un titlu din același document:

text

```text
[Reguli de bază](#reguli-de-bază)
```

Reguli:

- Între `]` și `(` nu se lasă spațiu.
- Adresa web trebuie să conțină `https://`.
- Textul afișat trebuie să descrie destinația.
- Linkurile trebuie verificate în previzualizare.

## 10\. Imagini

Pentru introducerea unei imagini se folosește semnul `!` înaintea sintaxei unui link.

**Sintaxa:**

text

```text
![Descrierea imaginii](calea-catre-imagine)
```

Exemplu:

text

```text
![Schița unui afiș](imagini/schita.png)
```

- Textul alternativ descrie imaginea și ajută persoanele care folosesc cititoare de ecran.
- Imaginile se pot păstra într-un folder numit `imagini`.
- Calea către imagine trebuie să fie relativă.
- Se folosește bara `/`, nu `\`.
- Numele fișierelor trebuie să fie simple, fără spații și diacritice.

### Formate de imagine

| Format | Utilizare |
| --- | --- |
| PNG | Capturi de ecran și grafică |
| JPG | Fotografii |
| SVG | Desene vectoriale |

**Atenție:** La predarea unui proiect se predă întregul folder, nu doar fișierul `.md`.

## 11\. Citate

Pentru introducerea unui citat se folosește simbolul `>` urmat de un spațiu.

Exemplu:

text

```text
> Un afiș bun se înțelege fără
> a fi citit până la capăt.
>
> — Din regulile atelierului
```

Citatele pot fi folosite pentru:

- Texte preluate din alte surse.
- Idei importante.
- Observații și avertismente.

Se pot introduce și texte îngroșate sau liste în interiorul unui citat.

## 12\. Cod și linie orizontală

### Cod în rând

Se folosesc două accente grave în jurul textului.

Exemplu:

text

```text
Fișierul se numește `afis_v2.pdf`.
```

### Bloc de cod

Se folosesc trei accente grave înainte și după fragmentul de cod.

Exemplu:

text

````text
```
Titlu: Ziua Porților Deschise
Data: 24 octombrie
Format: A3
```
````

Blocul de cod păstrează spațiile și rândurile exact cum au fost scrise.

### Linie orizontală

Se folosește un rând cu trei liniuțe:

text

```text
---
```

Aceasta separă diferite secțiuni ale documentului. Se lasă un rând gol înainte și după.

## 13\. Caractere speciale

Unele simboluri au rol special în Markdown. Pentru a le afișa ca simple caractere, se folosește bara inversă `\` înaintea lor.

Exemple:

| Sintaxă | Rezultat |
| --- | --- |
| `\*text\*` | _text_ |
| `\# titlu` | \# titlu |
| `2026\.` | 2026. |
| `\\` | \\ |

În interiorul codului, simbolurile sunt afișate exact așa cum au fost scrise.

### Elemente HTML utilizabile în Markdown

| Sintaxă | Rol |
| --- | --- |
| `<kbd>Ctrl</kbd>` | Afișarea unei taste |
| `<sup>2</sup>` | Exponent |
| `<sub>2</sub>` | Indice |
| `<br>` | Rând nou |

Exemple:

- `m<sup>2</sup>` → m²
- `H<sub>2</sub>O` → H₂O

## 14\. Greșeli frecvente

| Greșit | Corect |
| --- | --- |
| `#Titlu` | `# Titlu` |
| `-element` | `- element` |
| `** important **` | `**important**` |
| `**important*` | `**important**` |
| `[Google] (https://google.com)` | `[Google](https://google.com)` |
| `[Google](www.google.com)` | `[Google](https://www.google.com)` |
| `[Schiță](imagini/schita.png)` | `![Schiță](imagini/schita.png)` |

### Reguli pentru un document îngrijit

1. Se folosește un singur titlu de nivel 1.
2. Nu se sar nivelurile titlurilor.
3. Se lasă rânduri goale între secțiuni.
4. Se folosesc consecvent aceleași simboluri.
5. Se utilizează diacritice corecte (ă, â, î, ș, ț).
6. Fișierul se salvează cu extensia `.md`.
7. Se utilizează codarea UTF-8.
8. Se verifică documentul în previzualizare înainte de predare.

## 15\. Glosar – termeni de reținut

- **Markdown** – limbaj de marcare ușoară.
- **Sintaxă** – regulile de scriere ale unui limbaj.
- **Randare** – transformarea textului marcat în text formatat.
- **Previzualizare** – afișarea rezultatului în timpul scrierii.
- **Paragraf** – grup de rânduri separate de alte paragrafe printr-un rând gol.
- **Ierarhie** – ordinea nivelurilor titlurilor.
- **Aldin** – text îngroșat.
- **Italic** – text cursiv.
- **Link** – legătură către o pagină sau un fișier.
- **Text alternativ** – descrierea unei imagini.
- **Cale relativă** – drumul către un fișier pornind de la folderul documentului.
- **Bloc de cod** – fragment de text afișat exact cum a fost scris.
- **UTF-8** – codare care permite păstrarea corectă a caracterelor și diacriticelor.

---

# 16\. EXERCIȚII DE VERIFICARE

### A. Completează spațiile libere

1. Fișierele Markdown au extensia \_\_\_\_\_\_\_\_\_\_.
2. Markdown a fost creat în anul \_\_\_\_\_\_\_\_\_\_.
3. Simbolul utilizat pentru titluri este \_\_\_\_\_\_\_\_\_\_.
4. Pentru text îngroșat se folosesc \_\_\_\_\_\_\_\_\_\_.
5. Pentru introducerea unui citat se utilizează \_\_\_\_\_\_\_\_\_\_.
6. Pentru introducerea unei imagini se folosește \_\_\_\_\_\_\_\_\_\_.
7. Pentru un link se utilizează sintaxa \_\_\_\_\_\_\_\_\_\_.
8. Transformarea textului Markdown în text formatat se numește \_\_\_\_\_\_\_\_\_\_.

### B. Alege varianta corectă

1. Ce simbol se folosește pentru un titlu de nivel 1?
   - a) `*`
   - b) `#`
   - c) `>`
2. Cum se scrie un cuvânt îngroșat?
   - a) `*cuvânt*`
   - b) `#cuvânt`
   - c) `**cuvânt**`
3. Ce extensie are un fișier Markdown?
   - a) `.docx`
   - b) `.md`
   - c) `.jpg`
4. Ce simbol se folosește pentru o listă cu buline?
   - a) `-`
   - b) `#`
   - c) `!`
5. Ce simbol se folosește pentru introducerea unei imagini?
   - a) `>`
   - b) `!`
   - c) `#`

### C. Răspunde la întrebări

1. Ce este Markdown?
2. Care este diferența dintre text simplu și text formatat?
3. Care este diferența dintre un paragraf și un rând nou în același paragraf?
4. Ce rol are previzualizarea?
5. Care este diferența dintre o listă numerotată și una cu buline?
6. Ce este textul alternativ al unei imagini?
7. De ce trebuie folosite căi relative pentru imagini?
8. Ce rol are bara oblică inversă `\`?

### D. Aplicații practice

**Exercițiul 1 – Formatarea textului**

Scrie următorul text în Markdown, respectând formatarea:

- Titlu principal: „Producție media”.
- Un subtitlu: „Programe de editare”.
- Scrie cuvântul Photoshop îngroșat.
- Scrie cuvântul Illustrator cursiv.
- Introdu numele fișierului `proiect.pdf` ca text de tip cod.

**Exercițiul 2 – Liste**

Realizează o listă numerotată cu trei programe de editare media. Pentru unul dintre programe, adaugă o listă interioară cu două funcții.

**Exercițiul 3 – Link și imagine**

Scrie:

- Un link către `https://www.google.com`, cu textul afișat „Motor de căutare”.
- O imagine cu descrierea „Fotografie de prezentare”, aflată în folderul `imagini`, cu numele `fotografie.jpg`.

**Exercițiul 4 – Citat și cod**

Adaugă un citat despre importanța designului și un bloc de cod care să conțină:

text

```text
Proiect: Afiș publicitar
Format: A3
Rezoluție: 300 DPI
```

**Exercițiul 5 – Document complet**

Creează un fișier numit `prezentare-media.md` care să conțină:

1. Un titlu principal.
2. Două subtitluri.
3. Două paragrafe.
4. Un text îngroșat și unul cursiv.
5. O listă numerotată.
6. O listă cu buline.
7. Un link către o pagină web.
8. O imagine cu text alternativ.
9. Un citat.
10. O linie orizontală.

**Salvează fișierul și verifică rezultatul în previzualizare.**

---

**Concluzie:** Markdown este un instrument simplu și eficient pentru structurarea documentelor digitale. Cunoașterea sintaxei de bază permite realizarea unor texte clare, organizate și ușor de transformat în diferite formate.
