# digital-wellbeing-analytics
Using Data Analytics to Promote Healthier Digital Habits:<br>

Did you know that excessive internet use can actually rewire your brain? Prolonged internet usage, especially involving frequent task-switching and multitasking, may interfere with our ability to maintain focus on a single task for extended periods.<br>
It’s like training your brain to constantly seek the next notification or distraction, potentially at the cost of deep, sustained concentration.<br>

I dove into an impactful challenge this past week: using physical activity and other health-related metrics to detect early signs of problematic internet usage among children and adolescents.<br> This project aimed to analyze and identify the key factors that contribute to poor health and to verify if high amounts of time spent on the internet affect overall well-being.<br>

Let’s walk through what we did:<br>


1️⃣ Data Exploration and Understanding:<br>

Analyzed a dataset with 4,000+ rows and 80+ features, including demographic, behavioral, and physical health indicators.<br>
Applied descriptive statistics and visualizations to uncover key features about the dataset, such as the number of missing values, outliers, and a few notable patterns and trends.<br>

2️⃣ Data Preprocessing:<br>

Addressed missing values across features using tailored imputation methods<br>
Removed placeholder values and designed preprocessing functions to reduce cleaning time.<br>
Dropped highly correlated features to avoid repetition in the analysis and prevent multicollinearity.<br>

3️⃣ Exploratory Data Analysis (EDA):<br>

SII (Severity Impairment Index): A tool that measures how much a person's physical or mental functioning is impaired.<br>
Children's Global Assessment Scale (CGAS): A numeric scale used by mental health clinicians to rate the general functioning of youths under the age of 18.<br>
Physical Measures: Blood pressure, heart rate, height, weight, and BMI-related metrics.<br>
Bioelectric Impedance Analysis: A measure of body composition elements, including BMI, fat, muscle, and water content.<br>
Sleep Disturbance Scale: A tool to categorize sleep disorders in children.<br>
Parent-Child Internet Addiction Test: A 20-item scale measuring compulsive, escapist, and dependency-related internet use behaviors.<br>

Key Insight:<br>
The analysis revealed a moderate negative correlation between physical activity levels and Severity Impairment Index (SII).<br>
Children with lower physical activity levels and those using the internet for more than 3 hours a day tend to have higher SII scores, which correlates with increased BMI and body fat percentages.<br>
