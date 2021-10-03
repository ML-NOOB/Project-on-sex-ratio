# Project-on-sex-ratio
The gender ratio in India is really skewed.  As per census 2011 there are 943 females per 1000 males.
Global average is 101 males for every 100 females. However, this global average is skewed by populous countries like India and China, where sex ratio suffers because of prevalent gender discrimination. So for countries in where gender discrimination is less prevalent , have females out numbering males. When it comes to countries of South and south east asia , the sex ratio is 1043 on average with a standard deviation of 40. The sex ratio at birth is 957 +- 15 for these countries.
 Globally  in most of the countries where female foeticide/infanticide is absent females outnumber males. 
The states of Haryana and Punjab which is the topic of study here has sex ratio of 879 and 895 respectively. This is more than 3 standard deviation from mean. The  child sex ratio is 832 and 888 for these two states. The state of poor sex ratio in these states has been a cause of worry for decades and it is having impact on social stability. Also we cannot neglect gender justice as a god in itself and the fact that more than 10% of women have gone missing in these states is something which should trouble us all.
The aim of this project is to find the determinants of sex ratio and child sex ratio in these states and also do a comparison between these states, to find whether the same determinants play the role in both these states
The reason for selecting Haryana and Punjab for this project is as follows:-
•	These two states are at the bottom of scale in terms of sex ratio and child sex ratio
•	They are neighboring states so we could hope for some similarities in their sociological order. This would facilitate comparison
•	Both of these states are comparatively affluent and have mix of both rural and urban population. 
METHODOLOGY
Data Source
The source of our DATA is NFHS-4 which was held in 2014-15.  The reasons for using this data is because it’s :-
•	Reliable
•	Comprehensive
•	Available
•	Representative(collected from around 800 households in each districts.
Technique:-
The methodology used is K-Means clustering. Here we use an unsupervised ML algorithm to cluster together data points and thereby we would try to understand whether we can find some underlying patterns in the data.
Linear regression has also been used to plot the relationship between determinants and sex ratio and Sex ratio at birth.

TOOLS:-
Jupyter – LAB(Python)
Microsoft excel.
Exploring the determinants:-
Poor sex ratio is generally associated with  developing countries, where scarcity of resources along with gender discrimination may lead to families preferring male child. 
This however at times may lead to policy makers targeting for developmental and economic factors to improve sex ratio. This project aims to understand , what role such factors have to play in sex ratio and child sex ratio.
So we are going to explore the impact of developmental factors on sex ratio on sex and child sex ratio.
The factors that we are going to focus are on, mens literacy rate(%), womens literacy rate(%), women who have had >10 years of schooling(%), Quality of life (access to santiation, drinking water, fuel as indicator for this), institutional births(%) to measure access to maternal and child health services.
We would also explore the relationship within these factors also, inorder to check for any correlations and gaher additional insights.
We also use mini_max scaling to scale these factors from (0,1) in order to bring out the relative difference between districts. As we are more interested in relative differences between the districts. This would enable us to identify districts which need greater focus.

