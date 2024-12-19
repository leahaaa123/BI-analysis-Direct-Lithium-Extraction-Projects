## Project Purpose
This project aims to provide detailed information on Direct Lithium Extraction (DLE) technologies and evaluate the investment potential across key lithium-producing regions. The goal is to assist investors in understanding the productivity of DLE technology for lithium extraction mining projects across various regions. 
The analysis incorporates both quantitative insights derived from Power BI dashboards and qualitative research, and the challenges and benefits associated with DLE mining projects

## Business Problem
1. Regional Investment Challenge:
   Determining the most attractive country or mining project for investment is challenging for investors due to a lack of comprehensive information and difficulties in comparing mining projects.
2. DLE Technology Evaluation Challenge:
   Identifying the most efficient and cost-effective Direct Lithium Extraction (DLE) technology for specific projects and regions is challenging.

## Work Flow
Step1. Data Modeling  →  Step2. Data Integration  →  Step3. Dashboard Development  →  Step4. Data Analysis 


### STEP1. Data Modeling
![ER Diagram](https://github.com/user-attachments/assets/3a9dc848-b148-47c0-86ab-6e750868944b)
### STEP2. Data Integration
Created database in SSMS then conducted ETL process with VIsual studio 
Download SQL file


### STEP3. Dashboard Development 
[Download file](https://github.com/leahaaa123/Portfolio-Public/blob/main/DLE%20project%20analysis%20dashboard.pbix)

![Screenshot1 (1)](https://github.com/user-attachments/assets/bf73045f-20d1-4ba2-bd7b-791cbddcf9f2)
### STEP4. Data Analysis 
#### 1) Production Efficiency Analysis
- (Country) When comparing lithium deposits by region, Argentina possesses favorable conditions both quantitatively and qualitatively, with high lithium resource volumes and concentrations. In contrast, North America has relatively lower resource volumes and concentrations.
![image01](https://github.com/user-attachments/assets/718963c8-85b9-41d3-b802-5197d49562fc)

- (DLE method) The adsorption method shows a trend of increasing recovery rates as lithium concentration rises, while the ion exchange method maintains high recovery rates even in projects with lower lithium concentrations.
   ![image](https://github.com/user-attachments/assets/3fa3d19a-524e-4ce0-b4a0-e97375341710)

- (Project)  North American projects like Clearwater and Boardwalk in Canada, which utilize the ion exchange method, have achieved high lithium recovery rates despite the low lithium concentrations.

  ![image](https://github.com/user-attachments/assets/68314b3d-b17d-42dc-a1d6-94758684e9d8)
  
#### 2) Investment Efficiency Analysis
This analysis assesses investment efficiency based on capital expenditure intensity per annual production volume and operational expenditure.
- (DLE method Comparison) The ion exchange method, being at an early stage of commercialization, has a higher average capital expenditure intensity ($68,237/ton) and annual OPEX ($5,502/ton) compared to the adsorption method.
 ![image](https://github.com/user-attachments/assets/f81c6b80-dbdd-4d31-9d36-2afa11ffca40)

- (Country Comparison) Canada shows the highest average capital expenditure intensity ($77,081/ton), indicating substantial initial investment requirements, while the United States has a comparatively higher annual OPEX at $5,469/ton for ongoing operations. Conversely, Chilean projects exhibit low capital expenditure intensity and operational costs, offering a competitive edge in terms of cost efficiency.
  ![image](https://github.com/user-attachments/assets/ac1dcfe9-d884-48bc-b532-336aca7f30d1)

## Insights and Recommendation

#### key investment insights:
1) Efficiency and Versatility: 
DLE methods, particularly ion exchange, show high recovery rates even at lower lithium concentrations, making them viable in diverse regions, including North America. Argentina has the most favorable lithium resources, while Canada’s low-concentration projects perform well due to DLE.

3) Cost Analysis: 
Ion exchange, while promising, currently involves higher CAPEX and OPEX than adsorption. Canada has the highest CAPEX needs, while the U.S. faces higher OPEX. In contrast, Chile’s low-cost projects present strong cost-efficiency and scalability for investors.
4) Investment Potential: 
Despite higher costs, DLE expands extraction options beyond high-lithium regions and offers future cost reductions as the technology matures. Investors should weigh strategic market access in North America against cost advantages in regions like Chile and Argentina.
#### Recommendation: 
Investors should consider North American Ion exchange type DLE projects for market access, while Chile and Argentina offer more cost-effective, resource-rich options. Monitoring DLE’s commercialization progress will be key to realizing potential long-term savings and returns.
