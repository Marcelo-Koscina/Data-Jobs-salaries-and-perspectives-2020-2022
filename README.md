# Data Jobs salaries and perspectives 2020/2022
 A storytelling job, salaries and perspectives analysis on Data fields from 2020 until early 2022

Goal:

   This project focuses on presenting to interested parties or students dedicated to training in data science and its various specialties, a summarized overview of job opportunities around the world with the respective salary ranges of the profession, taking as a reference the information acquired between period of the year 2020 to date.
   It is based on a fictional but no less real story, which formulates questions and answers on the topic at hand.
   
Search sources:
   The data set in .csv format extracted from the website www.kaggle.com, prepared by Saurabh Shahane, as shown in the link below:
   
   https://www.kaggle.com/datasets/saurabhshahane/data-science-jobs-salaries
   
   The same was based on information extracted from the job search site 'ai-jobs.net'.
   
   
   Structure:
   
   The project was developed in two parts.
   
   
   1) The first part carried out on the jupyter notebook platform, in the python language, and following the 'data pipeline' principles,
   enabling connection to the SQL database platform. After extracting and transforming the data set, which included treatment and cleaning, 211 samples from around the world remained to be used as a reference. The following data set tables were relevant for further graphical analysis:
   
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
               
               
     obs. In this first part of the project, a code was also created applying the web scrapping methodology, which extracts a list from the Indeed job search site (www.indeed.com), with the most recent vacancies in the position of junior data analyst in Brazil. .
   
   
   
   2) The second part of the project was developed in the Tableau graphical platform, for visualization, data analysis, and the search for answers to the questions asked throughout the story.
   
   note:
   * Due to the large number of job sub-categories (lead, manager, consultant, etc.), the analysis was structured into four types of specialization:
   Data engineer, data analyst, data scientist and machine learning engineer.
   
   * Some outliers (salary values ​​very far from the average) were removed, as well as salary medians were used instead of averages to improve results accuracy.
      
   * The countries mentioned are highlighted not because they offer more job offers than others with perhaps more vacancies, but because they are also open to hiring foreigners, hence their greater relevance worldwide. Likewise, the respective salary averages, which vary proportionally with the cost of living in each location.
   
   
   
   The story:
   
   We have a story and it has a beginning...
   
     A great friend, dissatisfied with his current profession, and not discarding the idea of ​​moving abroad and, knowing that I have not been looking for friends anymore because I am immersed in the Ironhack bootcamp, invites me to have a coffee and ask for information about the my future new profession, which is data analyst.
     Then he asks a series of 9 questions. The first one follows below:
   
   QUESTION 1: I have seen a lot of specializations in this area of ​​data and I didn't understand anything, can you give me a quick idea?
   
   Following the common sense of any analysis, I went, before the meeting, to do a research on the subject, already imagining that this would be a possible initial question:
   
   Briefly:
   
   *Data Engineer: Specialized in data structure. Prepares the material and code base for the other data areas.
   *Data analyst: collects, treats, analyzes the data, and seeks solutions according to the analysis.
   *Data scientist: works with a wider range of information. A more macro view, more planning than the immediate analysis itself, also dealing with predictions.
   *Machine learning engineer: works with one of the artificial intelligence fields. The development of virtual customer service is an example.
   
   
   
   * The other 8 questions are answerd in a storytelling, project available at Tableau Public, through link below:
   https://public.tableau.com/app/profile/marcelo5344/viz/Datajobssalariesandperspectives20202022/AnunpretentiousDataFieldsjobssalariesandcareerperspectivestory___?publish=yes   
