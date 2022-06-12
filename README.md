# thesis_project

Welcome to my repository for my undergraduate honor's thesis project! This 2021 study examined how children learn to answer questions containing 'who' and 'how' in the context of negation ('n't' and 'not') as well as in the context of communication verbs with differing control properties ('ask' and 'promise'). Here, you can find the original assets for the project (audio and video) and the Lookit protocol generator. Soon, these files will be joined by the dataset, data wrangling scripts in PowerQuery and R, and an RMarkdown document with the code used for statistical analysis.  

Originally, the study was launched on **[Lookit.com](https://lookit.mit.edu/)**, an experimental platform designed by MIT's Early Childhood Cognition Lab. The full thesis, which achieved a Highest Honors designation, is available through the **[Smith College Scholarworks](https://scholarworks.smith.edu/theses/2358/)**.

For reference, the procedure was approximately as follows:
1. Experiment design and stimuli creation
2. Coding the Lookit protocol generator in JSON and JavaScript
3. Collect data from child and adult participants
4. Download, compile, and clean CSV data files using Excel PowerQuery
5. Import data and run statistical analysis in RStudio
6. Complete written thesis and defense with findings  
  
    
    

## File & Folder Overview

### Assets

#### img

All original images used in the study for the stories and buttons.

#### mp3

All original audio stimuli, in MP3 format.

#### oog

All original audio stimuli, in OOG format.

---

### Logistics

#### LICENSE

The MIT license for the Lookit software.

#### README.md

The Markdown code for the description you're reading.

---

### Analysis
There were two Excel sheets in the same workbook that were used to clean and consolidate the data. As a source folder for PowerQuery, we used the zipped folder of CSV files downloaded from Lookit. 

#### data_cleaning_frameChoices_NEW.pq

This script set up the `frameChoices` sheet compiled the code of all possible responses or buttons that participants could use. 

#### data_cleaning_selectedImages_NEW.pq

This script set up the `selectedImages` sheet to compile all choices made by participants during the study.

---

### Lookit
#### protocol_generator_dec_2021.js

The code to generate the study's Lookit protocol, including the randomization script for the JSON frames.

