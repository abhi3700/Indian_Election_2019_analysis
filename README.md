# Indian_Election_2019_analysis
Analysis on India's Lok Sabha Election 2019

## Data
This data is extracted from the election commission website: http://results.eci.gov.in

Data is available in JSON as well as CSV format. `votes.csv` & `votes.json` contains the votes for each candidates along with vote share and other details.

Format of Constituency wise page url.
```markdown
http://results.eci.gov.in/pc/en/constituencywise/Constituencywise${province_id}${constituency_id}.htm?ac=${constituency_id}
```