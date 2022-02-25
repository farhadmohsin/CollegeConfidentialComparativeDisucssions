# College Confidential Comparative Disucssions

This repository contains the discussions scraped from [College Confidential Forum](https://talk.collegeconfidential.com/).
The discussions are usually in the format of a thread, first post asking for a comparison between multiple colleges, and the rest of the thread responding to the question.
In total, we have 53 discussions and 2140 comments with annotations.

The discussions were labeled through Amazon Mechanical Turk. 
We have 2864 annotations for each 
The dataset was presented in **Making Group Decisions from Natural Language-Based Preferences** (*Farhad Mohsin, Lei Luo, Wufei Ma, Inwon Kang, Zhibing Zhao, Ao Liu, Rohit Vaish, Lirong Xia*)

### Files/Directories:

- **[Data file](/cc_raw_data.csv)**
contains all the discussions in an unstructured format.
**Columns:**
  - Raw_text: contains unfiltered text
  - Label: Aggregate label from Mturk
  - Alt_a: Name of first alternative being compared
  - Alt_b: Name of second alternative being compared
  - n_colleges: Number of colleges being discussed in the original thread
  - discussion_title: Title and unique identifier of College Confidential Dataset
  - discussion_index: Index of the comment in the discussion
  - processed_text: Processed version of the text.

- **[synonyms.json](/synonyms.json)**
Contains all synonyms that appear in the dataset for each alternative.
