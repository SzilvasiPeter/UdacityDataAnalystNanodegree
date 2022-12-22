# Data Visualization PISA2012

Udacity Data Analyist Nanodegree - Communicate Data Findings Project

## by Peter Szilvasi

## Dataset PISA

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

* [PISA Data](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip) contains students' assessments informations.
* [PISA Data Dictionary](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv) explains the variables in the data set.
* The data and topics of investigation come from the [PISA Data Visualization Competition](http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm).

> Note: The unzipped PISA Data csv file is 2.75 GB.

## Summary of Findings

* Albania (lower income country) performs worst among Portugal, Hungary (middle-income countries), and Germany (higher income country).
* More than half of the school does not have group work.
* Students spend more time on a computer than doing homework on average.
* Genders are similarly good at math and science. Females are better at reading than males.
* First-generation immigrant scores slightly less than others.
* Students have a higher score if they live with single or both parents.
* Parent educational background positively correlated with the student's score. Higher parent education translates to higher students score.
* Playing video games daily will reduce the students' scores. Males play more than females, especially in the multi-player setup.

## Key Insights for Presentation

1. Country scores based on their income level
2. Group work frequency ratio
3. Parent numbers and students' score
4. Parent educational levels and students' score
5. Immigrant status and students' score
6. Gaming and students' score

Slides converting command:

`!jupyter nbconvert .\Part_II_slide_deck_template.ipynb --to slides`
