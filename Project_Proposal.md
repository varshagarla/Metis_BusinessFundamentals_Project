
# Business Project Proposal

## Data Science for Good: Combating Sexual Violence in NYC

### Opportunity/Problem:
According to the CDC, 1 in 5 women and 1 in 14 men experience sexual violence during their lifetime.  While sexual violence impacts the entire community, it has a profound, devastating impact on victims' physical and mental health.The [NY Post](https://nypost.com/2021/04/10/sexual-assault-across-nyc-up-125-from-same-time-last-year/) reported just yesterday that sexual assault reports across NYC during the week of March 29-April 4 jumped from 9% to 38% from last year during lockdown to this year (an increase of 322%). As such, the enduring concerns of NYC law enforcement and victim advocacy groups to prevent sexual violence remain as urgent as ever. Harnessing data science methods on NYPD Complaint Data, we can provide the NYPD and [Safe Horizon](https://www.safehorizon.org/our-services/what-we-do/) (a victim assistance nonprofit in NYC) a data-driven approach to prevent sexual violence, raise awareness to the community, and allocate resources and support to victims.

### Impact Hypothesis:
My first proposed solution path is to develop an interpretable linear regression model that will identify factors that increase the risk of sex-related crimes. The impact hypothesis is that by utiizing such a model, we may uncover insights into which boroughs or precincts have the highest prevalence of sex-related crimes, what age group victims fall under most, and what time of day sex-related crimes occur the most. Identifying such patterns and predictors of sexual violence will allow the NYPD and Safe Horizon to take actions such as increasing officer presence in high-risk areas and targeting awareness campaigns to high-risk victim groups. The desired impact is to reduce the incidence of the sexual violence across all boroughs of NYC (or ensure that the incidence does not increase if it has been the same, depending on the trend identified from EDA). This assumes that all sex-related crimes in NYC are reported to the NYPD.

### Data Description:
* Dataset: NYPD Crime Complaint Data Historic (years TBD, most likely 2017-2020, years will be adjusted depending on number of rows of data and Google Sheets capacity)
* Subsetting on complaints with offense description of 'SEX CRIMES' or 'RAPE'
* Dataset contains 35 columns, with features such as BORO_NM (borough name), VIC_AGE_GROUP (victim age group), VIC_RACE (victim race), RPT_DT (date event was reported to police), Latitude, Longitude

### Tools:
I will use Google Sheets for data cleaning and exploratory data analysis and leverage Tableau to visualize findings.

### MVP Goal:
After further project scoping, data acquisition and cleaning, and preliminary exploratory data analysis, I plan to submit an updated version of this project proposal as an MVP along with a few visualizations of preliminary insights from exploratory data analysis.














