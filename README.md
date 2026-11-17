# Ievade

Jautajums = "Cik 1L pudeles ielien 3456ml udens"

# Apstrāde

Tiks rekinats cik pudeles ielein 3456ml ar udeni

# Izvade

Vajag 3 pudekes un 456ml paliks pāri.

# Mainigie un formulas

| Mainiga vards | Datu tips | Ko glaba |
| :--- | :--- | :--- |
| `kopejais_udens` | `int` | Kopejais udens daudzums ml |
| `pudeles_tilpums` | `int` | Vienas 1L pudeles tilpums ml |
| `pilnas_pudeles` | `int` | Aprekinatais pudelu skaits, ko var piepildit |
| `atlikums` | `int` | Aprekinatais udens atlikums ml, kas paliek pari |

## Formulas

* `pilnas_pudeles = kopejais_udens // pudeles_tilpums`
* `atlikums = kopejais_udens % pudeles_tilpums`

## Datu ieguve

* **No `input()` nak:** `kopejais_udens` (ja speletajs ievada savu atbildi, tad ari `lietotaja_atbilde`).
* **Programmas noteikts (konstante):** `pudeles_tilpums`.
* **Tiek izrekinati:** `pilnas_pudeles` un `atlikums`.
