# ExamplePoster
An example of a poster I created for the Spring 2023 SIS-750 Data Analysis course I took at American University.

This  was meant to be a simple demonstration of using RMarkdown to create a poster that could be used to present at a data analysis conference (or really any conference). I had to go find my own data, conduct an analysis using that data, then finally present the results.

Data sources are documented in detail on the poster file. I filtered out all information on voting that wasn't related to Trump votes in the 2020 election and to simplify the analysis I also dropped all records with missing or NULL values. The slides were created using RStudio and the `posterdown` package. 

Files for the project:
- `countypres_2000-2020.csv` raw data
- `counties.csv` raw data
- `US_County_ACP_FEB2023.csv` raw data
- `ARC_Logo.png` image file for the poster
- `FCC_logo.png` image file for the poster
- `qrcode_www.arc.gov.png` image file for the poster
- `HansenPoster_files` folder of generated files to produce poster preview

Project code and output:
- `HansenPoster.Rmd` code that generates the poster
- `index.html` this is the output set of slides

**See the poster** using `gh-pages` [at this link](https://curtisnedhansen.github.io/ExamplePoster/).
