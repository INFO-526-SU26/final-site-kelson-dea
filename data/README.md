# Data

- **endangered_status.csv**: Associates endangerment status to each language
- **families.csv**: Identifies each language with it's language family
- **languages.csv**: Describes geographic features and isolate status of each language

### The following Data Dictionary is taken directly from the TidyTuesday GitHub page:

https://github.com/rfordatascience/tidytuesday/blob/main/data/2025/2025-12-23/readme.md

## Data Dictionary

### `endangered_status.csv`

| Variable     | Class     | Description                                        |
|--------------|-----------|----------------------------------------------------|
| id           | character | Unique identifier for language                     |
| status_code  | character | Code of the agglomerated endangerment status (1–6) |
| status_label | character | Descriptive label of endangerment category         |

### `families.csv`

| Variable | Class     | Description                           |
|----------|-----------|---------------------------------------|
| id       | character | Unique identifier for language family |
| name     | character | Language family name                  |

### `languages.csv`

| Variable | Class | Description |
|----|----|----|
| id | character | Unique identifier for language |
| name | character | Language name |
| macroarea | character | General geographic area in which the language is found |
| latitude | double | Latitude of language location (as point) |
| longitude | double | Longitude of language location (as point) |
| iso639p3code | character | ISO 639-3 identifier of language (if available) |
| countries | character | Countries in which language is used (separated by ";") |
| is_isolate | logical | Whether language is an isolate (i.e. has no known relatives) |
| family_id | character | Unique identifier of family that the language is part of (if not isolate) |
