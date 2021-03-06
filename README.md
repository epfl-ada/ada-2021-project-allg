# The evolution of the presence of women’s voices in the media

The datastory can be found on the website: https://luciecastella2.github.io/ADA-Data-Story/

### Abstract  (150 words):

24% of the news sources -people quoted, heard, seen- are women, according to a 2015 study by the Global Media Monitoring Project (1).
The Me Too movement started to spread in 2017 after the sexual abuse allegations against Harvey Weinstein. This movement led to a raise of women’s voices everywhere.
The goal of this project is to track the evolution of the presence of women’s voices in the media following the Me Too movement, to see if a major feminist movement like this one has led to an increase in the number of women quoted. We can then see if women are underrepresented in the medias and if they are only quoted on certain subjects. We can also include the ethnicity and the age of the women that the medias highlight to find which social backgrounds are best represented.

### Research questions : 
Are women more quoted in the media since the Me Too movement in 2017 ? Are they only quoted on certain subjects (eg. Feminism) ? Women of which social backgrounds, ethnicity and age are best represented in the media ?

### Database:
The Quotebank dataset was used to conduct the project and to answer the research questions. The Quotebank is a corpus containing 178 million English news articles sourced from over 377 web domains between August 2008 and April 2020 (2).   

More information about dataset can be found here: 
Timoté Vaucher, Andreas Spitz, Michele Catasta, and Robert West
"Quotebank: A Corpus of Quotations from a Decade of News"
https://doi.org/10.1145/3437963.3441760

### Additional database : 
As additional database, the suggested .parquet file containing speakers attributes as Wikidata entities will be used. 
Since all additional information on the speakers that we need for our project is in the provided database, there is no need for further databases. 
We are aware that there is a general imbalance between men and women in many fields but as we are only looking at relative changes in our project, there is actually no need for this. 
An additional database showing the imbalance between men and women in different fields could be added and analyzed to compare.
 
### Methods : 
The Wikidata IDs of the speakers in the provided database will be used to find the speaker’s gender and see if the number of quotations from women has increased between 2015 and 2020, especially since the Me Too movement in 2017. This will be done by merging the gender information to our filtered quotbank dataframe. Then hypothesis testing approach for binary variables will be applied to test if the Me Too movement has an effect on the proportion of women as a speaker. Also, trend analysis of the time series will be conducted to see if the proportion is moving from year to year, and if the movement created a change, or just a peak on 2017 of women speakers and then the proportion goes down again. 
The Wikidata IDs of the speakers will also be used to find and merge the ethnicity, occupation and the age of the quoted women to the dataframe. 
To analyse the subjects of the quotes, a machine learning algorithm will be used. The machine learning algorithm that will be used still has to be decided. The idea is that the algorithm will recognise a set of subjects based on words appearing, the quotes of women will then be analysed to see if only some subjects are present, if there is a difference with the appearance on men's quotes. We will then try to analyse and explain why there is or is not a difference. 

### Contributions:
- Hypothesis testing approach for binary variables: Gabriel
- Handling text and analysis of the quotes: Lucie
- Trend analysis of the time series: Lilian
- Age and ethnicity analysis: Amaia
- Website: Everyone 

### Notes
The assistant's suggestion to use the Interrupted Time Series Analysis was noted and looked at. However, the time series had no obvious intervention at the time of the Me Too movement and therefore the use of the Interrupted Time Series Analysis was not applied.

Sources : 
(1)https://www.weforum.org/agenda/2020/03/women-representation-in-media/
(2)https://zenodo.org/record/4277311#.YbyxXy_37PD


ada-2021-project-allg