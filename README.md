# Indian General Elections 2024

This project delivers a comprehensive analysis of the **Indian General Elections 2024**, using **structured SQL queries** for data processing and a **Power BI dashboard** for impactful visualization. It provides deep insights into party performance, alliance dominance, voting patterns, and constituency-level breakdowns.

---

## Project Components

| File | Description |
|------|-------------|
| `Indian_Election_Analysis.sql` | SQL script to extract, transform, and analyze election data. |
| `India_General_Election_Results.pbix` | Power BI dashboard for interactive visual storytelling. |

---

## Tech Stack

- **SQL** : For querying, data aggregation, transformations.
- **Power BI**: For building dynamic dashboards and charts.
- **Data Sources**: Election results including constituencies, votes, candidates, parties, alliances.

---

## 🔍 Analytical Objectives

- Calculate **total and state-wise seat availability** and **wins**.
- Analyze **performance of NDA, I.N.D.I.A, and OTHER alliances**.
- Identify **top winning candidates, highest vote margins**, and **EVM vs Postal vote breakdowns**.
- Highlight **state-specific insights** (e.g., *Uttar Pradesh*, *Bihar*, *Mathura*, *Amethi*).
- Determine **winning vs runner-up candidates** per constituency.

---

## Key Insights

### 1. Total Seats and State-Wise Distribution
- India had **543** parliamentary seats contested.
- States like **Uttar Pradesh**, **Maharashtra**, and **West Bengal** contributed the highest number of seats.

### 2. Alliance Performance
- **NDA** emerged as the leading alliance with the highest number of seats.
- **I.N.D.I.A.** alliance showed strong performance in southern and eastern states.
- Remaining seats were won by **Other regional parties** and independents.

### 3. Top Candidates and Margins
- Candidates from **BJP, INC, and AITC** secured top ranks in terms of **EVM votes**.
- Constituencies like *Amethi* and *Mathura* displayed **significant victory margins**.

### 4. Voting Method Analysis
- Detailed distribution between **EVM and Postal Votes** for each candidate.
- Example: **Mathura** showed a strong skew toward EVM-based voting.

### 5. Winners vs Runner-Ups by Constituency
- Implemented `ROW_NUMBER()` logic to identify both winners and runner-ups in **each constituency** (e.g., Bihar).

---

## Notable SQL Concepts Used

- **Joins & Aggregations**: To merge party, state, and constituency data.
- **CTEs & Window Functions**: For advanced analytics like ranking candidates.
- **CASE Statements**: For classifying party alliances.
- **Data Transformations**: Updating table fields for categorization and comparison.

---

## Power BI Dashboard Highlights

- **Overview Section**: Alliance-wise seat share, party-wise comparisons.

<img width="629" height="353" alt="image" src="https://github.com/user-attachments/assets/3e02dc1a-380b-48bb-b289-59be06c56042" />

---

- **State-wise Map View**: Interactive choropleth highlighting winning alliances.

<img width="626" height="347" alt="image" src="https://github.com/user-attachments/assets/7a99eb26-84b3-49e0-a404-1e6e5bba5d69" />

---
- **State-wise Analysis**: Determining all the winning alliances and parties of that alliance, party wise seat share by state.

<img width="626" height="347" alt="image" src="https://github.com/user-attachments/assets/21ff75bc-4fe9-433c-8575-526de0366b56" />

---  
- **Constituency-wise Analysis**: Highlighting the constituency wise details of candidates (winnig candidate, runner up candidate), votes and parties they belong to.

<img width="631" height="347" alt="image" src="https://github.com/user-attachments/assets/322bb960-dcfb-429b-90ab-ae7f7d911454" />

---
- **Details in Grid**: This is the full detail of winning candidates by votes and parties they belong to. 

<img width="628" height="352" alt="image" src="https://github.com/user-attachments/assets/c8b3e414-fb60-42a0-bac1-dffad3c8f900" />



---

## Author's Note

> This project was built as a full-stack data analysis case study to explore how **data analytics can explain complex electoral dynamics**. It also showcases my ability to work with **real-world datasets**, **perform SQL transformations**, and **deliver insights via BI tools**.

---
