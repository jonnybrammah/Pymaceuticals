# Pymaceuticals
---

## Project Description
This project analyzes the data collected on the effectiveness of multiple drug regimen on tumor volumes in mice in order to evaluate Pymaceuticals, Inc.'s new anti-cancer medication, Capomulin.

To complete this analysis, the information was read from two csv files (one on the mice used in the trial, and one with data by assigned Mouse ID) into a Jupyter notebook and analyzed using Pandas. The two csvs were merged into a combined dataframe and then cleaned to remove a duplicate Mouse ID, and then analyzed.
Plots were created to demonstrate the potential effectiveness of Capomulin as a treatment, and plotted using both Pandas and Mapplotlib.

---
### Analysis

A summary of some key findings are as follows:
- Capomulin appears to be effective at reducing the volume of tumors. In one example mouse, the tumor volume (in cubic mm) was reduced from 45 mm3 to approximately 41 mm3 over 45 days.
- Similarly, Capomulin demonstrated a mean tumor volume (over all mice, over all timepoints) of 40.7 mm3 and similar median tumor volume, which was much lower than many of the other drugs tested.
- Capomulin performed approximately as well as Ramicane, with a similar spread of results and a similar mean tumor volume after 45 days, and significantly smaller than Infubinol and Ceftamin.


![Range of Medicines in pill form](https://cdn.pixabay.com/photo/2016/12/05/19/43/pill-1884775_960_720.jpg) (Image sourced from pixabay)
