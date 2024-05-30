# Predict Students' Dropout and Academic Success

The data comes from[ (https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success).

A dataset created from a higher education institution (acquired from several disjoint databases) related to students enrolled in different undergraduate degrees, such as agronomy, design, education, nursing, journalism, management, social service, and technologies. The dataset includes information known at the time of student enrollment (academic path, demographics, and social-economic factors) and the students' academic performance at the end of the first and second semesters.


# objectives

The dataset was created in a project that aims to contribute to the reduction of academic dropout and failure in higher education, by using machine learning techniques to identify students at risk at an early stage of their academic path, so that strategies to support them can be put into place. 



# key data features

Mother's occupation	Feature	Integer	Occupation	0 - Student 1 - Representatives of the Legislative Power and Executive Bodies, Directors, Directors and Executive Managers 2 - Specialists in Intellectual and Scientific Activities 3 - Intermediate Level Technicians and Professions 4 - Administrative staff 5 - Personal Services, Security and Safety Workers and Sellers 6 - Farmers and Skilled Workers in Agriculture, Fisheries and Forestry 7 - Skilled Workers in Industry, Construction and Craftsmen 8 - Installation and Machine Operators and Assembly Workers 9 - Unskilled Workers 10 - Armed Forces Professions 90 - Other Situation 99 - (blank) 122 - Health professionals 123 - teachers 125 - Specialists in information and communication technologies (ICT) 131 - Intermediate level science and engineering technicians and professions 132 - Technicians and professionals, of intermediate level of health 134 - Intermediate level technicians from legal, social, sports, cultural and similar services 141 - Office workers, secretaries in general and data processing operators 143 - Data, accounting, statistical, financial services and registry-related operators 144 - Other administrative support staff 151 - personal service workers 152 - sellers 153 - Personal care workers and the like 171 - Skilled construction workers and the like, except electricians 173 - Skilled workers in printing, precision instrument manufacturing, jewelers, artisans and the like 175 - Workers in food processing, woodworking, clothing and other industries and crafts 191 - cleaning workers 192 - Unskilled workers in agriculture, animal production, fisheries and forestry 193 - Unskilled workers in extractive industry, construction, manufacturing and transport 194 - Meal preparation assistants		no


Father's occupation	Feature	Integer	Occupation	0 - Student 1 - Representatives of the Legislative Power and Executive Bodies, Directors, Directors and Executive Managers 2 - Specialists in Intellectual and Scientific Activities 3 - Intermediate Level Technicians and Professions 4 - Administrative staff 5 - Personal Services, Security and Safety Workers and Sellers 6 - Farmers and Skilled Workers in Agriculture, Fisheries and Forestry 7 - Skilled Workers in Industry, Construction and Craftsmen 8 - Installation and Machine Operators and Assembly Workers 9 - Unskilled Workers 10 - Armed Forces Professions 90 - Other Situation 99 - (blank) 101 - Armed Forces Officers 102 - Armed Forces Sergeants 103 - Other Armed Forces personnel 112 - Directors of administrative and commercial services 114 - Hotel, catering, trade and other services directors 121 - Specialists in the physical sciences, mathematics, engineering and related techniques 122 - Health professionals 123 - teachers 124 - Specialists in finance, accounting, administrative organization, public and commercial relations 131 - Intermediate level science and engineering technicians and professions 132 - Technicians and professionals, of intermediate level of health 134 - Intermediate level technicians from legal, social, sports, cultural and similar services 135 - Information and communication technology technicians 141 - Office workers, secretaries in general and data processing operators 143 - Data, accounting, statistical, financial services and registry-related operators 144 - Other administrative support staff 151 - personal service workers 152 - sellers 153 - Personal care workers and the like 154 - Protection and security services personnel 161 - Market-oriented farmers and skilled agricultural and animal production workers 163 - Farmers, livestock keepers, fishermen, hunters and gatherers, subsistence 171 - Skilled construction workers and the like, except electricians 172 - Skilled workers in metallurgy, metalworking and similar 174 - Skilled workers in electricity and electronics 175 - Workers in food processing, woodworking, clothing and other industries and crafts 181 - Fixed plant and machine operators 182 - assembly workers 183 - Vehicle drivers and mobile equipment operators 192 - Unskilled workers in agriculture, animal production, fisheries and forestry 193 - Unskilled workers in extractive industry, construction, manufacturing and transport 194 - Meal preparation assistants 195 - Street vendors (except food) and street service providers		no



Admission grade	Feature	Continuous		Admission grade (between 0 and 200)		no
Displaced	Feature	Integer		1 – yes 0 – no		no
Educational special needs	Feature	Integer		1 – yes 0 – no		no
Debtor	Feature	Integer		1 – yes 0 – no		no
Tuition fees up to date	Feature	Integer		1 – yes 0 – no		no
Gender	Feature	Integer	Gender	1 – male 0 – female		no
Scholarship holder	Feature	Integer		1 – yes 0 – no		no
Age at enrollment	Feature	Integer	Age	Age of studend at enrollment		no


International	Feature	Integer		1 – yes 0 – no		no
Curricular units 1st sem (credited)	Feature	Integer		Number of curricular units credited in the 1st semester		no
Curricular units 1st sem (enrolled)	Feature	Integer		Number of curricular units enrolled in the 1st semester		no
Curricular units 1st sem (evaluations)	Feature	Integer		Number of evaluations to curricular units in the 1st semester		no
Curricular units 1st sem (approved)	Feature	Integer		Number of curricular units approved in the 1st semester		no
Curricular units 1st sem (grade)	Feature	Integer		Grade average in the 1st semester (between 0 and 20)		no
Curricular units 1st sem (without evaluations)	Feature	Integer		Number of curricular units without evalutions in the 1st semester		no
Curricular units 2nd sem (credited)	Feature	Integer		Number of curricular units credited in the 2nd semester		no
Curricular units 2nd sem (enrolled)	Feature	Integer		Number of curricular units enrolled in the 2nd semester		no
Curricular units 2nd sem (evaluations)	Feature	Integer		Number of evaluations to curricular units in the 2nd semester		no
Curricular units 2nd sem (approved)	Feature	Integer		Number of curricular units approved in the 2nd semester		no
Curricular units 2nd sem (grade)	Feature	Integer		Grade average in the 2nd semester (between 0 and 20)		no
Curricular units 2nd sem (without evaluations)	Feature	Integer		Number of curricular units without evalutions in the 1st semester		no
Unemployment rate	Feature	Continuous		Unemployment rate (%)		no
Inflation rate	Feature	Continuous		Inflation rate (%)		no
GDP	Feature	Continuous		GDP		no
Target	Target	Categorical		Target. The problem is formulated as a three category classification task (dropout, enrolled, and graduate) at the end of the normal duration of the course		no


# your task

You will practice your data cleaning skills on the main data (not the summarized version) by perfoming the following tasks: 
1. Explore the missingness in the dataset for categorical and numerical data
2. Develop a strategy to deal with the missing values, i.e deletion, imputation by mean or mode etc, whilst providing rationale for your approach.
3. Drop non-consequntial fields
4. Transform temporal data to their corrrect format (date time) 
5. Perfom a full EDA and demonstrate the validity of the following assumptions 
> - Moore's Law still holds, especially in GPUs.
> - Dannard Scaling is still valid in general.
> - CPUs have higher frequencies, but GPUs are catching up.
> - GPU performance doubles every 1.5 years.
> - GPU performance improvement is a joint effect of smaller transistors, larger die size, and higher frequency.
> - High-end GPUs tends to first use new semiconductor technologies. Low-end GPUs may use old technologies for a few years.
> - Process Size for Intel, AMD and Nvidia lies in comparatively lower range than for ATI and other vemdors
> - TSMC makes the highest number of chips in the world

6. Calculate and visualized the correlation among the features
7. Perfom the correct encoding for your data, in readiness for modelling. 

# bonus task 

Since it is your first week of ML, it is okay if you do not proceed to this section, however, if you feel adventureous, you can explore a classification model to predict whether a product is a GPU or a CPU based on the other independent variables. 
- Compare the perfomance of a Random Forest Classifier with that of a Logistic Regression Model


# data dictionary

# `semiconductor-chips.csv`

|variable                 |class     |description |
|:------------------------|:---------|:-----------|
|date                     |double    |Date of release    |
|type                     |character |Type of chip    |
|foundry                  |character | Creator    |
|vendor                   |character | Vendor    |
|process_size_nm_mean     |double    | Process size in nanometer    |
|process_size_nm_sd       |double    |    Process size in nanometer |
|tdp_w_mean               |double    | Thermal design profile    |
|tdp_w_sd                 |double    |Thermal design profile    |
|die_size_mm_2_mean       |double    | Die size in millimeters^2    |
|die_size_mm_2_sd         |double    |Die size in millimeters^2    |
|transistors_million_mean |double    | Transitor count in millions    |
|transistors_million_sd   |double    |Transitor count in millions    |
|freq_m_hz_mean           |double    | Frequency (Mhz)    |
|freq_m_hz_sd             |double    |Frequency (Mhz)    |
|n                        |integer   | Total number of observations for date, type, foundry, vendor grouping    |

