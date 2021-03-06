# Text-Analysis-SEC-EDGAR-Data
Objective of this assignment is to extract some sections (which are mentioned below) from SEC / EDGAR financial reports and perform text analysis to compute variables those are explained below. Link to SEC / EDGAR financial reports are given in excel spreadsheet “cik_list.xlsx”. Please add https://www.sec.gov/Archives/ to every cells of column F (cik_list.xlsx) to access link to the financial report.
Example: Row 2, column F contains edgar/data/3662/0000950170-98-000413.txt
Add https://www.sec.gov/Archives/ to form financial report link
i.e. https://www.sec.gov/Archives/edgar/data/3662/0000950170-98-000413.txt

1) Variables:
“Text Analysis.docx” you need to compute following: Section 1.1: Positive score, negative score, polarity score Section 2: Average Sentence Length, percentage of complex words, fog index Section 4: Complex word count Section 5: Word count   In addition to these eight variables, compute two more items: “uncertainty” and “constraining”. These variables are calculated similar to the ones in Section 1.1 or Section 4. Attached the lists of words that are classified as uncertain or constraining.

For uncertainty: “uncertainty_dictionary.xlsx”
For constraining: “constraining_dictionary.xlsx”

That means you need to collect/compute 10 variables in total.

2) Sections:
For each report (financial reports, links available in excel, cik list), we would like these 10 variables calculated for three sections. These are “Management's Discussion and Analysis”, “Quantitative and Qualitative Disclosures about Market Risk”, and “Risk Factors”. If a report does not include any of these sections, leave those fields blank.

In other words, we need 10 x 3 = 30 variables. Attached the spreadsheet “cik_list.xlsx”, which also contains the links to reports. It would be ideal if you could add 30 columns to each row, so that we would have the # rows unchanged after your data collection.

3) Additional Variables: positive/negative and uncertainty/constraining word proportion
The absolute values of “Positive/Negative Scores” are equal to the number of positive/negative words in each section of 10-Q/K; so the (Loughran-McDonald) positive/negative word proportion can be simply calculated as “Positive/Negative Scores divided by Word Count – compute these measure in addition to Polarity Score.  And, the “uncertainty score” and “constraining score” will be also just equal to the number of corresponding words and you can calculate the portion of these words as same as above.  
