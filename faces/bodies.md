# Bodies

Valid height:

```json
[
    "shortest",
    "shorter",
    "short",
    "median",
    "tall",
    "taller",
    "tallest"
]
```


Valid fat_content:

```json
[
    "lowest",
    "lower",
    "median",
    "higher",
    "highest"
]
```


Height logic:

| Height Label      | Height range in cm|
| ----------- | -----------  |
| "shortest"  |    <= 137    |
| "shorter"   |    138 - 164 |
| "short"     |    165 - 171 |
| "median"    |    172 - 179 |
| "tall"      |    180 - 187 |
| "taller"    |    189 - 193 |
| "tallest"   |    >= 194    |

<br />

BMI logic:

| Label      | Value|
| ----------- | -----------  |
| "lowest"    |    <= 18    |
| "lower"     |    19 - 24 |
| "median"    |    24 - 29 |
| "higher"    |    30 - 39 |
| "highest"   |    >=40    |
