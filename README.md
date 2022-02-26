# College Confidential Comparative Disucssions

This repository contains the discussions scraped from [College Confidential Forum](https://talk.collegeconfidential.com/).
The discussions are usually in the format of a thread, first post asking for a comparison between multiple colleges, and the rest of the thread responding to the question.
In total, we have 53 discussions and 2140 comments with annotations.

The discussions were labeled through Amazon Mechanical Turk. The labels presented in the final file is the majority label from three labellers. 
The dataset has 2864 pairwise comparisons in total.  

Cite as Farhad Mohsin, Lei Luo, Wufei Ma, Inwon Kang, Zhibing Zhao, Ao Liu, Rohit Vaish, and Lirong Xia. Making group decisions from natural language-based preferences. In *The 8th International Workshop on Computational Social Choice (COMSOC-2021)*, 2021

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
  - comment_index: Index of the comment in the discussion
  
- **[synonyms.json](/synonyms.json)**
Contains all synonyms that appear in the dataset for each alternative.
