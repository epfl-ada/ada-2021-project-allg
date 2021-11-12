# The evolution of the presence of women’s voices in the media
ada-2021-project-allg created by GitHub Classroom


Abstract  (150 words):

24% of the news sources -people quoted, heard, seen- are women, according to a 2015 study by the Global Media Monitoring Project (1).
The Me too movement started to spread in 2017 after the sexual abuse allegations against Harvey Weinstein. This movement led to a raise of women’s voices everywhere.
The goal of this project is to track the evolution of the presence of women’s voices in the media following the Me too movement, to see if a major feminist movement like this one has led to an increase in the number of women quoted. We can then see if women are underrepresented in the medias and if they are only quoted on certain subjects. We can also include the ethnicity and the age of the women that the media highlight to find signs which social backgrounds are best represented.

##Assistant comment : Make sure to account for the fact that in many fields there is an imbalance between men and women (e.g., in many parliaments). But this should be less of a problem when looking at relative changes.

Research questions : Are women more quoted in the media since the Me too movement in 2017 ? Are they only quoted on certain subjects (eg. Feminism) ? Women of which social backgrounds, ethnicity and age are best represented in the media ?

Additional database? : 
The suggested .parquet file containing speakers attributes as Wikidata entities. 
Since all additional information on the speakers that we need for our project is in the provided database, there is no need for further databases. 
We are aware that there is a general imbalance between men and women in many fields but as we are only looking at relative changes in our project, there is actually no need for this. 
If there is time, an additional database showing the imbalance between men and woman in another field would be added to compare. 
 
Methods : The Wikidata IDs of the speakers in the provided database will be used to find the speaker’s gender and see if the number of quotations from women has increased between 2015 and 2020. This will be done by merging the gender information to our filtered speaker database. These IDs will also be used to find the ethnicity and the age of the quoted women.
To answer the research question if women are only quoted on certain subjects, machine learning will be used to analyze the content of the quotes. 
--> more details on methods

Proposed timeline :
- Week 8 : end Milestone 2 : kick-off and checking if all good
- Week 9 : ML algorithm for content analysis
- Week 10 : incorporating feedback from Milestone 2
- Week 11 : add information of age and ethnicity to the database
- Week 12 : put results together and write the story 
- Week 13 : Milestone 3 : wrap-up and debug of last problems

Internal milestones : (who does what)
Quotes subject by Machine learning algorithm: XX
Women's age and ethnicity: XX

Questions for TAs :

Sources : (1)https://www.weforum.org/agenda/2020/03/women-representation-in-media/