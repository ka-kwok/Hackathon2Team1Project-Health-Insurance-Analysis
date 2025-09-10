# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* This dataset captures details on personal attributes such as age, gender, BMI, family size and smoking habits as well as geographic factors and their influence on medical insurance charges. 
It can be used to analyze how these attributes affect medical insurance costs and for building predictive models to estimate healthcare expenses.


## Business Requirements
* To find out which attribute(s) have a larger impact on medical Insurance Cost.


## Hypothesis and how to validate?

* With Statistical tests (T-Test and ANOVA) in Data Visualization Jupyter Notebook, we justified our findings with the p-value as below. 

**Hypothesis 1 (Smoker Status):** We hypothesize that individuals who smoke will have significantly higher insurance charges compared to those who do not smoke. This will be tested as we keep other attributes constant while we compare relationship between smoker status and medical insurance cost.

    * Answer: **Modest significant** 
    * p-value: 0.0000 (very near to 0)

**Hypothesis 2 (BMI):** We hypothesize that there is a positive correlation between an individual's Body Mass Index (BMI) and their insurance charges. This will be tested as we keep other attributes constant while we compare relationship between BMI and medical insurance cost.

    * Answer: **Highly significant**
    * p-value: 0.0000 (very near to 0, t-tested with obese and non-obese category)

**Hypothesis 3 (Age):** We hypothesize that older individuals will have higher average insurance charges than younger individuals. This will be tested as we keep other attributes constant while we compare relationship between Age and medical insurance cost.

    * Answer: **Highly significant**
    * Slope / Age coefficient: 257.72 (Linear Regression) 

**Hypothesis 4 (Region):** We hypothesize that geographic region will have less impact than personal attributes (Smoker status, BMI and Age) on medical insurance cost. This will be tested as we keep other attributes constant while we compare relationship between Age and medical insurance cost.

    * Answer: **Modest significant**
    * p-value: 0.0309 (ANOVA)

**Hypothesis 5 (Children):** We hypothesize that the number of children an individual has will have an impact on medical insurance cost but will be less than the impact of personal attributes (Smoker status, BMI and Age). This will be tested/validated as we keep other attributes constant while we compare relationship between number of children and medical insurance cost.

    * Answer: **Small but statistically significant**
    * p-value: 0.0177 (T-Test)


## Project Plan
Kanban board at: https://github.com/users/ka-kwok/projects/7/views/1
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.
