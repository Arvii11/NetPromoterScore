# NetPromoterScore
NPS - customer loyalty and satisfaction measurement taken from a survey asking customers how likely they are to recommend the product or service to others on a scale of 0-10.

## Description
This code analyzes survey data from a file named 'survey.txt', which contains customer scores ranging from 0 to 10 indicating their likelihood to recommend a product or service. It computes the Net Promoter Score (NPS) to evaluate customer loyalty and satisfaction.

## Usage
1. Ensure 'survey.txt' file is in the same directory as the script.
2. Run the script to load the survey data and perform analysis.
3. Check the output for the computed NPS value.

## Code Overview
- The script loads survey data from 'survey.txt' into a NumPy array.
- It calculates basic statistics such as the minimum and maximum scores, and identifies detractors (scores <= 6) and promoters (scores >= 9).
- The Net Promoter Score (NPS) is calculated as the percentage of promoters minus the percentage of detractors.

## Results
- Total number of responses: 1167
- Number of promoters (score >= 9): 609
- Number of detractors (score <= 6): 332
- Net Promoter Score (NPS): 23.74%

## Dependencies
- NumPy library is required for data manipulation and analysis.

