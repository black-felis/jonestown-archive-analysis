# jonestown-archive-analysis
A beginner's project that takes files from the jonestown archive and looks at the frequency of inputted words.
The transcripts are not included in this repository, you must access them at the Jonestown Institute Archive at https://jonestown.sdsu.edu/
Please cite the Jonestown Institute Archive if you plan on using their transcripts in your own work.

## REQUIREMENTS:
- Python 3.12
- 'nltk' and 'beautifulsoup4' (listed in the Pipfile)

  ```bash
pipenv install
```

One-time NLTK data downloads:

```python
import nltk
nltk.download("punkt_tab")
nltk.download("stopwords")
```

## Usage

```bash
pipenv run python html_jonestown.py

## Suggested order for a new transcript: 1, then 2, then 3, then 5, 6, and 7.

## Acknowledgments

The `jones_speaker` function was written with the assistance of Claude (Anthropic).

## License
[MIT License, see LICENSE]


## Author

[Rebecca Sova], [UTSA, Linguistics]
