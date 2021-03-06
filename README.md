# Investigating firearm registrations and census data at a State level in the U.S.

For this investigation the FBI's National Instant Criminal Background Check System (NICS) data and U.S. census data has been utilised.

### FBI's National Instant Criminal Background Check System (NICS) data
The NICS data comes from the FBI's National Instant Criminal Background Check System (NICS).

Mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998, NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. More than 100 million such checks have been made in the last decade, leading to more than 700,000 denials.

Whilst the NICS data may at first glance look complete, it is important to remember it represents the number of firearm background checks initiated but a one-to-one correlation cannot be made between a firearm background check and a firearm sale due to varying state laws and purchase scenarios including:

- Checks may only be for concealed carry permits, not actual gun sales
- Kentucky runs a new check on each concealed carry license holder each month
- Checks not conducted for private gun sales e.g. Harvard researchers found that roughly 40 percent of respondents had acquired their most recent firearm without going through a background check.
The NICS data is provided in one sheet of an .xlsx file. It contains the number of firearm checks by month, state, and type.

### U.S. census data
For this study, the NICS data has been supplemented with state level data from census.gov.

The U.S. census data is provided in a .csv file. It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.

### Questions to investigate:
- Which states have had the highest growth in firearm registrations?
- Is there a seasonality to firearm registrations?
- Does population change, education or poverty have an impact on firearm registrations?

### Prerequisites
- Python 3.6.3
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - datetime
- Jupyter Notebook
- Anaconda-Navigator
