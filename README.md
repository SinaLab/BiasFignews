# Bias Fignews

A multilingual corpus of 12,000 Facebook posts fully annotated for bias and propaganda. The corpus was created as part of the FigNews 2024 Shared Task on News Media Narratives for framing the Israeli War on Gaza. It covers various events during the War from October 7, 2023 to January 31, 2024. The corpus comprises 12,000 posts in five languages (Arabic, Hebrew, English, French, and Hindi), with 2,400 posts for each language.

## The Distribution of the Bias and Propaganda Classes Across Languages.

Tables below illustrate the distribution of the bias and propaganda classes across languages.

| Class                    | Ar   | En   | He   | Fr   | Hi   | Total |
| ------------------------ | ---- | ---- | ---- | ---- | ---- | ----- |
| Biased Against Palestine | 466  | 514  | 595  | 807  | 534  | 2916  |
| Biased Against Israel    | 94   | 79   | 23   | 19   | 70   | 285   |
| Biased Against Both      | 6    | 7    | 11   | 6    | 14   | 44    |
| Biased Against Others    | 42   | 28   | 53   | 39   | 49   | 211   |
| Unbiased                 | 1371 | 1486 | 1369 | 1212 | 1386 | 6824  | 
| Not applicable           | 49   | 7    | 17   | 20   | 25   | 118   |
| Unclear                  | 132  | 39   | 92   | 57   | 82   | 402   |
| Total                    | 2160 | 2160 | 2160 | 2160 | 2160 | 10800 |

This table shows that about 32% of the posts are biased against either Palestine, Israel, Both, or Others, most of the bias against Palestine originated from French posts.


| Class          | Sub-class    | Count  |
| -------------- | ------------ | ------ |
| Offensive      | Abusive      | 124    |
|                | Hate         | 631    |
|                | Pornographic | 4      |
|                | Violence     | 454    |
| Not offeinsive | -            | 14,681 |
| Total          |              | 15,881 |

Similarly, this table shows that 54% of the posts are classified as propaganda, either must/may/not be deleted. The majority of the propaganda originated from French posts.

## Corpus Download

The data and inter-annotater agremment (IAA) is available in the `data` directory in this repo.


Clone this repo

    git clone https://github.com/SinaLab/OffensiveHebrew

## Citation

Lina Duaibes, Areej Jaber, Mustafa Jarrar, Ahmad Qadi, Mais Qandeel: [Sina at FigNews 2024: Multilingual Datasets Annotated with Bias and Propaganda](https://www.jarrar.info/publications/DJJQQ24.pdf). In Proceedings of the Second Arabic Natural Language Processing Conference (ArabicNLP 2024), Bangkok, Thailand. Association for Computational Linguistics.
