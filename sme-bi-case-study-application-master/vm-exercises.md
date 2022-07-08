# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products.
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*One measurable learning objective that this exercise assesses*
To look at alternative metrics we can create to give us more insights, in the form of calculated fields


#### Context

*3 - 4 sentence description of why it’s important to to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*
You can look at the same [exercise]([url](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4)) from the Case Study: Analyzing Customer Churn in Tableau on how to write a good context.

This task is important because it's a fundamental concept in data analysis - how to turn data into an insight. Analysts show their worth through their ability to look at numbers
and manipulate them to create metrics, because these help summarize the situation we are studying. In the case of the house prices dataset, creating two new metrics ("Holding Period"
and "Average Revenue") give us more information that we can tailor to our potential investors depending on the timescales they are working with. It helps the course viewer
understand the importance of showing clients what is important to them and how we can manipulate data to achieve this.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Create calculated field for "Holding Period" in new workbook
- Place "Holding Period" on rows, "Neighborhood" on columns, set to Average measure
- Ensure title and axes are correctly labeled, data is ordered in descending order
- In second workbook, create calculated field for "Average Revenue"
- Drag "Average Revenue" to rows, "Neighborhood" to columns, set to Average measure
- Ensure title and axes are correctly labeled, data is ordered in descending order

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*
Which neighborhood provides the highest average revenue per year of holding?

#### End goal:

*Add an image of the final visualization here.*
Added two images in /exercises, initial state is a blank tableau workbook

## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`.

#### Explanation & Description
Which answers will the learner be able to solve once building this? How does it fit in the bigger picture?
The learner will understand:
- the importance of creating your own metrics
- how to write simple Tableau code in calculated fields
- how to create bar charts
- the advantages and limitations of the new metrics that have been created

#### End goal:

*Add an image of the final visualization here.*
Images have been added in the /exercises folder, along with the final workbook
