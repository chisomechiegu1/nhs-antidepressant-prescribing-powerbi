# NHS Antidepressant Prescribing in England: A Five-Year Analysis (2021–2025)

An interactive Power BI dashboard analysing five years of antidepressant prescribing across NHS England, covering national volume, cost, drug-level patterns and regional variation.

![Executive Overview](images/executive_overview.png)

## Background

Mental health is an early priority in the NHS 10 Year Health Plan for England. Antidepressants are the single largest prescribed drug category in England, with over 23 million items dispensed quarterly. As prescribing volumes continue to rise, understanding the patterns, costs and regional variation behind these numbers is essential for data-driven NHS decision-making.

## Data Source

NHS Business Services Authority (NHSBSA), Prescription Cost Analysis (PCA) Monthly Data, openly available at [opendata.nhsbsa.net](https://opendata.nhsbsa.net). The data covers January 2021 to December 2025.

**What one row means:** the total number of items dispensed and the total cost for one specific antidepressant drug, in one NHS region, in one calendar month.

## Research Objectives

1. **National volume trend:** How has the total volume of antidepressant prescriptions changed between 2021 and 2025?
2. **Cost vs volume relationship:** How has the total cost changed over the same period, and does it follow the same pattern as volume?
3. **Drug-level analysis:** Which antidepressants are prescribed most frequently, and which cost the NHS the most?
4. **Regional variation:** Which regions show the highest prescribing volumes and costs, and where is the variation greatest?

## Policy Relevance

This analysis supports two NHS strategic goals: the 10 Year Health Plan's focus on mental health as a national priority, and the 2025/26 operational guidance calling for reduced unwarranted variation in prescribing across Integrated Care Boards.

## Tools Used

- Power BI (data modelling, DAX measures, dashboard design)

## Dashboard Pages

| Page | What it shows |
|---|---|
| Executive Overview | Headline items and cost, change since 2021, compound annual growth rates |
| Regional Performance | Cost and items by region, year-on-year change, regional trends |
| Drug Analysis | Top drugs by cost and items, cost share, contribution to cost change |
| Monthly Trends | Monthly cost and items, average cost per item by year, YoY cost change |

## Key Findings

**National trend**
- Total of **443M items** dispensed at a cost of **£1.2bn** over the period.
- Prescribing volume **rose 14.6%** since 2021, from 82.6M to 94.7M items a year (compound annual growth of 3.47%).
- Prescribing cost **fell 23.0%**, from £288M in 2021 to £222M in 2025 (compound annual decline of 6.33%).

**Cost vs volume**
- Volume and cost moved in opposite directions. Average cost per item fell from about £3.50 in 2021 to £2.34 in 2025, so the cost fall reflects lower unit cost rather than lower demand.
- The biggest single drop was in 2022 (-22.02%).

**Drug level**
- **Sertraline** is the top drug by both cost (£263.7M, 25.7% of total cost) and volume (115M items).
- **Venlafaxine** is second by cost (£210.1M, 20.5% share), while **Amitriptyline** is second by volume (78M items).
- Sertraline accounts for **62.9% of the change in total cost**, with its annual cost falling from £91M in 2021 to £33M in 2022.
- Some drugs have a very high cost per item (for example Tranylcypromine at about £1.34K per item) but low volumes, so they add little to total spend.

**Regional variation**
- **North East and Yorkshire** and the **Midlands** have the highest costs (£0.23bn each). North East and Yorkshire also has the highest item volume (98M) and the fastest growth in items (+7.87% in the latest year).
- **London** shows the largest cost reduction (-10.68%) and a fall in items (-3.58%).
- **South West** has the lowest cost (£0.12bn) and items (42M).

## Repository Structure

```
├── README.md
├── NHS_Antidepressant_Prescribing.pbix
├── images/
│   ├── executive_overview.png
│   ├── regional_performance.png
│   ├── drug_analysis.png
│   └── monthly_trends.png
└── data/   (optional, if file size allows)
```

## Dashboard Screenshots

### Regional Performance
![Regional Performance](images/regional_performance.png)

### Drug Analysis
![Drug Analysis](images/drug_analysis.png)

### Monthly Trends
![Monthly Trends](images/monthly_trends.png)

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Use the Year, Region and Drug slicers on each page to explore the data.

## Limitations

- The data records items dispensed and cost, not patients, so it cannot show how many people are prescribed antidepressants.
- Cost reflects the recorded cost at the time of dispensing and may be affected by pricing changes over the period.

## Author

**Anthony**
Medical Laboratory Scientist | Data Analyst
[LinkedIn](https://www.linkedin.com/) · [GitHub](https://github.com/)
