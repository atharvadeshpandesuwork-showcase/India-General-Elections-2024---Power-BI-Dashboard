## 📂 About the Dataset

#### The data is derieved from Election Commision of India website.

### Dataset Tables

#### Constituencywise_results.csv
Purpose: Stores the final election outcome for each Lok Sabha Constituency and serves as the primary fact table in the the data model.

Key Use Cases
- Winning Candidate Analysis.
- Seat Distribution Analysis.
- Alliance performance tracking.
- Victory Margin Analysis.

Key Fields
- Constituency ID
- Parliment Constituency
- Winning Candidate
- Party ID
- Total Votes

---

#### Constituencywise_details.csv
Purpose: Contains detailed vote-level information for every candidate who contested in the constituency.

Key Use Cases
- Candidate performance analysis.
- Runner-up analysis.
- Vote share calculations.

Key Fields
- Candidate Name
- Party
- EVM Votes
- Postal Votes
- Total Votes

---

#### partywise_results.csv
Purpose: Store the total number of seats won by each political party.

Key Use Cases
- Party-wise seat share analysis
- Alliance contribution analysis

Key Fields
- Party ID
- Party
- Won
- Party Short Name (Calculated Column)
- Party Alliance (Calculated Column)
