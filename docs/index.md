# Web Mining and Applied NLP Project Report

Author: John James

Date: 2026 October

Course: Web Mining & Applied NLP

Project: NLP-02 Text Preprocessing

## Overview

In my project I am analyzing a Kansas City Chiefs article about a game played with Los Angeles Chargers in October 2026. I modified the python script to include retreival tools learned in Module 1 to pull text directly from the Chiefs website in order to understand the effectiveness of text preprocessing.

## Tools and Methods

The project uses:

- Python for text processing and analysis.
- Local text files for input data.
- Regular expressions for punctuation removal.
- Tokenization for separating text into words.
- Lowercasing for text normalization.
- Stopword filtering for reducing common vocabulary.
- Polars for calculating token frequencies.
- Matplotlib for visualizing preprocessing results.
- Logging for execution records.
- Ruff, ty, and pytest for code verification.
- Zensical and GitHub Pages for published documentation.
- Requests for retrieving webpage content
- BeautifulSoup for extracting text from HTML.

The example script reads text records,
combines them into a corpus,
and applies a sequence of preprocessing operations.

The analysis compares raw and cleaned token counts
and identifies frequently occurring words.

## Technical Modification

I modifed the preexsisting Python script in order to show the percentage of tokens removed while doing preprocesing.  This allowed for a comparison between the original token count and the cleaned token count.

## Verification

A successful execution displays:

    Pipeline executed successfully!

The script records execution details in a project log.

The output includes token counts,
frequency distributions,
and preprocessing comparison charts.

Automated tests provide additional verification
of the project's expected behavior.

The customized project was ran with the following
  uv run python -m nlp.text_processing

This allowed for the Kansas City Chiefs new article to be review, processed, and calculate word frequencies, then generated preprocessing charts.

## Interpretation

Text preprocessing transforms raw language
into a representation suitable for analysis.

Lowercasing, punctuation removal,
and stopword filtering change the resulting
token distribution.

These operations can reduce unwanted noise,
but they may also remove meaningful information.

Understanding these tradeoffs is important
when preparing text for traditional NLP
and modern language-model applications.

One interesting observation is that it reduced the token count by 34.96%.

## Analysis

I applied preprocessing text techniques to a Kansas City Chiefs news article. The text was cleaned with tokenization, lowercasing, punctuation removal, and stop-word filtering. Raw text length was 3,733 characters with the following found: raw tokens - 655, after punctuation removal - 697, and after stop word removal - 426. This netted a 229 token reduction or 34.96% reduction in tokens.

## Documentation Index

- **Home** - this landing page
- [**Project Instructions**](project-instructions.md)
- [**Glossary**](glossary.md)

## Project Links

- [GitHub Repository](https://github.com/johnjamez187/nlp-02-text-preprocessing)
- [Python Script](https://github.com/johnjamez187/nlp-02-text-preprocessing/blob/main/src/nlp/text_preprocessing.py)
- [Jupyter Notebook](https://github.com/johnjamez187/nlp-02-text-preprocessing/blob/main/notebooks/text_preprocessing.ipynb)
- [Project Dataset](https://github.com/johnjamez187/nlp-02-text-preprocessing/blob/main/data/text_data.txt)
- [Kansas City Chiefs News Article](https://www.chiefs.com/news/chiefs-defeat-chargers-22-6-to-move-to-5-0-on-the-season)

## Project Resources

- [Project Instructions](project-instructions.md)
- [Professional Python Guide](https://denisecase.github.io/pro-analytics-02/)
- [Professional Python Project Explainer](https://pup-pack.github.io/professional-python-project-explainer/)
- - [GitHub Repository](https://github.com/johnjamez187/nlp-02-text-preprocessing)
