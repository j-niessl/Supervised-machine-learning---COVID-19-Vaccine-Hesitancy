# Supervised-machine-learning---COVID-19-Vaccine-Hesitancy
A mini machine learning project. Using classifier models to predict if a person would be hesitant to get the COVID-19 shot in the US. Exploring features contributing to vaccine hesitancy



Dataset obtained from Kaggle: https://www.kaggle.com/datasets/cid007/predicting-covid19-vaccine-hesitancy?select=vh_data15.csv

Features are:

County Density
Vaccine_Trust_Index: The final index takes the mean value of the three response-“the vaccine is safe”, “the vaccine is effective” and “the public has been provided with enough information about the coronavirus vaccine”. Values range from 0 to 10, where 0 indicates complete disagreement, and 10 indicates complete agreement.
Personal_Responsibility: Values range from 0 to 10, where 0 indicates complete disagreement, and 10 indicates complete agreement.
Trust_Science_Apolitical: Extent to which respondents are confident political biases do not impact scientific research. variables range from 0 to 10, with higher values indicating greater trust.
Trust_Science_Politicians: Extent to which a respondent believes that politicians and the media can be trusted to appropriately use and accurately communicate scientific findings. Values for all aforementioned variables range from 0 to 10, with higher values indicating greater trust.
Trust_Science_Media: Extent to which a respondent believes that politicians and the media can be trusted to appropriately use and accurately communicate scientific findings. Values for all aforementioned variables range from 0 to 10, with higher values indicating greater trust.
Trust_Science_Community: Extent to which respondents have confidence in the scientific community.values range from 0 to 10 where 0=“Never” and 10=“Always”.
Trust_National: (0–10; 0=”Never” Trust; 10=”Always” Trust)
Trust_State: (0–10; 0=”Never” Trust; 10=”Always” Trust)
Trust_Local: (0–10; 0=”Never” Trust; 10=”Always” Trust)
Trust_Media: How often a respondent can trust media to “do what is right”: values range from 0 to 10 where 0=“Never” and 10=“Always”.
Perceived_Risk: Extent to which an individual agrees that the coronavirus “poses a serious risk to my health”.(0–10 scale where 0 = complete disagreement and 10 = complete agreement).
Perceived_Network_Risk: Extent to which they agree it “poses a serious risk to those with whom [they] regularly interact” (0–10 scale where 0 = complete disagreement and 10 = complete agreement).
Doctor_Comfort: Extent to which a respondent agrees that they “feel comfortable going to the doctor” . Values range from 0 to 10, where 0 = complete disagreement and 10 = complete agreement.
Fear_Needles: Extent to which a respondent agrees that they “are afraid of needles”. Values range from 0 to 10, where 0 = complete disagreement and 10 = complete agreement.
Condition_Pregnancy: 0 = No; 1 = Yes
Condition_Asthma: 0 = No; 1 = Yes
Condition_Lung: 0 = No; 1 = Yes
Condition_Diabetes: 0 = No; 1 = Yes
Condition_Immune: 0 = No; 1 = Yes
Condition_Obesity: 0 = No; 1 = Yes
Condition_Heart: 0 = No; 1 = Yes
Condition_Organ: 0 = No; 1 = Yes
County_Cases: the proportion of people in the county in which they reside that have been infected
County_Cases2wk: the proportion of people in the county in which they reside that have been infected
Male: 0 = No; 1 = Yes
Race: 1 = white; 2 = Black; 3 = Hispanic; 4 = other
Age
PS_Index: How “politically sophisticated” or knowledgeable an individual is, by gauging their ability to correctly answer several political trivia questions4: (0–1; 0 = zero percent correct; 1 = 100 percent correct).
Natural_Science_Literacy: How scientifically literate an individual is. Answers of a number of natural science based trivia questions: values range from 0 to 1, where 0 = zero percent correct and 1 = 100 percent correct.
College_Degree: (1 = Yes; 0 = No)
Pandemic_Impact: Extent to which i) their financial health and ii) their mental health was impacted by the pandemic (0–10, where 0 =“major negative impact” and 10=“major positive impact”):
Pandemic_Impact_Network: Extent to which i) their financial health and ii) their mental health was impacted by the pandemic (0–10, where 0 =“major negative impact” and 10=“major positive impact”):
Infected_Personal: Whether they have already been infected (Infected Personal: 0 = No; 1 = Yes)
Infected_Network: Whether someone in their immediate network has been infected (Infected Network: 0 = No; 1 = Yes)
Biden: 0 = No; 1 = Yes
Trump: 0 = No; 1 = Yes
Party_ID: 1 = Democrat; 2 = Independent; 3 = Libertarian; 4 = Republican; 5 = other
Household_Income: <10,000 (=1); 10,000-19,999 (=2); 20,000-29,999 (=3); 30,000-39,999 (=4); 40,000-49,999 (=5); 50,000-59,999 (=6); 60,000-69,999 (=7); 70,000-79,999 (=8); 80,000-89,999 (=9); 90,000-99,999 (=10); 100,000-149,999 (=11); >150,000 (=12)
Vaccine_Required: Whether an “employer, school, or other entity” requires that they get the vaccination (1 = Yes; 0 = No or Unsure).
Evangelical: Whether an individual identifies as a Christian Evangelical (=1) or not (=0).
Vaccine_Hesitant: Vaccine Hesitant—takes a value of 0 when a respondent had either i) already received one dose of the vaccine or ii) indicated that they planned on getting it “as soon as possible”. Vaccine Hesitant takes a value of 1 if the respondent i) had not yet received a vaccine, and ii) indicated that they were either a) unsure about getting the vaccine, b) planning to wait to get the vaccine, or iii) refusing to get the vaccine.
