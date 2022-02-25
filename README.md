# College Confidential Comparative Disucssions

This repository contains the discussions scraped from [College Confidential Forum](https://talk.collegeconfidential.com/).
The discussions are usually in the format of a thread, first post asking for a comparison between multiple colleges, and the rest of the thread responding to the question.
In total, we have 53 discussions and 2140 comments with annotations.

The discussions were labeled through Amazon Mechanical Turk. 
At most, each comment has 3 labels, but in some cases we faced ties in the labels. In total, we have 5860 labels for our dataset.

The dataset was presented in **Making Group Decisions from Natural Language-Based Preferences** (*Farhad Mohsin, Lei Luo, Wufei Ma, Inwon Kang, Zhibing Zhao, Ao Liu, Rohit Vaish, Lirong Xia*)

### Files/Directories:

- **[text](/text)**
contains all the discussions in an unstructured format.

- **[json/entities](/json/entities)**
contains the pre-defined entities for each discussion

- **[json/comments](/json/comments)**
contain the discussion in a json format
<!-- * TODO: combined/ contains separate directory for each annotated discussion. But the file is incomplete, with the "comment" column empty. Need to fix this -->

- **[all_annotations.csv](/all_annotations.csv)**
has all annotations from all annotators. i.e., each pair of alternative will have multiple annotations (from different annotators) for each comment
- **[/aggregate_labels.csv](/aggregate_labels.csv)** 
has one annotation for each pair of alternative in each comment (the majority annotation)
