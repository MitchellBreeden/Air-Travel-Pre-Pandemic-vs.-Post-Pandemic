# Air Travel Pre-Pandemic vs. Post-Pandemic Project

## Project Overview
- **Title:** Air Travel Pre-Pandemic vs. Post-Pandemic
- **Author:** Mitchell Breeden
- **Course:** AIT-580-007
- **Institution:** George Mason University
- **Date:** March 9, 2022

## Project Description
Objective: Analyze the effects of the COVID-19 pandemic on global air travel, focusing on changes in flight numbers, airline performance, and passenger volumes.

## Data Sources
- `flightlist_20200301_20200331.csv`: [Data](https://zenodo.org/records/7065179/files/flightlist_20200301_20200331.csv.gz?download=1) on flights during the pandemic.
- `Airlines.txt`: List of airlines and relevant information.
- `Airports.txt`: List of airports and relevant information. 
- `Aircrafts.txt`: List of aircrafts and relevant information.  

## Methodology
- **Tools Used:** Python, Jupyter Notebook, Pandas, DateTime, GeoPandas, keplerGl, Matplotlib, Numpy, skLearn, bar_chart_race, [ffmpeg](https://superuser.com/questions/624561/install-ffmpeg-on-os-x).
- **Features:** Flight trends analysis, airline performance metrics.
- **Approach:** Comparative analysis of pre-pandemic and post-pandemic data.
- **Notes:** For Airlines, Airports and Aircrafts the author used \N to signify null values but this is read as new line in python. To fix this we opened each file in text edit and replaced all \N with N/A.  

## Results and Conclusions
- Insight into how the pandemic impacted air travel.
- Suggestions for future research and potential improvements in the industry.

## Additional Resources
- `Script.ipynb`: Python Jupyter Notebook for analysis.
- `Presentation.pptx`: Overview of project findings.
- `Report.docx`: Detailed project report.

## Contact Information
- Mitchell Breeden, Student, George Mason University.
- Email: breedenmitch@gmail.com

## Acknowledgments
- Dr. Huajun Zhang, Course Instructor.

## Sources
- **CDC Information on COVID-19:**
  - Provides information on the COVID-19 virus, its impact, and preventive measures. [CDC COVID-19 FAQs](https://www.cdc.gov/coronavirus/2019-ncov/faq.html)
- **Dataset Sources:**
  - Sirangelo Cristina's [dataset](Sirangelo, Cristina. http://www.lsv.fr/~sirangel/teaching/dataset/index.html) on air traffic.
  - Xavier Olive, Martin Strohmeier, & Jannis Lübbe. (2022). “Crowdsourced air traffic data from The OpenSky Network 2020” [Data set]. [Zenodo - Crowdsourced air traffic data](https://zenodo.org/record/4066722)
- **Airline and Aircraft Information:**
  - Alpine Air Express. [Alpine Air Express](http://www.alpine-air.com)
  - Kalitta Air LLC. [Kalitta Air](http://www.kalittaair.com)


