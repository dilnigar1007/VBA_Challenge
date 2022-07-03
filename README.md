# VBA_Challenge

## Overview of Project and Purpose

	Steve performed an analysis on stock "DQ" for the year of 2017 and 2018, but he wanted to make a deeper analysis on other stocks and see which one made the most value and return, also which ones made negative return. Therefore, we made our analysis on 12 stocks including "DQ". We wanted to see how much value each stock had throughout the year and percentage of return. We looked at each stocks beginning and ending prices for each day and calculated the return percentage.

## Results
	Because we formatted the "return" column, it easily showed which ones red/negative return, or green/positive return. In 2017, only "TERP" made negative return of -7.2%. "DQ", "ENPH", "FSLR", and "SEDG" made the most return of 100% or more. In 2018, "ENPH" and "RUN" are the only ones made positive return of 81.9% and 84.0%. We can see them in the following snapshots 
![VBA_Challenges_2017](https://github.com/dilnigar1007/VBA_Challenge/blob/main/VBA_Challenge_2017.png)
![VBA_Challenges_2018](https://github.com/dilnigar1007/VBA_Challenge/blob/main/VBA_Challenge_2018.png)
So, we can let Steve know that it is safe to invest in "ENPH" since it was making positive return two years in a row.

### Challenges
	There were a lot challenges throught this work. For example, I was struggling with creating multiple loops and repeating them. I wasn't sure where to include "Next i" or "Next j". I thought I repeat i after closing j loop, but it wasn't the case. I was keep getting error messages. Luckily, I was able to fix it with one of TA's help. Also, I set tickers variable as String, but later I set tickerIndex as Integer and added two different variables together. This was one of the errors I was constantly getting "type mismatch". I didn't realize it until TA pointed out. Dealing with multiple variables and looping was a real challenge for me, especially we had to loop over for two different years for the  same variables.
	
### Summary
		There are some benefits of having refactoring the code. For example, in this case, we improved the code itself, we added codes to analyze two different years' stock data comparing to the original data in the module where we only analyzed one year and one stock. Also, it gave us the chance to debug all the issues we ran into throught the challenge and understand them fully by fixing them. I had easy time refactoring because  we had all the directions and guidance to do next, what to do in step 2 and all that. But, on the other side, it's a bit challenging to refactor this. First, it took me a lot of time to think through the whole process and know what the teacher (in real life probably the person who assigned the job) is looking for. In this challenge, two screenshots were given so we know how the results look like. But imagine, in real life people don't give you the answer or how your analysis going to look like. So when we run the code, answer might not look like what they're looking for. It's hard to know which step went wrong. I know that the codes we were given were 100% accurate, but in real life we can't guarantee the code we are provided is not, so we
need to take extra steps to make sure the original code is accurate so we can start our work based on that. 
