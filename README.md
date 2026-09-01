\# Regex Job Title Analysis



\## Overview



This project explores the use of regular expressions (regex) for

cleaning, searching, and classifying real-world job titles using

Python.



The project uses the O\*NET Job Titles dataset containing more than

54,000 job-title records.



\## Objectives



\- Clean job-title text using Python and regular expressions

\- Demonstrate common regex patterns

\- Identify patterns within job titles

\- Build a rule-based job-title classifier

\- Evaluate classification performance

\- Analyze classification errors and limitations



\## Technologies



\- Python

\- Pandas

\- Regular Expressions (`re`)

\- Scikit-learn

\- Matplotlib

\- Jupyter Notebook



\## Regex Concepts



The project demonstrates:



\- `^` — beginning of a string

\- `$` — end of a string

\- `.` — any character

\- `\\\\\\\\\\\\\\\*` — zero or more repetitions

\- `?` — optional element

\- `{}` — specified repetitions

\- `()` — grouping

\- `|` — alternatives

\- `\\\\\\\\\\\\\\\\b` — word boundary

\- `\\\\\\\\\\\\\\\\d` — digit

\- `\\\\\\\\\\\\\\\\s` — whitespace



\## Dataset



The project uses the O\*NET Job Titles dataset.



The dataset contains more than 54,000 job-title records.



\## Evaluation



A random sample of job titles was manually labelled to create

ground-truth categories for evaluating the regex-based classifier.



\## Limitations



The classification approach is rule-based and relies on keywords

and regular-expression patterns.



Job titles can be ambiguous, and the same terms can occur across

different occupational categories. Increasing the number of rules

may improve performance on a particular sample while reducing

generalizability.



Therefore, the project focuses on demonstrating regex-based text

processing rather than building a highly optimized classification

system.



\## Project Structure



```text

regex-job-title-analysis/

│

├── data/

│   ├── job\\\\\\\\\\\\\\\_titles.csv

│   └── evaluation\\\\\\\\\\\\\\\_sample.csv

│

├── regex\\\\\\\\\\\\\\\_job\\\\\\\\\\\\\\\_titles.ipynb

├── README.md

└── .gitignore




