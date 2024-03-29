# New Rocket Company Project Bob

Worked on a new rocket company named "SpaceY" that would like to compete with SpaceX founded by Billionaire industrialist Ellon Musk. Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. to compete with SpaceX we need to understand these informations.

Project Steps:

Collected the rocket launch data from the SpaceX API 
Web-scraped the SpaceX table in the wikipedia page to collect Falcon 9 historical launch records 
Performed some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models 
Built an Interactive map with folium to find some geographical patterns about launch sites. 
Built an Interactive dashboard using plotly dash.
Implemented the machine learning classification model to predict if a rocket will land successfuly or not using logistic regression, KNN, desision tree and support vector machine. 
