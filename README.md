# India's EV Market Evolution (2019-2024)
## Project Overview
This project analyzes the adoption of Electric Vehicles (EVs) and the availability of charging infrastructure in India from 2019 to 2024. The data has been collected from official government sources and analyzed using Python (Pandas), MySQL, and Power BI. The study specifically focuses on major EV companies operating in India, including Tata Motors, Mahindra Electric, Ola Electric, Ather Energy, MG Motors, and Hyundai.
## Technologies Used 
- 	**Python (Pandas):** Data cleaning, preprocessing, and analysis.
- 	**MySQL:** Database storage and query execution.
- 	**Power BI:** Data visualization and dashboard creation.
## Data Sources 
The datasets were obtained from official sources, including:
- [Press Information Bureau - Government of India](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2036276)
- [Data.gov.in - Electric Vehicle Data](https://www.data.gov.in/keywords/Electric)
  ## Project Components
### 1. Data Acquisition & Storage
- **Collected multiple datasets** related to EV sales, charging infrastructure, and adoption trends.
- **Stored structured data** in MySQL for efficient querying and management.
- **Cleaned and formatted data** using Python's Pandas library.

### 2. Data Analysis with Python & SQL
The following analyses were conducted on EV companies such as **Tata Motors, Mahindra Electric, Ola Electric, Ather Energy, MG Motors, and Hyundai**:
- **State-wise EV Market Share**
- **Top 10 EV Companies by Total Sales**
- **EV Charging Infrastructure Analysis**
- **Year-over-Year EV Sales Growth**
- **States Needing More Charging Stations**
- **Popular EV Types (2-Wheelers, Cars, etc.)**
- **Leading EV Companies in the 2-Wheeler and 4-Wheeler Segments**

Sample SQL queries used in the analysis:
```sql
SELECT state_ut, total_ev, total_vehicles_sold, 
       (total_ev / total_vehicles_sold) * 100 AS market_share 
FROM total_evs 
ORDER BY market_share DESC 
LIMIT 10;
```
## 3. Data Visualization with Power BI
Interactive dashboards created include:
- **EV Adoption Trends Dashboard**
- **Charging Infrastructure Availability**
- **State-wise EV Market Insights**
- **Yearly Sales Growth Analysis**

## Key Insights
- **Growing EV adoption** but uneven distribution of charging stations.
- **Some states have a high EV density** but lack sufficient charging infrastructure.
- **EV sales have increased significantly** from 2019 to 2024.
- **Tata Motors and Ather Energy** have seen the most consistent growth among competitors.
- **Ola Electric and MG Motors** have rapidly expanded in the last two years.

## How to Run the Project
### Prerequisites:
- Install **Python** (3.8 or later) and required libraries (`pandas`, `mysql-connector-python`).
- Install **MySQL Server** and create a database.
- Install **Power BI Desktop** for visualization.

### Steps:
1. Clone the repository and navigate to the project folder.
2. Load the dataset into MySQL using provided scripts.
3. Run Python scripts for data processing.
4. Open Power BI and connect to the MySQL database.
5. Load Power BI reports to explore visualized insights.

## Future Scope
- **Machine Learning Models** for EV adoption prediction.
- **Real-time Data Integration** for continuous analysis.
- **Geospatial Mapping** to identify areas needing infrastructure improvement.

## Conclusion
This project provides deep insights into India's **EV growth trends and charging infrastructure gaps**, helping policymakers and businesses **make data-driven decisions**. The study highlights the market performance of key EV manufacturers such as **Tata Motors, Mahindra Electric, Ola Electric, Ather Energy, MG Motors, and Hyundai**, offering a competitive analysis of their contributions to India's EV landscape.

---
For detailed analysis, refer to the **SQL queries** and **Power BI dashboards** used in this project.
