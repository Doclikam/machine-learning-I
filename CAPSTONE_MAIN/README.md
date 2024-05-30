# Predict Students' Dropout and Academic Success

The data comes from[ (https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success).

A dataset created from a higher education institution (acquired from several disjoint databases) related to students enrolled in different undergraduate degrees, such as agronomy, design, education, nursing, journalism, management, social service, and technologies. The dataset includes information known at the time of student enrollment (academic path, demographics, and social-economic factors) and the students' academic performance at the end of the first and second semesters.
This project holds transformative potential for student support and academic outcomes. By amalgamating student demographics, academic paths, socio-economic backgrounds, and performance data, it enables predictive analytics to forecast student success accurately. This predictive capability not only identifies at-risk students but also facilitates proactive interventions, ranging from academic tutoring to socio-emotional support, fostering an environment conducive to student success. Additionally, it optimizes resource allocation within institutions, directing resources effectively to maximize their impact on student outcomes. Beyond academia, these insights inform broader societal imperatives, aiding policymakers in devising strategies to enhance educational equity and accessibility. This project resonates with contemporary educational needs, offering pathways to inclusive, adaptive learning environments. Its applications span student advising, curriculum development, enrollment management, and retention initiatives, with potential extensions to diverse educational contexts. In essence, it represents a significant advancement in leveraging machine learning to reshape higher education and enhance student success


# objectives

The dataset was created in a project that aims to contribute to the reduction of academic dropout and failure in higher education, by using machine learning techniques to identify students at risk at an early stage of their academic path, so that strategies to support them can be put into place. 



# key data features

| Variable Name                   | Role    | Type       | Demographic | Description                                                                                            |
|:--------------------------------|:--------|:-----------|:------------|:-------------------------------------------------------------------------------------------------------|
| Mother's occupation             | Feature | Integer    | Occupation  | Occupation code representing the mother's occupation                                                    |
| Father's occupation             | Feature | Integer    | Occupation  | Occupation code representing the father's occupation                                                     |
| Admission grade                 | Feature | Continuous |             | Continuous variable representing the admission grade of the student                                       |
| Displaced                       | Feature | Integer    |             | Binary variable indicating whether the student has been displaced (1 for yes, 0 for no)                   |
| Educational special needs       | Feature | Integer    |             | Binary variable indicating whether the student has educational special needs (1 for yes, 0 for no)       |
| Debtor                          | Feature | Integer    |             | Binary variable indicating whether the student is a debtor (1 for yes, 0 for no)                         |
| Tuition fees up to date         | Feature | Integer    |             | Binary variable indicating whether the student's tuition fees are up to date (1 for yes, 0 for no)       |
| Gender                          | Feature | Integer    | Gender      | Binary variable representing the gender of the student (1 for male, 0 for female)                         |
| Scholarship holder              | Feature | Integer    |             | Binary variable indicating whether the student is a scholarship holder (1 for yes, 0 for no)            |
| Age at enrollment               | Feature | Integer    | Age         | Continuous variable representing the age of the student at enrollment                                    |
| International                     | Feature | Integer    |             | Binary variable indicating whether the student is international (1 for yes, 0 for no)                    |
| Curricular units 1st sem (credited)    | Feature | Integer    |             | Number of curricular units credited in the 1st semester                                                  |
| Curricular units 1st sem (enrolled)   | Feature | Integer    |             | Number of curricular units enrolled in the 1st semester                                                   |
| Curricular units 1st sem (evaluations)| Feature | Integer    |             | Number of evaluations for curricular units in the 1st semester                                            |
| Curricular units 1st sem (approved)  | Feature | Integer    |             | Number of curricular units approved in the 1st semester                                                   |
| Curricular units 1st sem (grade)     | Feature | Integer    |             | Grade average in the 1st semester (between 0 and 20)                                                       |
| Curricular units 1st sem (without evaluations)| Feature | Integer    |             | Number of curricular units without evaluations in the 1st semester                                         |
| Curricular units 2nd sem (credited)    | Feature | Integer    |             | Number of curricular units credited in the 2nd semester                                                  |
| Curricular units 2nd sem (enrolled)   | Feature | Integer    |             | Number of curricular units enrolled in the 2nd semester                                                  |
| Curricular units 2nd sem (evaluations)| Feature | Integer    |             | Number of evaluations for curricular units in the 2nd semester                                            |
| Curricular units 2nd sem (approved)  | Feature | Integer    |             | Number of curricular units approved in the 2nd semester                                                   |
| Curricular units 2nd sem (grade)     | Feature | Integer    |             | Grade average in the 2nd semester (between 0 and 20)                                                       |
| Curricular units 2nd sem (without evaluations)| Feature | Integer    |             | Number of curricular units without evaluations in the 2nd semester                                         |
| Unemployment rate               | Feature | Continuous |             | Unemployment rate (%)                                                                                   |
| Inflation rate                  | Feature | Continuous |             | Inflation rate (%)                                                                                      |
| GDP                             | Feature | Continuous |             | GDP                                                                                                     |
| Target                          | Target  | Categorical|             | Target variable: dropout, enrolled, or graduate                                                         |
