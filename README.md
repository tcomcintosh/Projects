# About

This is a mini project using the Dual Credit Dashboard data available from the Washington State Education Research and Data Center. 

The caveat to this data is that certain factors, such as race and gender, were omitted for student privacy. The cumulative findings of these factors are available on the site itself. In my personal opinion, this would be moot since the conclusions would essentially be duplicated and just create more work.

My mini project looks across three school districts- Tacoma School District, Bellevue School District, and Yakima School District. These three were chosen based on the district's income level and to answer a question I've had- does an area's income level and associated factors with a district's income level have any effect on dual credit completion/success? I was interested in this question since I myself did Running Start and am also a non-traditional student. 

# Data Story

When cleaning the data, I got rid of any Nan values and only kept the three school districts and the year I wanted specifically (2024). Bellevue School District has a high income level; Yakima has a lower income level; and Tacoma School District would work sort of as a control. My plan was to use census data and draw from that to dig deeper into the available data.

Let's look at the data. This bar graph looks at the three chosen districts in the year 2024 across all categories for all students. We see that Yakima has less students enrolled in dual credits overall despite Bellevue and Yakima having similar total students (in 2024, the student population for Bellevue School District was ~20,339 and for Yakima, it was ~15,488). Bellevue is comprised of mostly White and Asian students, where as Yakima School District is comprised mostly of Hispanic/Latino, White, and Black students. 'Any Dual Credit Course' across all three districts are the most popular; then CTE (Career and Technical Education Course), the AP/IB courses. Among the cohort of students whose completion rates were 90% or higher, in Bellevue School District, the most popular courses were the Cambridge International Course, AP/IB, and Any Dual Credit Course; in Tacoma School District, it was CTE, Any Dual Credit Course (including excluding CTE); and in Yakima School District, Any Dual Credit Couse (including excluding CTE), and AP/IB.

Among the cohort of students where the success rate 50% or below, Running Start, College in the High School course, and IB are the most popular where student success is lower than expected. Based on my own experience, perhaps these programs are the most popular among these students because it seems they'll offer the most support as they are in school. As for Running Start- I am aware of its popularity but provided little educational support (skills, such as time management, were presumed to have been mastered already along with the rigors of college) when I was in that program, myself- but this is just a guess and more detailed information would be needed, via survey, to hazard a guess why Running Start is preferred.

The first question that came to mind was if certain dual credit programs were more popular among students in these 3 districts based on the categories 'Highly Capable' and 'Not Highly Capable'? That's not to say that certain programs are unhelpful or are 'bad', but if there are possibly underlying reasons for their popularity.
First off, my understanding of the 'Highly Capable' and 'Not Highly Capable' determinations is the equivalent to what would be in the past referred to as a gifted program. The 'Highly Capable' label (see 'Citations') comes with its own issues with racial, gender, economic and disability disparities, tending to highly favor White, Asian, neurotypical and male populations compared to others (low income, of color, female [in STEM]). Additionally, students who are assigned as Highly Capable are not necessarily in Running Start or other dual credit programs.

For those who are, though, among students classified as 'Highly Capable' and in dual credit programs, there are a couple of things that stood out. First, that Bellevue has many more students in the Highly Capable Program and Yakima is much lower. Given Bellevue's demographics compared to Yakima's, this tends to gel that the findings in "Addressing Under-representation of Student Populations in Gifted Programs" still holds true.

Back to a macro view, I was wondering if the total students enrolled in dual credit programs was significant. In other words, is there a significant difference among students enrolled in these three districts compared to each other? I used a p-value of 0.05 and confirmed that the bar chart that suggested that the rate of enrollment in Yakima School District was significantly lower compared to both Tacoma School District and Bellevue School District. However, the difference between Tacoma School District and Bellevue School District was not significant.

The remaining two bar charts were used to compare whether the rates of Dual Credit Enrollment and Dual Credit Completion were significant, again, using a p-value of 0.05. The result comes out as not significant. This means that though the rate of student enrollment and completion across these three districts were significant, the difference between districts of students who enrolled and completed these dual credit programs successfully wasn't. In other words, students who did enroll in these programs were just as successful in Yakima in completing the dual credit programs as those students in Bellevue and Tacoma School District.

# Conclusion/Findings

The fact that students in Yakima School District were just as successful in completing Dual Credit programs despite low overall enrollment tells me that socioeconomic factors in this low-income school district are probably the cause for depressed dual credit enrollment rate compared to the school districts that are not low-income. There's not a whole lot of information regarding students who are deemed 'Highly Capable' but based on the corresponding bar chart- Bellevue students may be overrepresented and this require more research to evaluate and discuss and implement changes to overcome these suggested disparities.  

# Citations
Pauley, Gayle and Johnstone, Kristina (2009). Addressing Under-representation
of Student Populations in Gifted Programs. Office of Superintendent of Public
Instruction. Olympia, Washington.

“Search for Public School Districts - District Detail For.” Ed.gov, 2024, nces.ed.gov/ccd/districtsearch/district_detail.asp?ID2=5310110. Accessed 21 June 2026.
“Search for Public School Districts - District Detail for Bellevue School District.” nces.ed.gov, nces.ed.gov/ccd/districtsearch/district_detail.asp?ID2=5300390.


