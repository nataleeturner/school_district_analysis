# school_district_analysis

## Overview of the school district analysis
The purpose of this analysis was to create an overview of the school test data across several high schools within a school district. We will look at the reading and writing test data per grade, per school, per school budget, per school size, and per type of school. Each of these analyses were performed with and without the 9th grade data from Thomas High School, due to some suspected academic dishonesty. By comparing the data, we can come up with a conclusion about the 9th grade test scores from Thomas High School (THS).

## Results
In all of the attached tables, the first table will include all of the data, while the second has the Thomas High School 9th grade test scores removed from the data.

### District Summary
According to the district summaries, removing the THS 9th graders caused the average math score to go down slightly, by 0.1, and the reading score to be unchanged. Even though the average reading test score did not change, the percentage of students passing reading reduced by 0.1%, which shows that even though the overall test average was the same, there is a larger percentage of students with passing grades in 9th grade at THS than the rest of the schools and grades. The percentage of students passing overall reduced by 0.3%, from 65.2 to 64.9%. This preliminary data shows that the THS 9th grade scores were above the average, since removing them made the averages go down.

<img width="933" alt="district_summary_full" src="https://user-images.githubusercontent.com/88349443/133946936-11d0a4f8-5786-479c-8d05-8bd6cb30468e.png">

<img width="923" alt="disctrict_summary_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133946940-f2ae2072-4672-49de-a572-060ebe9c576e.png">

### School Summary
In the school summary the only thing changing is the test data from Thomas High School. When looking at these, we can see that when we remove the 9th graders, the average math score goes down by about 0.06 and the average reading score goes up by about 0.05. However, the percentage of students passing math, reading, and both goes down when 9th graders are removed. This shows us that even at THS alone, the 9th graders are passing at a slightly higher rate than the rest of the school.

<img width="995" alt="per_school_summary_full" src="https://user-images.githubusercontent.com/88349443/133946958-53366fbd-65d2-4182-9f8f-e3e1b8f1ff97.png">

<img width="998" alt="per_school_summary_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133946960-05ffa2f4-1fd8-4c44-adf5-a561b153c302.png">

### Performance relative to other schools
Referencing the above two tables, Thomas High School’s performance relative to the other high schools is not affected very much when the 9th grade scores are removed. It still remains the second highest performing schools in the overall passing percentage. Additionally, when compared to the other charter schools, it remains around the middle on math and reading scores, as well as percentage passing math. However, THS went from being the best school for percentage of students passing reading to the 3rd highest. This measure was by far the most affected when the THS 9th grade student test data is removed.

### Math and reading scores by grade
Since these tables show the average score per high school per grade, the only change is that the 9th grade reading and math score averages now show “nan” instead of the averages. The averages for all of the other grades and high schools are not affected. The first table is the average math scores with all of the data, the second is the average math scores with THS 9th grade data removed, the third is the average reading scores with all of the data, and the fourth is the average reading scores with the THS 9th grade data removed.

<img width="301" alt="math_scores_by_grade_full" src="https://user-images.githubusercontent.com/88349443/133946985-66b606f1-9ca2-4c4d-9bab-b698d7051dee.png"> <img width="301" alt="math_scores_by_grade_full" src="https://user-images.githubusercontent.com/88349443/133946989-8fed5200-1592-42f4-80aa-d3817037ead3.png">

<img width="303" alt="reading_scores_by_grade_full" src="https://user-images.githubusercontent.com/88349443/133946992-6ef3c428-8b1f-4215-90d2-8fe67100735c.png"> <img width="307" alt="reading_scores_by_grade_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133946994-69218d1d-3801-4939-8e0a-1e0cbd30534e.png">

### Scores by school spending
Thomas High School’s budget is about $638 per student, which means it is included in the averages for the “$630 - $644” bucket. These tables were created with a format of one decimal place for the average test scores and zero decimal places for the percentage of students passing math, reading, and overall. Because the changes that occur when the 9th grade THS scores are omitted are so small, and because there are 4 schools included in the 3rd spending bucket, the effect of the THS 9th grade data removal cannot be seen in this data. Therefore, the before and after tables are unchanged. More decimal points would have to be added to potentially notice a change, but it would be too minimal to be worthy of analysis.

<img width="823" alt="spending_summary_full" src="https://user-images.githubusercontent.com/88349443/133947030-3b5b405a-da40-43c4-bf86-3eb8a95d77f9.png">

<img width="823" alt="spending_summary_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133947032-8bb32def-34eb-4463-bc78-2b6938db9a93.png">

### Scores by school size
At 1,635 students, Thomas High School is considered a Medium sized school. Similar to the reasons in the scores by school spending analysis, this table is also unaffected by removing the 9th grade data from THS.

<img width="756" alt="scores_by_size_full" src="https://user-images.githubusercontent.com/88349443/133947103-f8293237-13c7-48dd-86c1-10c8386b06da.png">

<img width="759" alt="scores_by_size_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133947069-14ba9924-ad55-4448-b2bf-7f14e54f6cc9.png">


### Scores by school type
Thomas High School is a charter school, but once again the data shown in these tables is unaffected by removing THS 9th grade test scores. What’s interesting, however, is the discrepancy between the test scores of the charter and district schools. While the averages aren’t too far off, the charter schools have a much higher overall passing percentage of its students.

<img width="710" alt="scores_by_type_full" src="https://user-images.githubusercontent.com/88349443/133947039-02574e03-6424-4c43-a86b-6d165fdfe3c2.png">

<img width="715" alt="scores_by_type_without_THS9th" src="https://user-images.githubusercontent.com/88349443/133947042-b4b8e5a1-5cad-40c7-a0b0-c7d800b88047.png">

## Summary
While there may be a small case that can be made for some academic dishonesty amongst the 9th grade math and reading test scores, it is a difficult assumption to make because the change in the data is so statistically insignificant. After removing these grades, Thomas High School test averages did go down, but only by about 0.1%. Additionally, the percentage of students passing overall went down by about 0.3%. When ranking the schools from best test performance to worst, THS went from 1st place to 3rd place in the reading passing percentage. Alternatively, their position did not change when looking at the overall and math score passing percentages. Lastly, when looking at the reading and math scores by grade, THS 9th grade scores don’t stand out, they’re fairly on par with other grades and schools for both.

Some items that do stand out and might require further investigation include looking into potential academic dishonesty in the Holden High School 11th graders. Their average math scores were the highest of all the grades and schools by 0.7 points, which is more significant than any of the THS 9th grade results. Additionally, the charter schools perform much higher than the district schools in math, but they are all fairly close in reading scores. I would recommend that the district schools change and improve their teaching efforts in math. Lastly, the schools with the highest budget per student also have the lowest scores. I would recommend doing an audit of the budgets and comparing them to the scores with lower budgets to optimize where the money is being spent.

