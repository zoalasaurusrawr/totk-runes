# Wall Art Room Cipher Analysis

## Cipher Text Mapping

Given the left and right panels in the wall art room:

| Left Panel | | Right Panel |
|--|--|--|
| ![Left Panel](../images/RunePanelLeft_c.png) |  | ![Right Panel](../images/RunePanelRight_c.png) |

We get the cipher text when read top-to-bottom, right-to-left with each panel being read right-to-left when using the [rune inventory](../pages/rune-inventory.md) to provide key mappings:

**Left Panel**

ABCDEGCGCDEXABABCDECD

**Right Panel**

YDEBSXDSAZYDBZRCESR

**Combined (based on right-to-left panel)**

YDEBSXDSAZYDBZRCESRABCDEGCGCDEXABABCDECD

### Notes

- Given other text that reads T-B, R-L, the right panel appears to be missing two characters because if the text was shorter, the empty spaces should be at the end.


## Frequency Analysis

### Single Characters

| Combined |   | Left |   | Right |   |
| -------- | - | ---- | - | ----- | - |
| D        | 7 | C    | 5 | D     | 3 |
| C        | 6 | D    | 4 | S     | 3 |
| B        | 5 | A    | 3 | Y     | 2 |
| E        | 5 | B    | 3 | E     | 2 |
| A        | 4 | E    | 3 | B     | 2 |
| S        | 3 | G    | 2 | Z     | 2 |
| G        | 2 | X    | 1 | R     | 2 |
| X        | 2 |      |   | X     | 1 |
| Y        | 2 |      |   | A     | 1 |
| Z        | 2 |      |   | C     | 1 |
| R        | 2 |      |   |       |   |

### Syllables

| Combined |   | Left |   | Right |   |
| -------- | - | ---- | - | ----- | - |
| CD       | 4 | CD   | 4 | YD    | 2 |
| DE       | 4 | AB   | 3 | DE    | 1 |
| AB       | 3 | DE   | 3 | EB    | 1 |
| BC       | 2 | BC   | 2 | BS    | 1 |
| GC       | 2 | GC   | 2 | SX    | 1 |
| YD       | 2 | EG   | 1 | XD    | 1 |
| EG       | 1 | CG   | 1 | DS    | 1 |
| CG       | 1 | EX   | 1 | SA    | 1 |
| EX       | 1 | XA   | 1 | AZ    | 1 |
| XA       | 1 | BA   | 1 | ZY    | 1 |

### Digraphs (3-grams)

| Combined |   | Left |   | Right |   |
| -------- | - | ---- | - | ----- | - |
| CDE      | 3 | CDE  | 3 | YDE   | 1 |
| ABC      | 2 | ABC  | 2 | DEB   | 1 |
| BCD      | 2 | BCD  | 2 | EBS   | 1 |
| DEG      | 1 | DEG  | 1 | BSX   | 1 |
| EGC      | 1 | EGC  | 1 | SXD   | 1 |
| CGC      | 1 | GCG  | 1 | XDS   | 1 |
| GCD      | 1 | CGC  | 1 | DSA   | 1 |
| DEX      | 1 | DEX  | 1 | SAZ   | 1 |
| EXA      | 1 | EXA  | 1 | AZY   | 1 |
| XAB      | 1 | XAB  | 1 | ZYD   | 1 |

### 4-grams

| Combined |   | Left |   | Right |   |
| ------- | - | ------- | - | ------- | - |
| ABCD    | 2 | ABCD    | 2 | \-      | 0 |
| BCDE    | 2 | BCDE    | 2 | \-      | 0 |

### 5-grams

| Combined |   | Left |   | Right |   |
| ------- | - | ------- | - | ------- | - |
| ABCDE   | 2 | ABCDE   | 2 | \-      | 0 |

### 6-grams

| Combined |   | Left |   | Right |   |
| ------- | - | ------- | - | ------- | - |
| \-      | 0 | \-      | 0 | \-      | 0 |

## Romaji Text Source Frequency Analsysis

**Source: Sheikah Tapestry Tranliteration**

`Taiko no mukashi Hylia no ji ni han'ei shita ōkoku ōku no min-tō ga kurashi bunmei ga hagukumu ma reta Sheikah-zoku no motarashita gijutsu wa kōdo 也 Kore o shite yaku wazawai fūin no tasuke o mōketaru yūsha to seinaru hime ga kore o fūin su Hyrule ni tsutawaru yaku wazawai no na wa Ganon shi hō ni shinji Yū o okite karakuri no hei o haisu korera no chikara o ete Ganon o fūzuru ni itaru ōke wa Sheikah-zoku no chikara o osore, tsuihō su sono Sue nite Sheikah chiru`

**Notes**

- This is an especially good source because its using a writing sample that is not only recent, but by the same source (Nintendo). It should be representative of the writing style and tendencies

### Analysis

| Characters |    |
| ---------- | -- |
| A          | 47 |
| O          | 42 |
| I          | 38 |
| U          | 35 |
| N          | 27 |
| K          | 26 |
| H          | 26 |
| E          | 23 |
| S          | 22 |
| R          | 19 |
| T          | 18 |
| M          | 8  |
| W          | 8  |
| G          | 7  |
| Y          | 6  |
| Z          | 5  |
| F          | 3  |
| C          | 3  |
| J          | 3  |
| L          | 2  |
| B          | 1  |
| D          | 1  |


| Syllables (top 10) |    |
| ------------------ | -- |
| NO                 | 13 |
| SH                 | 11 |
| HI                 | 11 |
| TA                 | 9  |
| KU                 | 9  |
| AR                 | 9  |
| IN                 | 8  |
| SU                 | 8  |
| WA                 | 8  |
| KA                 | 7  |


| Digraphs (top 10) |   |
| ----------------- | - |
| SHI               | 7 |
| ASH               | 5 |
| IKA               | 5 |
| ANO               | 4 |
| AKU               | 4 |
| HEI               | 4 |
| ARA               | 4 |
| ORE               | 4 |
| AWA               | 4 |
| ARU               | 4 |

| 4-grams |   |
| ------- | - |
| ASHI    | 3 |
| SHIT    | 3 |
| KUNO    | 3 |
| SHEI    | 3 |
| HEIK    | 3 |
| EIKA    | 3 |
| IKAH    | 3 |
| KORE    | 3 |
| KARA    | 3 |
| SHIH    | 2 |

| 5-grams |    |
| ------- | -- |
| SHEIK   | 3  |
| HEIKA   | 3  |
| EIKAH   | 3  |
| SHITA   | 2  |
| KUNOM   | 2  |
| RASHI   | 2  |
| ASHEI   | 2  |
| IKAHZ   | 2  |
| KAHZO   | 2  |
| AHZOK   | 2  |

| 6-grams |   |
| ------- | - |
| SHEIKA  | 3 |
| HEIKAH  | 3 |
| ASHEIK  | 2 |
| EIKAHZ  | 2 |
| IKAHZO  | 2 |
| KAHZOK  | 2 |
| AHZOKU  | 2 |
| HZOKUN  | 2 |
| ZOKUN   | 2 |
| YAKUWA  | 2 |

### Revisions

- Initially, the giraffe rune was indexed twice, which lead to cipher text errors on the left panel. It caused the cipher text to represent as "ABCDEGCGMDEXABABCDEMD" instead of "ABCDEGCGCDEXABABCDECD". Rune key "F" has been removed and will be re-purposed in the future.