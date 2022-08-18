# Data Jobs salaries and perspectives 2020/2022
 A storytelling job, salaries and perspectives analysis on Data fields from 2020 until early 2022

 Data jobs and salaries 2020/2022 analysis

   * Goal: This project focuses on presenting to interested parties or students dedicated to training in data science and its various specialties, a            overview of job opportunities around the world with the respective salary ranges of the profession, taking as a reference the information acquired          between period of the year 2020 to date.
   It is based on a fictional but no less real story, which formulates questions and answers on the topic at hand.
   
   Search sources:
   The data set in .csv format extracted from the website www.kaggle.com, prepared by Saurabh Shahane, as shown in the link below:
   
   https://www.kaggle.com/datasets/saurabhshahane/data-science-jobs-salaries
   
   The same was based on information extracted from the job search site 'ai-jobs.net'.
   
   
   * The Story
   
   We have a story and it has a beginning:
   
   A great friend of mine, not satisfied with his current career, and not discarding the idea of moving abroad, scheduled a meeting to have a coffee and      ask for information about my new profession. Then he asks a series of 9 questions. The first follows below:
   
   QUESTION 1: I saw a lot of specializations iat data world and I didn't understand anything, can you give me a quick idea?
   
   Following the common sense of any analysis, I went, before the meeting, to a subject research, already imagining that this would be a possible initial      question:
   
   Briefly:
   
   *Data Engineer: Specialized in data structure. Prepares the material and code base for the other data areas.
   *Data analyst: collects, treats, analyzes the data, and seeks solutions according to the analysis.
   *Data scientist: works with a wider range of information. A more macro view, more planning than the immediate analysis itself.
   *Machine learning engineer: works in the field of artificial intelligence. The development of virtual customer service is an example.
   
   
   * The  8 other questions are outlined and answered in a storytelling available at Tableau through the link below:
   
     https://public.tableau.com/app/profile/marcelo5344/viz/Datajobssalariesandperspectives20202022/AnunpretentiousDataFieldsjobssalariesandcareerperspectivestory___
   
   Structure:
   
   The project was developed in two parts:
   
   1) The first part carried out on the jupyter notebook platform, in the python language, and following the 'data pipeline' principles, enabling connection to the SQL database platform. After extracting and transforming the data set, which included treatment and cleaning, 211 samples from around the world remained to be used as a reference. The following data set tables were relevant for further graphical analysis:
   
   *job_title - type of specialization in the data area
   
   *experience_level - professional category by time of experience
                     EN - Entry Level / junior (< 2 years of experience);
                     MI - Middle Level (>= 2 and < 5 years of experience);
                     SE - Senior (>= 5 years of experience);
                     Former Executive / Director.
                     
   *remote_ratio - proportion of remote work offered in the job vacancy
                 0 - < 20% of remote work;
                 50 - >= 20% and < 80% of remote work;
                 100 - >= 80% of remote work.
                 
   *monthly_salary_usd - offered monthly salary converted to USD
   
   *work_year - the year in which the hiring took place: 2020 and 2021/2022
                The years 2021/2022 are on the same line as the data set used is still being updated in Kaggle.
               
              
   2) The second part of the project was developed in the Tableau graphical platform, for visualization, data analysis, and the search for answers to questions asked throughout the story.
   
   Notes:
   * Due to the large number of job sub-categories (lead, manager, consultant, etc.), the analysis was structured into four types of specialization:
     Data engineer, data analyst, data scientist and machine learning engineer.
   
   * Some outliers (salary values very far from the average) were removed, as well as salary medians were used instead of averages to improve results accuray.
   
   * The countries mentioned are highlighted not because they offer more job offers than others with perhaps more vacancies, but because they are also open to hiring foreigners, hence their greater relevance worldwide. Likewise, the respective salary averages, which vary proportionally with the cost of living in each location.
   
