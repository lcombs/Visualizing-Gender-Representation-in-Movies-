Group Members: Elizabeth Combs, Lauren D'Arinzo, Amber Teng

“Regardless of the content, a film has the power to shape perceptions of moviegoers on a range of subjects from love and marriage to the work of the government” - cf. Franklin 2006 ; Kolker 1999 ; Ortega-Liston 2000 ; Riggle, Ellis, and Crawford 1996

# Visualizing-Gender-Representation-in-Movies
http://imdbgenderrepresentation.getforge.io/

## Overview:
The Bechdel test is a blunt, basic measure of gender equality in fictional media. The test is comprised of three criteria: a movie or work of fiction has to (1) have at least two women in it, (2) who talk to each other, and (3) have a conversation that revolves around a topic other than a man.

From a data science perspective, we wondered if and how we could automate the process of scoring a film based on the Bechdel criteria. This project aims to complete a descriptive analysis to assess the potential of creating such a method.

## Conclusions:
In this descriptive exploration of data, we have begun to see how nuanced an automation methodology would need to be to accurately capture the scoring of the Bechdel test. It would be difficult to find single proxy variables for the 3 criteria of the test, and feature engineering would need to include domain knowledge. This is not to say that automation is impossible; but our takeaway is that, as Data Scientists, we are the ones who need to voice concerns about using proxies that aren’t representative, and we should include the voices of domain experts when modeling qualitative outcomes that may be subjective.

Finding a way to automate the Bechdel test may be a difficult undertaking; however, it could help improve the measure of the true proportion of Bechdel passing films by scoring all movies in the IMDb and beyond. It is of note is that it is also not the only metric for quantifying representation in media, as it only considers one identity variable -- gender. Washington Post writer Alyssa Rosenberg claims "The Bechdel Test set a very low floor for Hollywood. We can't let it become the ceiling for progress [3]." In the past decade, many other representation tests have been formulated, considering the distribution of people who work on the film's production, or relating other intersectional features like race, ethnicity, socioeconomic status, so that representation is inclusive to identities beyond cisgender white women. Though our analysis focuses on the Bechdel Test, our suggestions about feature engineering can help establish similar methodologies for other tests and continue to build a more equitable movie industry.

## Data Sources: 
- https://www.imdb.com/interfaces/ 
- https://github.com/matthewfdaniels/scripts/blob/graphs/character_list5.csv 
- http://bechdeltest.com/api/v1/getAllMovies
