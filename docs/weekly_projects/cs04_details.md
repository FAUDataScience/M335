





## Case Study 4: I can clean your data 
### Background 

The [Scientific American argues](https://www.scientificamerican.com/article/why-are-we-getting-taller/){target="blank"} that humans have been getting taller over the years.  As the data scientists that we are becoming, we would like to find data that validates this concept. Our challenge is to show different male heights across the centuries.  

This project is not as severe as the two quotes below, but it will give you a taste of pulling various data and file formats together into "tidy" data for visualization and analysis. You will not need to search for data as all the files are listed [here](https://byuistats.github.io/M335/maleheight.html)

1. "Classroom data are like teddy bears and real data are like a grizzly bear with salmon blood dripping out its mouth." - [Jenny Bryan](https://twitter.com/JennyBryan){target="blank"}
2. "Up to 80% of data analysis is spent on the process of cleaning and preparing data" - [Hadley Wickham](http://jstatsoft.org/v59/i10){target="blank"}



 * [Homework Schedule](../homework_schedule.html)






### Tasks


<style>
ul {
   color: black;
   list-style-type: none;
   list-style-position: outside;

}

</style>


* [ ] Use the correct functions from `library(haven)` , `library(readr)`, and `library(readxl)` to load the 6 data sets listed [here](https://byuistats.github.io/M335/maleheight.html){target="blank"}
* [ ] Tidy the Worldwide estimates `.xlsx` file
    * [ ] Make sure the file is in long format with year as a column
    * [ ] Use the `separate()` and `mutate()` functions to create a decade column
* [ ] Import the other five datasets into R and combine them into one tidy dataset.
    * [ ] This dataset should have the following columns - birth_year, height.cm, height.in, and study_id
* [ ] Save the two tidy datasets to your repository
* [ ] Make a plot with decade on the x-axis and height in inches on the y-axis with the points from Germany highlighted based on the data from the `.xlsx` file.
* [ ] Make a small-multiples plot of the five studies to examine the question of height distribution across centuries
* [ ] Create an `.Rmd` file with 1-2 paragraphs summarizing your graphics and how those graphics answer the driving question
* [ ] Compile your `.md` and `.html` file into your git repository
* [ ] Find two other student's compiled files in their repository and provide feedback using the issues feature in GitHub (If they already have three issues find a different student to critique)
* [ ] Address 1-2 of the issues posted on your project and push the updates to GitHub


### Reading

* o [Hadley on Tidy Data](http://vita.had.co.nz/papers/tidy-data.pdf){target='blank'}
* o [Chapter 18: R for Data Science - Pipes](http://r4ds.had.co.nz/pipes.html){target='blank'}







