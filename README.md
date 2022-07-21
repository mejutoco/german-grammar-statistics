# german-grammar-statistics

[Top 500,000 words in german with gender](german_top_50000_gender.csv).
The word frequency was taken from Wikipedia sets for different languages.
I believe the german one uses this underneath (https://invokeit.wordpress.com/frequency-word-lists/)
The gender was extracted querying different dictionaries for the word.

## Format
The [csv](german_top_50000_gender.csv) has 2 columns with word and gender, which can be one of:
  - f: Feminine
  - m: Masculine
  - n: Neutral
  - none: prepositions, conjunctions, etc. do not have a gender
  
|       |          |
|-------|----------|
| ihm   |	none   |
| koennen   |	none   |
| ich   |	n   |
| sie   |	none   |
| das   |	none   |
| ist   |	n   |
| du   |	none   |
| nicht   |	none   |
| die   |	none   |
| und   |	none   |
| es   |	n   |
| ...   |	...   |

  
## Usage

This dataset was used for the [article about grammar statistics in german](https://mejuto.co/statistical-grammar-guessing-a-germans-nouns-gender.html)
It is free to user under the Creative Commons Attribution 4.0 International. (see [License](LICENSE))
Enjoy.
