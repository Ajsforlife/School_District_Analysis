# School District Analysis

## Overview

### Purpose
The purpose of this analysis was to comparably figure out if there was anything in a certain school that skewed the data based on more spending or other factors discovered through this analysis. This code will automatically import the csv file used and run thru the process and send out the data in dataframes. There is tons of information throughout this analysis!

## Results
 - How is the district summary affected?
The overall passing % goes down slightly, because the amount of kids who pass math and reading are very similar count wise    compared to the set with the thomas 9th graders removed. and a majority of the data compiled from this still use the same    amount of passing students and the 461 missing from thomas make the data pool slightly smaller so if the data is smaller it will decrease the % amounts also.
 - How is the school summary affected?
the school summary changes as follows the first picture is the original summary and the second picture is the updated summary. The passing % at thomas high school drastically increase with the dropping of the 9th graders.
![image1](https://github.com/Ajsforlife/School_District_Analysis/blob/main/Pictures_challenge/pycity_original_summary.png)
![image2](https://github.com/Ajsforlife/School_District_Analysis/blob/main/Pictures_challenge/pycity_updated_summary.png)
 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the        other schools?
Replacing Thomas High School's ninth graders' math and reading scores drastically skew the data to have a much higher % of passing scores. In doing this it makes Thomas one of the best performing schools in the district. It seems that the 9th graders do not care as much in school as the 10th thru 12th graders do and after ninth grade the students in Thomas High School focus more on their grades.
 - How does replacing the ninth-grade scores affect the following:
            - Math and reading scores by grade
            Obviously the 9th grade will not show percise data because of the NaN being added, and the other classes have the same grades per grade, so the only real change is the removal of the ninth grade scores. Example below is the math scores by grade. ![image3](https://github.com/Ajsforlife/School_District_Analysis/blob/main/Pictures_challenge/Screenshot%202022-06-23%20151340.png)
            
      - Scores by school spending, scores by school size, and scores by school type.
Scores by school spending are comparitively the same as before you fudge thomas high schools numbers.
as well as the scores by school size and the scores by school type. The 461 student change doesn't affect the results enough to change them much. However there are some things you can infer based on these data. First and formost Charter schools do better then district schools overall. Secondly the larger the school is notoriously you have worse students, so the larger the school is (over 2000 students) usually has diminishing grades.
          Grades vs. spending below:
![image4](https://github.com/Ajsforlife/School_District_Analysis/blob/main/Pictures_challenge/pycity_gradevsepdning.png)

## Summary
The first change I'd say is that Thomas High Schools individual reading math and overall % drastically increased on the removal of those scores. A majority of the larger scale data very very slightly changes because on a data of almost 40000 students 461 being removed isnt a huge chunk of data. It actually decreases some of the data slightly in an overall district perspective because i guess some of the students that no longer have a value in their grades did relatively well. Lastly the changes are drastic for Thomas High School in general however on the grand scheme of the district very slightly affects the data.
