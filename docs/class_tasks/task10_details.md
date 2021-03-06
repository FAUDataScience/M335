





## Task 10: Strings and grep 
### Background 

Using global regular expression print (grep) and regular expressions (regex) to find character string patterns is a valuable tool in data analysis and is available with all operating systems and many different programming languages.  It is a powerful tool once it is understood.  The recently developed `library(stringr)` package makes these tools much easier to use. The three tasks below can be completed in many different ways.  As a challenge, my code to complete this entire task less than 10 lines.


 * [Homework Schedule](../homework_schedule.html)




### Tasks


<style>
ul {
   color: black;
   list-style-type: none;
   list-style-position: outside;

}

</style>


* [ ] Use the `readr::read_lines()` function to read in each string - [randomletters.txt](https://byuistats.github.io/M335/data/randomletters.txt){target="blank"} and [randomletters_wnumbers.txt](https://byuistats.github.io/M335/data/randomletters_wnumbers.txt){target="blank"}
* [ ] With the `randomletters.txt` file, pull out every 1700 letter (e.g. 1, 1700, 3400, <U+0085>) and find the quote that is hidden - the quote ends with a period
* [ ] With the `randomletters_wnumbers.txt` file, find all the numbers hidden and convert those numbers to letters using the letters order in the alphabet to decipher the message
* [ ] With the `randomletters.txt` file, remove all the spaces and periods from the string then find the longest sequence of vowels.
* [ ] Save your `.R` script to your repository and be ready to share your code solution at the beginning of class


### Reading

* o [Chapter 14: R for Data Science - Strings](http://r4ds.had.co.nz/strings.html){target='blank'}
* o [regexr.com](http://regexr.com/){target='blank'}
* o [Five principles of effective data visualizations](https://www.thoughtworks.com/insights/blog/five-principles-effective-data-visualizations){target='blank'}

