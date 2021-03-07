<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h1 align="center"><a href = "https://www.udacity.com/course/data-analyst-nanodegree--nd002"> Udacity Data Analyst Nanodegree </a></h1>
<h2 align="center">Project I: Introduction to Data Analysis<br></h2>
<p align="center">Utilised a curated dataset and investigated it using NumPy and Pandas. Progressed through the entire data analysis process, started by posing a question and finished by sharing findings.</p>
<h2 align="center"><br>Investigating Firearm Registrations and Census Data at a State Level in the U.S.A.<br></h2>

### Tools and Skills Used

#### Tools
- Python 3.6.3
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - datetime
- Jupyter Notebook

#### Skills
- Data exploration
- Data integration
- Data wrangling
- Data visualisation
- Communication

### Project Details

For this investigation the FBI's National Instant Criminal Background Check System (NICS) data and U.S. census data has been utilised.

#### FBI's National Instant Criminal Background Check System (NICS) data
The NICS data comes from the FBI's National Instant Criminal Background Check System (NICS).

Mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998, NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. More than 100 million such checks have been made in the last decade, leading to more than 700,000 denials.

Whilst the NICS data may at first glance look complete, it is important to remember it represents the number of firearm background checks initiated but a one-to-one correlation cannot be made between a firearm background check and a firearm sale due to varying state laws and purchase scenarios including:

- Checks may only be for concealed carry permits, not actual gun sales
- Kentucky runs a new check on each concealed carry license holder each month
- Checks not conducted for private gun sales e.g. Harvard researchers found that roughly 40 percent of respondents had acquired their most recent firearm without going through a background check.
The NICS data is provided in one sheet of an .xlsx file. It contains the number of firearm checks by month, state, and type.

#### U.S. census data
For this study, the NICS data has been supplemented with state level data from census.gov.

The U.S. census data is provided in a .csv file. It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.

#### Questions to investigate:
- Which states have had the highest growth in firearm registrations?
- Is there a seasonality to firearm registrations?
- Does population change, education or poverty have an impact on firearm registrations?
