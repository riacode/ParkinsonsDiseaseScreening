# ParkinsonsDiseaseScreening
Screening for Parkinson’s: Isolating Characteristic Typing Patterns with Machine Learning

Studies have shown that approximately 60,000 Americans are diagnosed with Parkinson’s disease (PD) each year, and there are many more who go undiagnosed. People are not getting the treatment they need early on since the procedures and screening tools for detecting Parkinson’s are very time-consuming and expensive. In this project, a more affordable and convenient screening methodology has been developed to detect Parkinson’s early on while uncovering key behavioral insights in Parkinson’s patients. This is done by analyzing keyboard typing data collected from human participants and then finding the most accurate machine learning algorithm to classify whether or not a participant has Parkinson's. The typing data has many features related to a person’s typing, such as the hold time, latency time, and flight time between keys. By using basic statistical, logistic regression, linear support vector machine, and random forest models, the algorithm with the highest accuracy score on the dataset is found and then unpacked to see what features it relies on. Not only do the results generated from this project provide the basis for a potential low-cost and scalable Parkinson’s screening tool, but they also reveal tremendous insights into some unique behaviors of Parkinson’s patients. For example, a characteristic typing pattern that was isolated through the feature importances is LR latency, the time between left and right key presses, implying that perhaps Parkinson’s patients have trouble transitioning from one task to another. The vision is to use this algorithm in typing tests across populations to quickly screen for Parkinson’s.
