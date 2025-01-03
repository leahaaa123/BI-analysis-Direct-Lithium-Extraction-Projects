## Project Purpose
This project aims to deliver comprehensive insights into Direct Lithium Extraction (DLE) technology through a combination of qualitative and quantitative analysis. Focused on data visualization using Power BI, the project explores key aspects of lithium extraction, production efficiency, and regional investment landscapes, with the following goals:
- Enhance understanding of DLE
- Analyze regional and methodological differences
- Support data-driven decision-making

## Business Problem

1) Lithium demand vs. supply gap

The global shift toward renewable energy and electric vehicles has triggered an unprecedented surge in lithium demand. However, traditional extraction methods face critical challenges, including environmental concerns, and geographic constraints. For example, evaporation ponds, primarily used in South America, and hard-rock mining in Australia dominate production but are limited in scalability and resource accessibility.


2) Inefficiencies in extraction technologies

Current lithium extraction methods, such as evaporation ponds and hard-rock mining, are time-consuming, and economically inefficient in regions with low lithium concentrations. This highlights the need for innovative approaches like Direct Lithium Extraction (DLE).

3) Geographic disparities in resource quality

Regions like South America, particularly Argentina and Chile, boast high-quality lithium resources with favorable extraction conditions. In contrast, North America’s resources are less concentrated, posing additional challenges for efficient production.

## Work Flow
### Step1. Data Modeling  →  Step2. Data Integration  →  Step3. Dashboard Development  →  Step4. Data Analysis 


#### [STEP1] Data Modeling
A visual representation of the database schema is created, mapping relationships between tables such as Company Database, Project Database, Technology Database, and Efficiency Metrics Database.

<img src="https://github.com/user-attachments/assets/b3faf9a3-d1a5-4ada-b809-6c88b1f663dc" width="700"/>
                         

#### [STEP2] Data Integration
In this step, data from multiple sources is combined, cleaned, and transformed to create a unified dataset that aligns with the project's goals.

 (1) Database Setup in SSMS: A comprehensive database was created in SQL Server Management Studio (SSMS), ensuring the schema design supports efficient data integration.
 
 (2) ETL Process with SSIS: The ETL (Extract, Transform, Load) process was conducted using SSIS, leveraging data flow tasks for seamless extraction, transformation, and loading operations.
 (3) Data Cleaning and Transformation: Data from Company, Project, Technology, and Efficiency Metrics Database was cleansed, and structured for consistency and accuracy.
 
 (4) Data Linking and Relationships: Foreign key relationships were established between tables, connecting key data points such as projects, companies, and technologies.
 
 (5) Data Analysis Integration: The integrated dataset was prepared for effective data analysis in Power BI, ensuring all key metrics related to lithium extraction and production are easily accessible for insights and visualization.

[File Download]

#### [STEP3] Dashboard Development 
[Dashboard Download](https://github.com/leahaaa123/Portfolio-Public/blob/main/DLE%20project%20analysis%20dashboard.pbix)

<img src="https://github.com/user-attachments/assets/409c324d-af88-45d7-9693-ec83b7801709" width="500"/>    <img src="https://github.com/user-attachments/assets/82bed174-1f8f-45f5-b9d4-369056b25f85" alt="Dashboard Screenshot" width="500"/>


#### [STEP4] Data Analysis 

#### 1) Regional Comparison of Lithium Deposits
Argentina demonstrates a significant advantage in lithium resources, both in terms of quantity and quality, with higher lithium resource volumes and concentrations compared to North America. In contrast, North America exhibits lower lithium resource volumes and concentrations, presenting inherent challenges for extraction efficiency.

<img src="https://github.com/user-attachments/assets/718963c8-85b9-41d3-b802-5197d49562fc" alt="Dashboard Screenshot2" width="600"/>

#### 2) Production Efficiency Using DLE Methods
##### Lithium Recovery Trends by Method
The adsorption method displays improved lithium recovery rates as lithium concentration increases, while the ion exchange method delivers consistently high recovery rates, even in environments with lower lithium concentrations.

<img src="https://github.com/user-attachments/assets/d5673273-f170-4bb0-8db5-43b63d195df2" width="600"/>

##### Performance in North America
Despite North America’s relatively lower lithium concentrations, projects such as Clearwater and Boardwalk in Canada, which employ the ion exchange method, have achieved high recovery rates, showcasing the effectiveness of DLE in enhancing production efficiency.

<img src="https://github.com/user-attachments/assets/ce40bb57-0af6-45b0-bb79-ba2505fc026d" width="600"/>

#### 3) Investment Efficiency of DLE Methods
##### DLE Method Comparison
Among DLE methods, the ion exchange technique, being in the early stages of commercialization, exhibits higher capital expenditure (CAPEX) intensity, averaging $68,237/ton, and operational expenditure (OPEX) at $5,502/ton, compared to the more mature adsorption method.

<img src="https://github.com/user-attachments/assets/54c29082-c7e1-41bb-ac9c-b7b29b44698e" width="600"/>

##### Regional Investment Landscape
North American projects highlight significant investment challenges: Canada reports the highest CAPEX intensity at $77,081/ton, requiring substantial upfront investment, while the United States faces comparatively higher OPEX at $5,469/ton for ongoing operations. Conversely, Chilean projects demonstrate low CAPEX and OPEX, presenting a more cost-efficient model that strengthens their competitive position.

<img src="https://github.com/user-attachments/assets/485aae16-93f7-4588-890c-bbedfd2ffe69" alt="Dashboard Screenshot6" width="600"/>

## Insights and Recommendation

#### key investment insights:
1) Efficiency and Versatility
   
DLE methods, particularly ion exchange, demonstrate exceptional recovery rates even in regions with lower lithium concentrations, such as North America. This makes DLE a transformative technology for expanding viable lithium extraction across diverse geographies. Argentina emerges as the most resource-rich region, while Canadian projects effectively leverage ion exchange to overcome lower resource concentrations

2) Economic Feasibility 

While the ion exchange method shows promise, it currently involves higher CAPEX and OPEX compared to adsorption. Canada has the highest CAPEX requirements, demanding substantial upfront investment, while the U.S. experiences elevated OPEX. Conversely, Chile offers the most cost-efficient projects, characterized by low CAPEX and OPEX, making it a compelling option for scalability and long-term profitability.


#### Recommendation: 
1) North American Opportunities
   
Invest in North American ion exchange-based DLE projects to capitalize on strategic market access and the ability to process lower-concentration resources. These projects position investors to benefit from growing lithium demand and the eventual cost optimization of DLE technology.

2) Cost-Efficient Alternatives

Consider prioritizing investments in Chile and Argentina for their abundant, high-quality resources and significantly lower extraction costs. These regions offer an immediate path to competitive returns and scalability.

3) Technology Monitoring

Maintain close monitoring of DLE commercialization progress. As technological advancements reduce CAPEX and OPEX, ion exchange projects may become increasingly competitive, offering greater returns over the long term.
