# Netflix-Movies-Data-Analysis

## Project Background

Netflix, founded on August-29-1997, in Scotts valley, California, by Reed Hastings and Marc Randolph began as a DVD-by-mail service. Hastings, a computer scientist and a mathematician, cofounded the company after being inspired by a hefty late fee from a traditional video rental store. Randolph a marketing executive, played apivotal role in shaping Netflix's early user interface and branding.

In 2007, Netflix introduced streaming services allowing subcribers to watch movies and TV shows instantly online. This strategic shift capitalized on the growing internet bandwidth and changing costumer preferences, propelling Netflix into aleading global streaming platform. By 2010, company began its global expansion, starting with Canada, and by 2016 it was available in over 190 countries.

As of 2024, Netflix reported a revenue of nearly $10 billion in the third quarter, with profits reaching $2.4 billion. The platform boasts over 283 million paid memberships across more than 190 countries, offering a vast library of TV series, films, and games in various genres and languages.Overall, Netflix's evolution from a DVD rental service to a global streaming giant underscores its adaptability and innovative approach in the entertainment industry.

### Objective / Business Problem:

Netflix is known for its work in data science, AI, and ML, particularly for building strong recommendation models and algorithms that understand customer behavior and patterns. Suppose you are working in a data-driven job role, and you have a dataset of more than 9,000 movies. You need to solve the following questions to help the company make informed business decisions accordingly.

### Key Questions:
- What is the most frequent genre of movies released on Netflix?
- Which has highest votes in vote average column?
- What movie got the highest popularity? What is it's genre?
- What movie got the lowest popularity? What is it's genre?
- Which year has the most filmmed movies?

## Data Preprocessing

After looking at the dataset, we started cleaning the data as it required before analysis check their data type and for any duplicates in the set. Then dropped three columns as they had no use in our analysis, and convert Vote_Average column from integer data type to object data type by replacing the vote avg. no into specified range of classes. Also spereated the genre column to get 1 genre at 1 time. 

## Insights and data interpretation

- As per our requirement, a bar graph was plotted, where we got that 'Drama' genre is most frequently released and 'Western' is least released on Netflix.
- As per analysis, in the Vote_Average column most users rated movies as 'Average' which was analyzed using bar graph.
- The movie that got the highest popularity as per analysis is 'SpiderMan: No Way Home' and the genre was 'Action, Adventure and Science Fiction'.
- The movie that got the lowest popularity as per the analysis are 'The United States vs. Billie Holiday' & 'Threads' with the genre of ' Music, Drama , History War, and Science Fiction'.
- The year that filmmed most movies as per our analysis was 2020, which was analysed using histogram graph.

### Key Findings 

- Drama genre is the most frequent genre in our dataset and has appeared more than 14%of the times among 19 other genre.
- We have 25.5% of our dataset with popular vote (6520 rows).Drama again gets the highest popularity among fans by having more than 18.5% of movies popularities.
- Spiderman: No Way Home has the highest popularity rate in our dataset and it has genre of Action, Adventure and Science Fiction.
- The United States vs. Billie Holiday, threads has the lowest popularity rate in our dataset and it has genre of music, drama, war,sci-fi, and history.
- The year 2020 has the highest rate of filmming rate in our dataset.

