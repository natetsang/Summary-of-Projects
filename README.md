# Summary of my projects
Below are brief descriptions and links to a selection of data science and optimization projects that I've completed. Some of these are personal projects, while others were completed as part of my coursework at UC Berkeley.

__This is currently under construction.__ I have many ML/optimization project's I'd like to include and will be making them public periodically.

<b>1. Building an image classifier from scratch </b> https://github.com/natetsang/image-classification-ML

In this project, I develop an image classifier in Python from a dataset of roughly 1500 images in 20 categories. I identify over 15 key features and explore several ML models including logistic regression, KNN, SVM, and random forest. The performance of each model was assessed by testing on a separate zipfile of images. Test results indicate that models were roughly 35-40% accurate, which is reasonable given only traditional ML models were used.

<b>2. Dynamic programming for optimal battery use in PHEVs </b> https://github.com/natetsang/optimizing-PHEV-battery-use

Plug-in hybrid electric vehicles (PHEVs) utilize conventional fuel and an electric battery for propulsion. To maximize fuel efficiency, an energy management system can optimally control when to utilize the battery and how much power it should deliver. In this project, I utilize dynamic programming to optimally schedule battery usage for a PHEV vehicle undergoing an EPA emissions test cycle. I also test the impact of the battery's state of charge on total fuel consumption.

<b>3. Analysis of MLB data </b> https://github.com/natetsang/baseball-analytics

In this project, I seek to achieve two tasks. First, I analyze a dataset with limited features to determine the top 15 baseball players. Second, I develop a grading algorithm to quantify the quality of pitches. In complete both of these tasks without using ML techniques. Instead, I constrain myself to traditional analytical methods.

<b>4. Using ML to improve simulation time of airplane wings </b> https://github.com/natetsang/airplane-wing-design

The design of airplane wings (i.e. airfoils) typically involves building thousands and thousands of computational fluid dynamics (CFD) models, which can take hours. To drastically reduce simulation time, this project attempts an novel design process. Instead of running 60,000 CFD simulations, I run 1,000 - 10,000 simulations and then utilize ML to approximate the rest. Using a hybrid approach, runtime was reduced from hours to minutes, and accuracy (w.r.t. CFD modeling) was maintained.
