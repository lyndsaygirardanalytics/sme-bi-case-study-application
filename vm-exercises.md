# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Use DAX to create two measures to initiate first steps of building BI Case Study dashboards

#### Context

To get started, you will need to create a couple of measures to calculate things like Total Discharges and Average Length of Stay (LOS) Days. It is extremely helpful to keep measures organized in a table, so you’ll do that first.

To calculate total discharges, you will recall each row in the dataset represents a discharge. Therefore, to create a measure for Total Discharges, you will need to calculate a count of the rows.

Next, calculating Average LOS Days will involve calculating an average of the length_of_stay attribute. Let’s get to it!


#### Steps to be executed by the student (max 6)

- Step 1.	To get started, create a measures table to keep things organized. Call your new table _Measures.
- Step 2.	Now let’s create a measure called Total Discharges by counting the rows in the dataset, and format it with commas as a thousands separator.
- Step 3.	Calculate another measure called Average Length of Stay Days using the length_of_stay column. Format it to 1 decimal place.
- Step 4.	Look at Average LOS Days by age_group using a clustered column chart, and notice the difference between groups.


#### Exercise question:

- Question 1: What is the total Average LOS in days for patients aged 0-17? (ANS 5.7)

#### End goal:

![ex-1-sol_image](https://user-images.githubusercontent.com/125575969/220402018-85ada634-0658-4913-b66e-da6862fca7a6.jpg)

## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`.

#### Explanation & Description
Which answers will the learner be able to solve once building this? How does it fit in the bigger picture?

#### End goal:

![ex-final-sol-image1](https://user-images.githubusercontent.com/125575969/220402315-d947f732-6d14-407b-b32a-5532b78660f2.jpg)

