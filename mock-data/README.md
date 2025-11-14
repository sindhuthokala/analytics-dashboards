# Mock Data for Analytics

This folder holds small synthetic datasets that power example dashboards and queries in this repo.

## 📘 Why Mock Data?
To keep real customer data private while still demonstrating:
- How I would structure tables
- What fields I care about
- How I join datasets for BI
- The kind of metrics I track

## 📂 Example Mock Datasets
- `customers.csv` – customer IDs, segments, signup dates, churn flags
- `events.csv` – event-level data (page views, clicks, conversions)
- `transactions.csv` – purchases, revenue, product SKUs
- `cdp_profiles.csv` – unified profile attributes

They can be generated using:
- Python (pandas + Faker)
- Excel / Google Sheets
- Simple manual construction

Each dataset includes:
- A short description in the header or in a separate `.md` file
- Clarification of how it's meant to be used

