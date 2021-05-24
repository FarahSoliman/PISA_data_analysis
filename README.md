PISA Data Analysis

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.
Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

Dataset Dictionary was used to identify the most interesting variables for me to be studied. I was interested in exploring how the student country, as well as parent birth countries, affect student score.

For data cleaning missing values in data were replaced and per subject, the 5 plausible scores for each student are merged into one by taking the average.

# Univariate Exploration and Analysis

The distribution of scores per subject is visualized: The scores show a normal distribution, with most students having an average score (between 400 to 500) in either Math, Reading or Science.

Countries with most students with scores higher than 700 (above average) per subject are identified:
*   Asian countries china and singapore have dominated top 3 positions in above average math scores. 
*   Singapore has the overall highest number of above average scoring students in all three subjects.
*   Canada and Australia also have a high number of above average scoring students in reading, science and, to some extent, math.

The proportion of students having parents with same or different country is visualized: The vast majority of students have parents from the same country.

# Bivariate Exploration and Analysis

Do countries with high numbers of above average scoring students have higher scroing students in general?
*   Asian countries such as China, Singapore, and Japan have, on average, the highest scoring students in all three subjects.
*   Peru is the country with the lowest average score in all three subjects, which hints at a need of improvement in their education system.
*   Mid-east countries such as Qatar, Tunisia, and Jordan have the low scoring studentys in all three subjects.

Countries with most above average scoring students in multiple subjects simeltanously are visulaized: Singapore has the overall highest number of above average scoring students in multiple subjects simeltanously.

Scores of students having parents from same and different cultural backgrounds are visualized: Students with parents having different countries have higher scores in all three subjects on average.

# Multivariate Exploration and Analysis

Correlation between score in one subject with score in the other two subjects is visualized:
*   A strong and positive correlation between the score of any two subjects is seen, indicating that students scoring high one subject tend to score high in the other two subjects.
*   It can be noticed that for a small number of students math performance may be disproportionaely weaker than reading or science performance.

Countries with more than a 10 position difference between rankings in each subject are obtained, with the countries and score distribution in each subject visualized:For each country, we can see the subject(s) which is outlying from other scores. For example, in the USA math scores are disproportionately lower than reading/science scores.

# Conclusion and Summary of Results

*   The scores for each subject showed a normal distribution, with most students having an average score between 400 to 500.
*   The majority of students have parents from the same country with students having parents with different countries acheiving higher scores in all three subjects on average.
*   A strong and positive correlation between the score of any two subjects is 
seen, indicating that students scoring high one subject tend to score high in the other two subjects, but it can be noticed that for a small number of students math performance may be disproportionaely weaker than reading or science performance.
*   Asian countries such as China, Singapore, and Japan have, on average, the highest scoring students in all three subjects. Meanwhile, Peru is the country with the lowest average score in all three subjects, which hints at a need of improvement in their education system, while Mid-east countries, such as Qatar, Tunisia, and Jordan have the low scoring studentys in all three subjects.
*   For some countries there is a large difference in ranking between the three subjects. For example, in the USA math scores are disproportionately lower than reading/science scores.
*   Asian countries like china and singapore have most students obtaining above average math scores. Canada and Australia also have a high number of above average scoring students in reading, science and, to some extent, math. Meanwhile Singapore has the overall highest number students with above average scoring students in all three subjects together, and in multiple subjects simeltanously.
