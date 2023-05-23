  # STUDENTS AND CHOOSING MAJORS
## Project "STUDENTS AND CHOOSING MAJORS"
### Part 1. Analysis using Data Visualization
## Authors:
#### Sergey Orlov
#### Shrivarshini Balaji
### Introduction: 
Major is a specific area of study in which a student chooses to specialize. Popular disciplines for college majors include business, health, engineering and biology. The importance of your major depends on the industry you want to work in. When students start college, it can be difficult for students to find their focus, not everybody is certain about what they want to major in.

However, most students know they want a good-paying and secure job. This is why they are willing to make the investment of time and money to go to college. A degree can open up unexpected And exciting opportunities and pathways that are more attractive, having perks such as a better work environment, retirement health insurance, paid time off, bonuses, stock options, wellness and benefits, continuing education as well as other memberships. There’s no doubt choosing a major is a big decision and one that many students agonize over.

You might be wondering, why is choosing a major important anyway?. Don't plenty of students go in undecided or switch their initial majors and still figure it out?. It’s a sad fact that even though more students are going to college than ever, many of them are not making it across the finish line and earning their bachelor's degree.

### Here are the 3 most common reasons why students dropout, fail out or transferred out of college.

They get discouraged after flipping repeatedly from major to major.

They take classes that don't fit their unique aptitudes, skill sets and strengths.

They feel overwhelmed by the combination of taking courses, adjusting to college life, choosing college major depending on the employment rate, the unemployment rate, the popularity of the major etc.

Our mission is to help school students find their passion and choose majors, making the task of getting information about college degrees easy. Choosing the right major according to a person’s skill and knowledge will help make the society a better place to live.

#### Guiding questions
Our guiding questions are based on the questions a student will get when they are choosing a major for their college degree. Even high school students are feeling overwhelmed while thinking about what major they are going to choose.

Many are also very uncertain about whether what they have chosen has a scope to shine in the near future? To bring solutions to all these questions that rises in a student’s mind we have formed a set of guiding questions which we will find answers with the help of python graph plotting.

How does Employee’s Salary is distributed depending on their university major?

What major should be chosen to find a job and maximize a salary in the future?

Distribution of men and women salaries and opportunities to find jobs depending on their majors?

#### Dataset:
For our project we use data from the dataset “College Majors and their Graduates” collected from Kaggle “College Majors and their Graduates”. This dataset contains a comprehensive selection of lavish data and processing scripts behind the articles, graphics, and interactive experiences generated by FiveThirtyEight. We have done a number of functions on the dataset such as Checking for NAs,Checking for Duplicates,Ensuring that the entire dataset has consistent Formatting.

#### License:
All this data is under the Creative Commons Attribution 4.0 International License and MIT License. The last update of the dataset was in November of 2022.

### Code
https://github.com/orlovtsu/portfolio/blob/main/university_majors/university_majors.ipynb

### Results
## 1. The Distribution of majors by category:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/92967b11-382a-4eb3-ad41-e9a528c4a192)


The total number of majors displayed in the dataset is 172 grouped into 16 groups, but, as we can see, the distribution between the engineering, scientific or humanitarian majors is not uniform.

The next interesting question to understand,

## 2. What is the unemployment rate by major and salary distribution by majors?
Unemployment rate and salary distribution by major category can help to understand chances to find a job after graduation. If anyone who makes a choice about a future field of study has a doubt it can be useful for that.

#### Unemployment rate by major category
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/1ac718c4-bb78-4ad1-a600-4ad1a06306c3)

#### Median salary by major category: 
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/4ec2bbe7-bede-4cab-a9aa-fe405a9cc025)

The entire dataset contains data for all ages graduates, but for young people it is more useful information about recent data. We can compare all ages data with data for recent graduates and see some differences between unemployment rate and salary

#### Unemployment rate by major category for recent graduates: 
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/554f00df-ca70-4043-9d7a-7f7ee5aac0e0)

#### Median salary by major category for recent graduates: 
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/67a56a7c-c460-4b55-8bb4-275e653e2606)


As we can find, the leaders are very predictable: Engineering, Computing & Mathematics, Business and Physical Science. But we also can find that the very fast growth of recent specialist salaries is detected for Law & Public policy, but it is also riskful to stay without a job if you are a recent Law & Public Policy graduate.

It is also sad (for me as a long-time university employed person) that based on this data we can conclude that such fields as Education, Psychology & Social Work, Humanities and Art are underpaid and also riskful in job finding for recent graduates.

People who are going to follow their passion in these fields should be more prepared for these aspects of their fields in the future.

## 3. Men and women distributions differences by major
One of the useful distributions might be the men and women most preferred majors distributions. We can gather these data from our dataset for recent graduates.

#### Men and Women proportion by major category:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/5f21194e-6f25-4b11-921b-63bc5b7f6efb)


There is interesting fact that in 21 century we are still have more men and more women major categories. Let's try to find is this fact has influence on the future median salary.

#### Median salary to women proportion rate:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/df35a17a-5682-4842-91e3-a7767f84aaa1)


The tendency can be viewed from the scatterplot. We can find that the median salary really depends on the women's rate in specialization. It is really sad in the 21st century, and of course this fact may depend on the dataset. But we work with this dataset and make conclusions from the data we have. So, let's find which of more "women'' majors have the highest median salaries?

#### Top 20 highest salary majors with women proportion > 50%:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/87637f17-25f2-484e-b56f-de2de2fa4c71)

..and what if we also consider the unemployment rate?

#### Top 20 highest salary majors with women proportion > 50% with unemployment rates:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/2fe19815-db6e-440d-b406-35446fa94ceb)

#### Top 20 highest salary majors with women proportion > 50% with unemployment rates:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/7431fdd8-0145-4fd0-8376-e716ed0c26a6)

Thus, we have found the most demanded majors on the labor market to study, which women go to in greater numbers than men. But let's consider the same questions for majors with higher men proportion than women.

#### Top 20 highest salary majors with men proportion > 50%:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/08b15692-8b45-46e1-a8c8-3822521fe642)

#### Top 20 highest salary majors with men proportion > 50% with unemployment rates:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/0647eb5b-18af-4d48-a6fc-f039c65b9cc3)

So, we can conclude that in the top 20 highly paid specializations with men rate more than 50% - 17 are engineering fields.

After the separate distribution analysis let's analyze these distributions together.

#### Top highest salary and least unemployment rate major categories:
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/ce42109e-5f34-489a-8a2f-d6d07c274d92)


#### Top 20 highest salary and least unemployment rate majors: 
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/5a11825a-eaf3-4b16-87c8-7800f2393b63)

As we can conclude Petroleum Engineering is the number one champ in all categories. It is very predictable, but the question which I did not predict is that in the 21st century the median salary still could be dependent on the proportion of women or men in the field. I can only remind again that this result can be dependent on the dataset we used and for more responsible research it is needed to gather special data and design separate experiments.

#### Top lowest salary and highest unemployment rate majors: Top highest and least unemployment rate majors
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/5ed98b99-fe73-4619-8bc7-d8fc9366923d)

#### Top lowest salary and highest unemployment rate major categories: Top highest and least unemployment rate majors
![image](https://github.com/varshabalaji18/MyPortfolio/assets/50570939/60f5ddf7-e38f-4c3d-80b3-f3d9da43f0a7)

And for lowes salary and highest unemployment rate major categories I do not want to highlight the best or worst fields of study, but just want to explain the approach to understand the future risks and become prepared for it.

## Conclusion
In conclusion, we can say that our data analysis will be the great help to students of all age, mainly high school students who are in need of information on majors and its categories in college.

With the help of our analysis, the task of getting information about college major's an its scope are made easy.

We have analyzed the dataset of the USA, from which we have plotted our graphs and interpreted that most of the major's that fall under STEM(Science,Technology,Engineering and Mathematics) have higher chances of getting more salary and also has lowest unemployment rate.

As the scope and importance of all major's in education are the same across all over the world, we can strongly say that this data will be helpful to students all over the world.
Choosing the right majors according to a student's skill and interest will help increase their quality of life and happiness, because
##  "Happy people will produce healthy society with strong economy and higher living standard"
### Gratitudes
I would like to special thank Dr. Tamer Jarada for the very useful feedback and great insights I received from his educational course and my project partner Sergey Orlov for productive cooperation, responsibility and excellent communication.

## References
[1] https://www.kaggle.com/datasets/thedevastator/uncovering-insights-to-college-majors-and-their?select=recent-grads.csv

[2] A. H. A. Rashid, M. Mohamad, S. Masrom and A. Selamat, "Student Career Recommendation System Using Content-Based Filtering Method," 2022 3rd International Conference on Artificial Intelligence and Data Sciences (AiDAS), IPOH, Malaysia, 2022, pp. 60-65, doi: 10.1109/AiDAS56890.2022.9918766.

[3] H. Ali, "How to Choose the Right Career Path [The Way Ahead]," in IEEE Potentials, vol. 40, no. 6, pp. 3-4, Nov.-Dec. 2021, doi: 10.1109/MPOT.2021.3109250. “Determinants of College Major Choice: Identification Using an Information Experiment,” Review of Economic Studies 82(2), 2015, pp. 791–824. See also “How Do College Students Respond to Public Information about Earnings?” Wiswall M, Zafar B. Journal of Human Capital 9(2), 2015, pp. 117–169.

[4] “Human Capital Investments and Expectations about Career and Family,” Wiswall M, Zafar B. Journal of Political Economy 129(5), 2021, pp. 1361–1424.

[5] “Preferences and Biases in Educational Choices and Labor Market Expectations: Shrinking the Black Box of Gender,” Reuben E, Wiswall M, Zafar B. Economic Journal 127(604), 2017, pp. 2153–2186.
