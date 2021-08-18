# Minimum Viable Product (MVP)

## Data Science for Good: Combating Sexual Violence in NYC

### Opportunity/Problem:
According to the CDC, 1 in 5 women and 1 in 14 men experience sexual violence during their lifetime.  While sexual violence impacts the entire community, it has a profound, devastating impact on victims' physical and mental health.The [NY Post](https://nypost.com/2021/04/10/sexual-assault-across-nyc-up-125-from-same-time-last-year/) reported on April 10th that sexual assault reports across NYC during the week of March 29-April 4 jumped from 9% to 38% from last year during lockdown to this year (an increase of 322%). 

**Clients/End Users:**
As such, the enduring concerns of NYC law enforcement and victim advocacy groups to prevent sexual violence remain as urgent as ever. Harnessing data science methods on NYPD Complaint Data, we can provide the NYPD and [Safe Horizon](https://www.safehorizon.org/our-services/what-we-do/) (a victim assistance nonprofit in NYC) a data-driven approach to (1) prevent sexual violence cases and (2) allocate support/resources to victims.

### Impact Hypothesis:
The impact hypothesis is that by analyzing patterns of sexual violence complaints reported to the NYPD, we can develop a model to identify factors related to high prevalence of sexual violence (such as borough, victim age group, time of occurrence, etc.).

**Primary Impact:** The primary desired impact is to identify strong predictors of sexual violence cases in NYC so that the NYPD and Safe Horizon can focus the attention of their actions/initiatives to prevent sexual violence most effectively. For example, they can target a campaign towards the most vulnerable victim group so that they are aware of their heightened risk and take extra precautions to stay vigilant. Additionally, the NYPD could increase officer presence in high-risk areas. [insert success metric]

**Secondary Impact:** The secondary desired impact is to identify which boroughs/locations require additional Safe Horizon counseling sites to support victims based on the prevalence of sexual violence cases. [insert success metric]

### Solution:
My first proposed solution path is to develop an interpretable linear regression model that will identify factors that increase the risk of sexual violence cases.

### Assumptions:
This assumes that the trends in reported sex crimes do not differ from trends in all sex crimes, reported and unreported.

### Methodology (Data & Tools):
* Dataset: NYPD Crime Complaint Data Historic, decade of 2010-2019, focusing on rape and sex crime offenses
* Example features: BORO_NM (borough name), VIC_AGE_GROUP (victim age group), VIC_RACE (victim race), RPT_DT (date event was reported to police), Latitude, Longitude
* Tools: MS Excel for data cleaning and exploratory data analysis, Tableau for data visualizations

### Preliminary Viz/Insights:
[insert visualizations here]






