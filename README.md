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

The above table shows that about 32% of the posts are biased against either Palestine, Israel, Both, or Others, most of the bias against Palestine originated from French posts.

| Class                        | Ar   | En   | He  | Fr  | Hi  | Total |
| ---------------------------- | ---- | ---- | --- | --- | --- | ----- |
| Propaganda Must be deleted   | 332  | 488  | 382 | 461 | 396 | 2059  |
| Propaganda May be deleted    | 192  | 191  | 266 | 348 | 277 | 1274  |
| Propaganda not to be deleted | 451  | 422  | 265 | 648 | 436 | 2522  |
| Not propaganda               | 1033 | 1021 | 882 | 649 | 977 | 4562  |
| Not applicable               | 48   | 11   | 17  | 16  | 24  | 116   |
| Unclear                      | 104  | 27   | 48  | 38  | 50  | 267   |
| Total                        | 2160 | 2160 | 2160 | 2160 | 2160 | 10800 |

Similarly, this table shows that 54% of the posts are classified as propaganda, either must/may/not be deleted. The majority of the propaganda originated from French posts.

## Corpus Download

The `data` directory in this repo contains four groups of sheets:

(a) Main and IAA-(1..4):  These are the annotation sheets.

Main has 90% of the posts; and IAAs have 10% in repetition. 
IAA is inter-annotator agreement.  IAA sheets are used to allow for  measuring inter-annotator consistency.
For better results its preferred to at least use IAA-1 and IAA-2. Copies are provided for IAA-3 and IAA-4. Each annotator must be given a unique ID (1, 2, 3, 4), and provide their details in the Annotation Team Sheet.
All these sheets have the following columns:

  * Batch: Batch id ranging from B01 to B15.
  * Source Language: Original language of the text - Arabic, English, Hebrew, French, and Hindi
  * ID: A unique identifier per Source Language
  * Type: MAIN or IAA
  * Text: Message text to annotate
  * English MT: machine translation of text to English
  * Arabic MT: machine translation of text to Arabic
  * Annotator ID: Unique identifier per annotator (as listed in the 'Annotation Team' sheet)
  * Bias: Bias subtask annotation labels: Unbiased, Biased against Palestine, Biased against Israel, Biased against both Palestine and Israel, Biased against others, Unclear, Not Applicable
  * Propaganda: Propaganda subtask annotation labels: Propaganda, Not Propaganda, Unclear, Not Applicable
 

(b) Status: This sheet includes an automatically updated record of completing the annotations to help you track your progress.

  * Batches: Batch id ranging from B01 to B15. 
  * Sub-Batch: MAIN or IAA
  * Bias #: number of completed posts
  * Propaganda #: number of completed posts
  * Bias %: percentage of completed posts
  * Propaganda %: percentage of completed posts

(c) Annotation Team: This sheet must be filed by every annotation team to provide the following information.

  * Team Name: Pick a cool and inspiring name!
  * Subtask: Bias, Propaganda
  * Annotator ID: A unique identifier (1,2,3,4) for each annotator. Annotar n should finish IAA-n sheet.  The annotators ID for Bias and Propaganda do not need to align.
  * Arabic Source Annotation Language: The language the annotator used to annotate the Arabic source posts (e.g., the annotator can read the Arabic or the English MT.)
  * Hebrew Source Annotation Language: The language the annotator used to annotate the Hebrew source posts (e.g., the annotator can read the Arabic or the English MT.)
  * French Source Annotation Language: The language the annotator used to annotate the French source posts (e.g., the annotator can read the Arabic or the English MT.)
  * Hindi Source Annotation Language: The language the annotator used to annotate the Hindi source posts (e.g., the annotator can read the Arabic or the English MT.)
  * English Source Annotation Language: The language the annotator used to annotate the English source posts (e.g., the annotator can read the Arabic or the English MT.)
  * Native Language: of the Annotator.
  * Gender: of the Annotator (defined as they prefer).
  * Country of Origin: of the Annotator (could be more than one). 
  * Education Level: of the Annotator.
  * Contribution: Main  (Do not edit this column, it will be updated automatically)
  * Contribution: IAA    (Do not edit this column, it will be updated automatically)

(d) Our Bias/Propaganda Guidelines: These sheets are to be filled by the team members with detailed annotation guidelines covering the following subtasks:

  * Define the Objective: Outline the purpose of this specific task.
  * Describe the Task: Provide a detailed task description with correct examples.
  * Establish Categories: List and define all annotation categories/tags.
  * Detailed Category Guidelines: Explain application criteria for each category/tag, with examples.
  * Include Examples: Offer examples for correct application and common mistakes.
  * Outline the Process: Describe the step-by-step annotation process and tools used.
  * Set Quality Standards: Define expectations for accuracy and consistency, along with quality check procedures.
  * Handle Ambiguities: Provide guidance on ambiguous cases and a protocol for seeking clarification.
  * Ensure Consistency: Implement measures for annotator consistency and recommend calibration sessions.
  * Ethical Considerations: Highlight unbiased annotation practices and handling of sensitive data.
  * Training and Support: Detail training procedures and support resources for annotators.
  * Review and Update: Schedule guideline reviews for updates based on feedback and new insights.
  * Feedback Mechanism: Include a system for annotator feedback to refine guidelines and processes.

    
Clone this repo

    git clone https://github.com/SinaLab/OffensiveHebrew

## Citation

Lina Duaibes, Areej Jaber, Mustafa Jarrar, Ahmad Qadi, Mais Qandeel: [Sina at FigNews 2024: Multilingual Datasets Annotated with Bias and Propaganda](https://www.jarrar.info/publications/DJJQQ24.pdf). In Proceedings of the Second Arabic Natural Language Processing Conference (ArabicNLP 2024), Bangkok, Thailand. Association for Computational Linguistics.
