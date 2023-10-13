| [home page](README.md) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |


# Outline
 
## Project Summary:
Medicare—the U.S. health insurance program for people 65 and over, affects the quality of lives of millions of Americans across the U.S.

The insurance system has its strengths, yet it is also flawed.

One of its problems is the fact that healthcare quality provided by Medicare varies across differing counties and hospitals. There may be certain hospitals that may also abuse their funding and have thoughtless or careless expenditures that do not benefit the patients. This creates additional funding challenges and hurts all taxpayers.

The goal of this project is to identify potential issues in Medicare, and also detect certain trends amongst the issues. 

Beginning in October 2014, CMS used the hospital-acquired condition (HAC) quality measures to rank the hospital's performance. The worst-performing quartile in terms of HAC would face a reduction in Medicare fee-for-service payments from the CMS (cms.gov, 2023). 

Public health HAI models (Dixon, 2011) were started by hospital-based clinicians and CDC epidemiologists in the 1960s. The model was built with the goal of identifying HAI, analyzing surveillance data to recognize potential problems, and undergoing implementation to protect hospital patients, staff, and visitors to prevent particular risks. By 1976, the Joint Commission had made it mandatory for accredited hospitals to have infection control programs similar to those recommended by the CDC. In 2008, the U.S. Congress made it mandatory that the Center for Medicare and Medicaid Services (CMS) stop giving hospitals increased payments for the care of patients with HAIs. HAI data points HAI data points have since been strongly tied to the Medicare insurance system (healthaffairs.org, 2015).

As certain hospital evaluation scores such as HAI and HAC directly affect the amount of payment hospitals are able to receive from the Centers for Medicare & Medicaid Services (cms.gov, 2023), this project would also like to detect and address locations and regions where HAI and HAC scores tend to be higher.

I will be focusing on data that documents the years 2021-2023.

## Project Structure:

### Story Arc:
![graph](/4.jpeg)

#### Phase 1:
Patients are grateful to have Medicare as their insurance and have certain expectations that they wish for the insurance to meet.

#### Phase 2:
Patients realize that by receiving healthcare treatments at certain hospitals and locations, they are not only more prone to getting infections but may also run into trouble when trying to have Medicare cover certain treatment expenses. The current raw data from the original database is hard to interpret for many of the patients, and they wish for a visualization that can help them be better choice-makers when it comes to the choice of healthcare hospitals and locations.

#### Phase 3:
Patients and recipients of Medicare appreciate visualizations that convey information which can come in handy when deciding healthcare treatment locations. 



# Initial sketches

Note: The data used for the initial sketches is fabricated and does not correspond to the specific datasets that will be used for the final project.

**Sketch 1: Maps**

I plan on creating maps that may create scales/bins that highlight and differentiate HAI & HAC infection rates amongst different counties or zip codes.
![graph](/6.jpeg)


**Sketch 2: Bar Charts**

I plan on creating bar charts that can express and compare the different HAI & HAC percentages among different counties or zip codes.
![graph](/7.jpeg)


**Sketch 3: Line Chart Combinations**

I plan on creating graphs that combine line charts with maps in order to showcase the trend of the rates regarding different locations over the recorded year.
![graph](/8.jpeg)


**Sketch 4: Line Charts That Include Forecasting**

As there is a good amount of data available for my final project; I plan on creating a line chart that can include forecasts regarding future infection rates.
![graph](/9.jpeg)


**Sketch 5: Line Charts With Regression**

I also plan on making line charts that document the regression trend for the data.
![graph](/10.jpeg)


# The Data
## Data Source
The four datasets are all achieved and retrieved from Data.CMU.gov—the Center for Medicare & Medicaid Services
([link](https://data.cms.gov)).

## Data Usage Explanation
I plan on undergoing some cleaning and analysis with the data in order to discover any trends or phenomenons amongst the relationship between hospital information, medicare spending per beneficiary, HAI scores, HAC scores, and geographic locations.



| Name | URL | Description |
|------|-----|-------------|
|Medicare Spending Per Beneficiary|[link](https://drive.google.com/file/d/1ZLPEfB2agSnhmHblKXW1yg2Ou254-QdQ/view?usp=share_link)|This dataset records the MSPB (Medicare Spending Per Beneficiary) score, which mainly showcases the degrees to which Medicare spends on each specific hospital when compared to the national median (or midpoint) hospital|
|Hospital General Information|[link](https://drive.google.com/file/d/18I-ygqpZ8K3cVmZdaLYA0lUB1KmehTgJ/view?usp=share_link)|This is the dataset that documents a list of all the hospitals that have been registered with Medicare. It also records general information about the hospitals, such as addresses, phone numbers, hospital types, and overall hospital ratings. |
|Healthcare Associated Infections|[link](https://drive.google.com/file/d/1IsjM4xgk_YiJX_l-8bL1prnZjeG6Pp4l/view?usp=sharing)|This dataset documents the HAI (Healthcare-Associated Infection) rate that measures infections that occur while the patient is in the hospital.|
|Hospital-Acquired Condition|[link](https://drive.google.com/file/d/1CIo2EYfXVvcRTdbOgSLmokIw-wlifZcQ/view?usp=share_link)|This dataset documents HAC (Hospital-Acquired Condition) scores from the HAC reduction program. The scores rank hospitals with respect to Hospital-Acquired Condition quality measures, and the total score is calculated as the equally weighted average of hospitals' individual measure scores.|

# Method & Medium
I plan on undergoing data cleaning via Tableau prep and making visualizations via Tableau desktop and Fourish. I will then use Shorthand to display my final project.

# References
1. Caplan, Z. (2023, May 25). U.S. older population grew from 2010 to 2020 at fastest rate since 1880 to 1890. Census.gov.
(https://www.census.gov/library/stories/2023/05/2020-census-united-states-older-populati on-grew.html)

2. News alert CMS releases latest enrollment figures for Medicare, Medicaid, and Children’s Health Insurance Program (CHIP). CMS. (2021, December 21).
(https://www.cms.gov/newsroom/news-alert/cms-releases-latest-enrollment-figures-medica re-medicaid-and-childrens-health-insurance-program-chip)

3. How is Medicare funded?. Medicare. (n.d.).
(https://www.medicare.gov/about-us/how-is-medicare-funded)

4. CMS’ program history. CMS.gov. (n.d.).
(https://www.cms.gov/about-cms/who-we are/history#:~:text=for%2050%20years-,On%2 0July%2030%2C%201965%2C%20President%20Lyndon%20B)

5. What’s the difference between Medicare and Medicaid?. Department of Health and Human Services. (2022, December 7). HHS.gov.
( https://www.hhs.gov/answers/medicare-and-medicaid/what-is-the-difference-between-me dicare-medicaid/index.html#:~:text=A%20federal%20agency%20called%20the,what%2 0state%20they%20live%20in.)

6. Centers for Disease Control and Prevention. (n.d.). Morbidity and mortality weekly report (MMWR). Centers for Disease Control and Prevention. (https://www.cdc.gov/mmwr/preview/mmwrhtml/su6004a10.htm#:~:text=During%20the% 201950s%2C%20epidemic%20penicillin,infections%20(HAIs%3B%20i.e.%2C%20nosoc omial)
   
7. Hospital-Acquired Condition (HAC) Reduction Program. Centers for Medicare & Medicaid Services. (2023, July 26).
(https://data.cms.gov/provider-data/dataset/yq43-i98g)

8. What’s Medicare? Medicare. (n.d.).
(https://www.medicare.gov/what-medicare-covers/your-medicare-coverage-choices/whats- medicare)

9. Dixon, Richard. E. (2011, October 7). Morbidity and mortality weekly report (MMWR). Centers for Disease Control and Prevention. (https://www.cdc.gov/mmwr/preview/mmwrhtml/su6004a10.htm#:~:text=During%20the% 201950s%2C%20epidemic%20penicillin,infections%20(HAIs%3B%20i.e.%2C%20nosoc omial)
    
10. Health policy brief - health affairs. (2015, August 6). (https://www.healthaffairs.org/do/10.1377/hpb20150806.512738/full/healthpolicybrief_14 2.pdf)
