# Asteria Space Station | Safety Analytics

A Power BI portfolio project analyzing synthetic workplace injury data from a fictional commercial space station.

**Author:** Kelsey Cronce  
**Tools:** Power BI, Power Query, DAX, Microsoft Excel  
**Period:** 2083–2087  
**Dataset:** 1,250 injury cases across eight operational divisions

<img width="1288" height="709" alt="asteria-overview" src="https://github.com/user-attachments/assets/9bf0ff94-8de9-4c36-aad6-f12433a34be6" />


## Business Question

Where should station leadership prioritize injury prevention, based on injury frequency, severity, and patterns across divisions?

## Approach

I compared injury counts, exposure-adjusted rates, and injury outcomes across divisions, then investigated EVA & Exterior Operations through annual trends, event categories, occupations, incident descriptions, and corrective-action records.

## Key Findings

- EVA had the highest five-year TRIR (8.65) and DART rate (2.01), compared with station-wide rates of 3.69 and 0.71.
- Overexertion accounted for 50 of EVA’s 92 days away from work (54%).
- Three exterior access equipment inspection cases accounted for all 50 overexertion-related days away across 2085–2087.
- A separate fatal maintenance incident occurred in 2086. Its hazardous-energy-related corrective action was recorded as Open.

## Recommendations

Prioritize follow-up on the fatality-related safeguards and energy-isolation actions. Assess the physical demands of exterior access equipment inspections and follow up on handling-method and mechanical-assistance evaluations.

Corrective-action status alone does not establish implementation or effectiveness.

## Data and Model Validation

- Checked incident IDs for missing and duplicate values.
- Reviewed incident dates and days-away and restricted/transferred-day fields.
- Corrected annual rate filtering so case counts and exposure hours covered the same year.
- Resolved an inactive occupation relationship that caused totals to repeat across occupations.

## Project Files

- [Read the case study]("C:\Users\kelc2\OneDrive\Desktop\Asteria Project\Asteria Space Station Report.pdf")
- [Download the Power BI report]("C:\Users\kelc2\OneDrive\Desktop\Asteria Project\Asteria_Safety_Analytics.pbix")
 
## How to Explore

Read the case study PDF for the analytical narrative. Download the PBIX file and open it in Power BI Desktop to explore the report and model.

Refreshing the report requires access to its source Excel files and updating their local file paths.

## Limitations and Disclosure

All organizational, incident, and exposure data are synthetic and were generated with ChatGPT for this project. Findings do not represent an actual workplace.

The detailed investigation focused on EVA. Occupation-specific exposure hours were unavailable, so occupation counts do not establish comparative injury rates.

The reviewed records do not establish root causes or corrective-action effectiveness. The improvement in 2087 cannot be attributed to the recorded actions.
