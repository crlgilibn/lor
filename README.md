# Jakob Lorber Gesamtkorpus

*Gemeinfreie digitale Textausgabe (Markdown) der 25 Werke in hierarchischen Lese-Abschnitten*

## Urheberrechtlicher Status

*Gemeinfreiheit / Public Domain nach § 64 UrhG*

Die Originaltexte von **Jakob Lorber (1800–1864)** sind weltweit **gemeinfrei** (*Public Domain*, § 64 UrhG — Schutzfrist von 70 Jahren nach dem Tod des Urhebers seit dem 1. Januar 1935 abgelaufen).
- Dieses Repository enthält ausschließlich die bereinigten, gemeinfreien Texte auf Basis der historischen Erstausgaben des 19. Jahrhunderts und der Urschrift-Wiederherstellungen — **ohne** moderne Herausgeber-Kommentare, Verlags-Vorworte oder nachgetragene Worterklärungen in eckigen Klammern.
- **Gesamtkorpus als Einzeldatei (`91.086` Zeilen):** **[`src/lrb.txt`](src/lrb.txt)** (`WERK/BAND/KAPITEL/VERS Text` bzw. `WERK/KAPITEL/VERS Text`, komplett frei von `|`-Trennzeichen und 6-stelligen Datumsnummern).
- **Einheitliche Kurz-Nummerierung mit `/`:**
  - Mehrteilige Werke (`HG`, `HIM`, `PSG`, `GS`, `RB`, `GEJ`): `WERK/BAND/KAPITEL/VERS` (z. B. `HG/2/252/8`, `HIM/3/26/9`, `HIM/3/148/5`).
  - Einteilige Werke (`PA`, `FL`, `ZS`, `MO`, `SA`, `GR`, `NS`, `KJ`, `STE`, `LAO`, `BJ`, `ER`, `SH`, `BM`, `HS`, `DTT`, `NZ`, `HEIG`, `UT`): `WERK/KAPITEL/VERS` (z. B. `ER/17/2`, `NZ/1/1`).
- **Hierarchischer Aufbau unter [`md/`](md/):** Damit jeder Abschnitt im Browser sofort lädt und bequem lesbar bleibt ($\le 20$ Kapitel bzw. $\approx 50\text{–}200\text{ KB}$ pro Datei), gliedert sich [`md/`](md/) in **1 bis 2 Unterebenen**:
  - `md/<WERK>/README.md` (Inhaltsverzeichnis des jeweiligen Werkes),
  - `md/<WERK>/k001-020.md` (bei einteiligen Werken) bzw. `md/<WERK>/b<BAND>/k001-020.md` (bei mehrbändigen Werken).
- **Strukturelle Korpus-Befunde ($r = 1\dots 7$, ${}(4+3=7){}$, Elektromagnetismus):** siehe **[`FINDINGS.md`](FINDINGS.md)**.

---

## 1. Übersicht der 25 Werke

| Nr | Kürzel | Titel | Beschreibung | Bände | Kapitel | Verse | Verzeichnis & Index |
| :---: | :---: | :--- | :--- | :---: | ---: | ---: | :--- |
| 01 | `HG` | Die Haushaltung Gottes | Urgeschichte (3 Bände, 1840–1844) | 3 | 833 | 17,089 | [`md/HG/`](md/HG/README.md) |
| 02 | `HIM` | Himmelsgaben | Kleinere Kundgaben (3 Bände, 1840–1864) | 3 | 498 | 6,845 | [`md/HIM/`](md/HIM/README.md) |
| 03 | `PSG` | Psalmen und Gedichte | Gedichte, Psalmen und Poesie in Prosa (3 Bände) | 3 | 107 | 1,383 | [`md/PSG/`](md/PSG/README.md) |
| 04 | `PA` | Pathiel | Die große Zeit der Zeiten (1841–1848) | 1 | 1 | 156 | [`md/PA/`](md/PA/README.md) |
| 05 | `FL` | Die Fliege | Einblicke in die Wunder der Schöpfung (1842) | 1 | 14 | 381 | [`md/FL/`](md/FL/README.md) |
| 06 | `ZS` | Die zwölf Stunden | Historisch-prophetische Betrachtungen (1841) | 1 | 13 | 541 | [`md/ZS/`](md/ZS/README.md) |
| 07 | `MO` | Der Mond | Wesen und Bestimmung des Mondes (1841) | 1 | 6 | 99 | [`md/MO/`](md/MO/README.md) |
| 08 | `SA` | Saturnus | Darstellung des Planeten, seiner Ringe und Monde (1841–1842) | 1 | 51 | 938 | [`md/SA/`](md/SA/README.md) |
| 09 | `GR` | Der Großglockner | Ein Evangelium der Berge (1842) | 1 | 14 | 417 | [`md/GR/`](md/GR/README.md) |
| 10 | `NS` | Die natürliche Sonne | Astronomisch-geistige Darstellung der Sonne (1842) | 1 | 74 | 1,585 | [`md/NS/`](md/NS/README.md) |
| 11 | `GS` | Die geistige Sonne | Darstellung der Geisterwelt (2 Bände, 1842–1843) | 2 | 228 | 4,128 | [`md/GS/`](md/GS/README.md) |
| 12 | `KJ` | Die Kindheitsgeschichte Jesu | Jakobus-Evangelium (1843–1844) | 1 | 301 | 7,017 | [`md/KJ/`](md/KJ/README.md) |
| 13 | `STE` | Schrifttexterklärungen | Auslegung ausgewählter Bibelstellen (1843–1844) | 1 | 37 | 830 | [`md/STE/`](md/STE/README.md) |
| 14 | `LAO` | Der Laodizenerbrief | Brief des Apostels Paulus nach Laodizea (1844) | 1 | 3 | 141 | [`md/LAO/`](md/LAO/README.md) |
| 15 | `BJ` | Briefwechsel Jesu mit Abgarus | Korrespondenz mit Abgarus von Edessa (1844) | 1 | 7 | 110 | [`md/BJ/`](md/BJ/README.md) |
| 16 | `ER` | Die Erde | Bau und Wesen des Erdkörpers und des Menschen (1846–1847) | 1 | 86 | 1,423 | [`md/ER/`](md/ER/README.md) |
| 17 | `SH` | Sterben und Hinübergehen | Szenen aus dem Jenseits (1847–1852) | 1 | 12 | 328 | [`md/SH/`](md/SH/README.md) |
| 18 | `BM` | Bischof Martin | Entwicklungsweg einer Seele im Jenseits (1847–1848) | 1 | 205 | 3,364 | [`md/BM/`](md/BM/README.md) |
| 19 | `RB` | Robert Blum | Von der Erde bis zum höchsten Himmel (2 Bände, 1848–1851) | 2 | 303 | 4,005 | [`md/RB/`](md/RB/README.md) |
| 20 | `HS` | Die Heilkraft des Sonnenlichts | Anleitung zur Sonnenlicht-Anwendung (1851) | 1 | 12 | 194 | [`md/HS/`](md/HS/README.md) |
| 21 | `DTT` | Die drei Tage im Tempel | Der zwölfjährige Jesus im Tempel (1859–1860) | 1 | 33 | 600 | [`md/DTT/`](md/DTT/README.md) |
| 22 | `GEJ` | Großes Evangelium Johannes | Hauptwerk der drei Lehrjahre Jesu (10 Bände, 1851–1864) | 10 | 2,426 | 34,128 | [`md/GEJ/`](md/GEJ/README.md) |
| 23 | `NZ` | Naturzeugnisse | Ergänzende Kapitel zu Natur und Kosmos (1840) | 1 | 3 | 79 | [`md/NZ/`](md/NZ/README.md) |
| 24 | `HEIG` | Heilung und Gesundheitspflege | Ergänzende Kapitel aus den Jahren 1841–1849 | 1 | 9 | 129 | [`md/HEIG/`](md/HEIG/README.md) |
| 25 | `UT` | Unveröffentlichte Texte | Vier kleinere Gedichte und Briefworte (1840–1859) | 1 | 4 | 20 | [`md/UT/`](md/UT/README.md) |

---

## 2. Mehrbändige Hauptwerke

| Werk | Band-Verzeichnisse |
| :--- | :--- |
| **`HG` — Die Haushaltung Gottes** | [Band 1 (`k000–186`)](md/HG/README.md) · [Band 2 (`k001–280`)](md/HG/README.md) · [Band 3 (`k001–366`)](md/HG/README.md) |
| **`HIM` — Himmelsgaben** | [Band 1 (`k001–138`)](md/HIM/README.md) · [Band 2 (`k001–182`)](md/HIM/README.md) · [Band 3 (`k001–178`)](md/HIM/README.md) |
| **`PSG` — Psalmen und Gedichte** | [Band 1 (`k001–077`)](md/PSG/README.md) · [Band 2 (`k000–022`)](md/PSG/README.md) · [Band 3 (`k001–007`)](md/PSG/README.md) |
| **`GS` — Die geistige Sonne** | [Band 1 (`k001–101`)](md/GS/README.md) · [Band 2 (`k001–127`)](md/GS/README.md) |
| **`RB` — Robert Blum** | [Band 1 (`k001–150`)](md/RB/README.md) · [Band 2 (`k151–303`)](md/RB/README.md) |
| **`GEJ` — Großes Evangelium Johannes** | [Alle 10 Bände (`b1` bis `b10`, je 20 Kapitel pro Datei)](md/GEJ/README.md) |
