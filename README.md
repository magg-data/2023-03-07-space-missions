# 2023-03-07-space-missions
Data analytics project

The purpose of this study is to get some insights of space missions that took place from 1957-2022. The data for this study is located at
Maven Analytics and contains 4,630 records regarding space missions around the world for the period 10/4/1957 - 07/29/2022.

More specifically, this report finds answers to the following questions

* Launches: 
  - How many launches in total
  - How many successful/failed launches?
* Facilities: 
  - How many launches per facility?
  - Which countries launched space missions?
* Rockets:
  - How many rockets?
  - How many is active vs. retiered?
  - Which rockets were used the most?
  - Which rockets served the longest?

# Files:
* mission-all-fields.csv This is the data that were cleaned and processed (mainly reformatted slightly) for the purpose of this project
* analysis-report* files
  - analysis-report.Rmd is the file I used documented the process of data analysis for this project and major findings
  - analysis-report.html and *.pdf are the output files knitted from analysis-report.Rmd
* space-missions-flexdashboard* files
  - space-missions-flexdashboard.Rmd is the source file for the dashboard created with Flexdashboard
  - space-missions-flexdashboard.html is the output file, knitted from the corresponding Rmd file
* maven 
  This folder contains screenshots for the Maven Analytics
* kaggle
  These are versions of flexdashboard I used at kaggle.com. Simple import of my original files did not work and I had to reformat the diagrams to adapt it to be digestible at kaggle.com. It was definitely a lot of pain to port the original flexdashboard to kaggle.com with some magic involved such as five empty space to show up the first screen ... Anyway.
