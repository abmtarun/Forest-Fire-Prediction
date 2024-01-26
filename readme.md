# Forest Fire Prediction and Analysis

This repository is a treasure trove of discovery and algorithmic alchemy, focusing on the Algerian forest fires dataset. Our quest is to harness the power of historical data, using exploratory data analysis and machine learning sorcery, to predict the elusive patterns of future forest fires in Algeria. By intertwining data with prediction, we aim to unlock secrets nestled in the heart of nature's fiery phenomena.

# About the Dataset

The dataset serving as the cornerstone of this project is a meticulously compiled collection of data chronicling forest fires in two distinct regions of Algeria: the Bejaia region and the Sidi Bel-Abbes region. This compilation covers the critical fire season months from June to September in the year 2012. It's a rich tapestry of data that includes a variety of features:

1.  **Date (DD/MM/YYYY):** This captures the day, month (spanning from June to September), and the year (2012), pinpointing the exact moment in time for each event.
    
2.  **Weather Data Observations:**
    
    -   **Temp:** This reflects the maximum temperature at noon in degrees Celsius, varying from a mild 22 to a scorching 42 degrees.
    -   **RH:** Relative Humidity, expressed in percentage, ranging from a dry 21% to a moist 90%.
    -   **Ws:** Wind speed, measured in kilometers per hour, with readings between a gentle 6 km/h to a more robust 29 km/h.
    -   **Rain:** This represents the total rainfall for the day, measured in millimeters, with a spectrum from 0 (no rain) to 16.8 mm.
3.  **FWI Components:**
    
    -   **Fine Fuel Moisture Code (FFMC):** An index from the FWI system, ranging from 28.6 to 92.5, indicating the combustibility of fine fuels.
    -   **Duff Moisture Code (DMC):** Also from the FWI system, this index ranges from 1.1 to 65.9 and reflects the moisture level of decomposed organic material.
    -   **Drought Code (DC):** This index, part of the FWI system, ranges from 7 to 220.4, indicating the dryness of deeper, compact organic layers.
    -   **Initial Spread Index (ISI):** From the FWI system, this index ranges from 0 to 18.5 and signifies the rate of fire spread.
    -   **Buildup Index (BUI):** Another FWI component, ranging from 1.1 to 68, reflecting the amount of combustible material.
    -   **Fire Weather Index (FWI):** An overall index ranging from 0 to 31.1, indicating the general risk of fire.
4.  **Classes:** The dataset categorizes each instance into two classes - 'fire' and 'not fire,' enabling a clear distinction for analytical purposes.
    

This dataset is not just a collection of numbers and dates; it's a vital tool for unraveling the complex tapestry of factors that lead to forest fires in Algeria. By leveraging this data, we can enhance our understanding of fire dynamics in these regions and develop predictive models to foresee and mitigate future forest fire incidents. It's a step towards not only comprehending the patterns and causes of these natural disasters but also in preparing and preventing them with greater efficacy


# Machine Learning Algorithms

In this project, we have strategically selected and implemented a suite of machine learning algorithms, each chosen for their unique strengths and suitability for the task at hand – predicting forest fires in Algeria. These algorithms are applied to analyze the intricate patterns within the dataset, offering insights into the likelihood of forest fires under varying conditions. The algorithms used include:
The following machine learning algorithms have been implemented on the data:

-   Logistic Regression
-   Decision Tree Classifier
-   Random Forest Classifier
-   XGB Classifier


1.  **Logistic Regression:** This algorithm is a staple in the world of predictive modeling, especially renowned for its simplicity and effectiveness in binary classification problems. In our case, it's used to distinguish between the two classes - 'fire' and 'not fire'. By analyzing the relationships between the various features like temperature, humidity, wind speed, and the FWI components, Logistic Regression provides a probability score indicating the likelihood of a forest fire occurrence.
    
2.  **Decision Tree Classifier:** Like a skilled storyteller, this algorithm breaks down the complex decision-making process into a series of simpler, easier-to-understand choices – much like the branches of a tree. Each node in the tree represents a crucial decision point, such as the level of the Drought Code or the Wind Speed, leading down different paths to a conclusion of 'fire' or 'not fire'. This classifier is particularly useful for visualizing the decision paths and understanding the key factors that contribute to forest fires.
    
3.  **Random Forest Classifier:** Imagine an ensemble of decision trees, each contributing its voice to the final decision. The Random Forest Classifier creates multiple decision trees, each trained on different subsets of the data, and then aggregates their predictions. This approach not only captures a more comprehensive picture of the data but also reduces the risk of overfitting, making it a robust and reliable model for predicting forest fires.
    
4.  **XGB Classifier:** Short for eXtreme Gradient Boosting, this is an advanced implementation of gradient boosting machines. It's a powerhouse of an algorithm, known for its speed and performance. The XGB Classifier builds sequential trees, where each new tree attempts to correct the errors made by the previous ones. It's particularly effective in handling diverse data types and distributions, making it an excellent choice for the complex and varied features of the forest fire dataset.
    

By harnessing these algorithms, we aim to uncover the subtle patterns and relationships within the data, providing a predictive lens through which we can better understand and anticipate forest fire occurrences in Algeria. This not only aids in preparedness and response strategies but also contributes significantly to research and knowledge in the field of environmental data science.

# Results
The results of the machine learning models are compared and evaluated, and the best performing model is selected based on its accuracy.