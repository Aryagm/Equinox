# Equinox: Changing the world, one student at a time

<hr/>

![](https://cdn.discordapp.com/attachments/889980120461361225/1008177908726104144/unknown.png)

<hr/>

## The Problem
![](https://media.istockphoto.com/vectors/chalkboard-friends-walk-vector-id584478142?k=20&m=584478142&s=612x612&w=0&h=L_Xn1ujs4v7BHmv5dnMqPbuxsZjN418JhWiTh8XVNik=)

<br/>

Every year, over 1.2 million or 25% of students drop out of high school in the United States alone. That’s a student every 26 seconds! Students dropping out of high school has become a huge problem in America which is seldom talked about! Increasing high school graduation rates is essential in the development of a save and innovative society. A high school dropout will earn $200,000 less than a high school graduate over his lifetime and almost a million dollars less than a college graduate. Additionally, In the U.S., high school dropouts commit about 75% of all crimes. It should be our responsibility to set up future citizens for success by ensuring that they graduate high school.

<hr/>

## The Solution

![](https://cdn.discordapp.com/attachments/889980120461361225/1008283684031430717/unknown.png)

<br/>

This is where Equinox comes in! Equinox is a cohesive solution designed to identify students who have a high risk of dropping out of high school. School boards can use this tool to identify students who are at risk of not graduating from high school and may benefit from targeted interventions. Equinox provides an efficient and easy to use solution that can be adopted by education departments around the globe! Based on a variety of longitudinal, student-level data, we developed predictive models to identify students who are at risk of not graduating from high school on time and may benefit from targeted interventions. Our major goal was to identify students who are at risk for not graduating on time. We used data from previous high school cohorts and modeled their outcomes. We can then apply this predictive model on current students to predict their risk of falling behind. As a second step, we applied survival analysis techniques to generate an urgency score associated with each of the students. This additional information can be used by school counselors to decide which students are in most immediate need of attention. To explore possible under-matching, we merged student data from the final year of high school with 5 years of post-secondary enrollment and graduation data. 

## Impact

![](https://cdn.discordapp.com/attachments/889980120461361225/1008283891267797062/unknown.png)

Why is this so revolutionary and important? The impact Equinox can have is immense, but it is not directly evident at first sight. The implications this piece of software has on society is astonishing. High school dropouts are 3.5 times more likely to be arrested and eight times more likely to be incarcerated than their counterparts who graduate from high school. In a study conducted by John Hopkins university, increasing high school graduation rates by 5% can half the number of violent crimes in a city. We can achieve something with a national investment of a few million dollars that would otherwise take tens of billions of dollars and a huge risk. The importance of this technology lies in its efficiency. Apart from reducing crimes, increasing high school graduation has been proven to result in better financial conditions, healthier living conditions and healthier local economies. It is an investment that gives exponential returns at a very low risk. Equinox can break economic barriers, create social equity and be a driving force for social good.

<hr/>

## Technology Used

![](https://cdn.discordapp.com/attachments/889980120461361225/1008283745184399370/unknown.png)

I used several technologies behind the scenes to make this project easy to use and powerful. I used Streamlit in the frontend to display the dashboard and connect to the machine learning models in the back. The data I used for the project was collected from the Arizona’s Education Department. The data had quirks like missing values, skewed columns and large ranges. I did some preprocessing to make the data usable. I also dived deep into analyzing the data and created several reports to summarize the results. For the predictor, I tried several models. Ensembles of tree-based models like Xgboost, Cat Boost and Random Forests gave the best accuracy. I tried creating RNN’s with TensorFlow, but they tended to over fit the relatively small dataset. Using these tuned predictive models, we can generate risk scores for new sets of students.

## Future Improvements

I believe that Equinox has immense potential and a few steps in the right direction can take it to the next level. The following steps are the improvements I hope to make to Equinox in the coming weeks:

1. Improve accuracy of the ML models by collecting more data and testing additional model architectures.
2. Identify additional factors that contribute to increased dropout rates.
3. Make the UI more streamlined (move from Streamlit to react).

Equinox is currently a fully functional prototype which has the ability to change the very fabric of our society if developed properly. 

![](https://cdn.discordapp.com/attachments/889980120461361225/1008286819726659635/unknown.png)]
