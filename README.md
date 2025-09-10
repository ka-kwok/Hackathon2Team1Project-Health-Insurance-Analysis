# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* This dataset captures details on personal attributes such as age, gender, BMI, family size and smoking habits as well as geographic factors and their influence on medical insurance charges. 
It can be used to analyze how these attributes affect medical insurance costs and for building predictive models to estimate healthcare expenses.


## Business Requirements
The business requires a predictive model to estimate insurance charges based on customer demographics (age, sex, region) and lifestyle factors (smoker). Since categorical variables cannot be directly used by most models, they must be transformed into numerical format using one-hot encoding. Additionally, visualizations of the encoded features are required to understand category distributions and their impact on charges, enabling data-driven decisions in pricing strategy, risk assessment, and market targeting.

* Customer Segmentation

    * Distribution plot shows how customers are spread across sex, smoker, region.

    * Helps insurers identify under/over-represented groups.

* Risk Assessment

    * Average charges per category plot shows which groups drive higher costs (e.g., smokers have higher charges).

    * Insurers can adjust premiums accordingly.

* Market Strategy

    * Regional distribution can reveal where most insured clients are located.

    * Helps allocate sales and marketing resources effectively.

* Fairness & Compliance

    * By examining how categorical groups differ in charges, insurers can ensure pricing models comply with regulations (avoid discrimination while adjusting for risk).


## Hypothesis and how to validate?

* With Statistical tests (T-Test and ANOVA) in Data Visualization Jupyter Notebook, we justified our findings with the p-value as below. 

**Hypothesis 1 (Smoker Status):** We hypothesize that individuals who smoke will have significantly higher insurance charges compared to those who do not smoke. This will be tested as we keep other attributes constant while we compare relationship between smoker status and medical insurance cost.

    * Answer: Modest significant
    * p-value: 0.0000 (very near to 0)

**Hypothesis 2 (BMI):** We hypothesize that there is a positive correlation between an individual's Body Mass Index (BMI) and their insurance charges. This will be tested as we keep other attributes constant while we compare relationship between BMI and medical insurance cost.

    * Answer: Highly significant
    * p-value: 0.0000 (very near to 0, t-tested with obese and non-obese category)

**Hypothesis 3 (Age):** We hypothesize that older individuals will have higher average insurance charges than younger individuals. This will be tested as we keep other attributes constant while we compare relationship between Age and medical insurance cost.

    * Answer: Highly significant
    * Slope / Age coefficient: 257.72 (Linear Regression) 

**Hypothesis 4 (Region):** We hypothesize that geographic region will have less impact than personal attributes (Smoker status, BMI and Age) on medical insurance cost. This will be tested as we keep other attributes constant while we compare relationship between Age and medical insurance cost.

    * Answer: Modest significant
    * p-value: 0.0309 (ANOVA)

**Hypothesis 5 (Children):** We hypothesize that the number of children an individual has will have an impact on medical insurance cost but will be less than the impact of personal attributes (Smoker status, BMI and Age). This will be tested/validated as we keep other attributes constant while we compare relationship between number of children and medical insurance cost.

    * Answer: Small but statistically significant
    * p-value: 0.0177 (T-Test)


## Project Plan
Kanban board at: https://github.com/users/ka-kwok/projects/7/views/1
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

# Choice of Methodology

* **Exploratory Data Analysis (EDA):** Performed to identify patterns, trends, and correlations between personal attributes (such as age, gender, BMI, smoking status, number of children, and region) and the target variable (insurance charges). EDA helps to detect outliers, understand variable distributions, and inform the selection of features for further analysis.

* **Visualization (Boxplots, Scatterplots, Heatmaps):** Utilized to visually represent relationships between key attributes and insurance charges. These visual tools help to clarify the impact of factors like smoking status, BMI, and age on costs, making complex data more accessible for stakeholders.

* **Statistical Testing:** Applied to quantitatively assess the influence of attributes (e.g., smoker status, BMI, age, region, number of children) on insurance charges. Techniques such as T-tests, ANOVA, and regression analysis provide statistical evidence for observed differences and validate hypotheses, ensuring conclusions are robust and data-driven.


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

### Tableau Dashboards

Link:


## Main Data Analysis Libraries
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* Scipy
* Sklearn
* Tableau


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
