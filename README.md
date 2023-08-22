# From Gaze to Empathy: Machine Learning Exploration

This project aims to predict empathy scores using gaze and eye movement data. By employing a variety of machine learning models, our goal is to discern the relationship between different features and the target variable: empathy scores.

## Table of Contents
- [Installation and Setup](#installation-and-setup)
- [Data Preparation](#data-preparation)
- [Preprocessing](#preprocessing)
- [Visual Analysis](#visual-analysis)
- [Model Analysis](#model-analysis)
- [Key Takeaways and Recommendations](#key-takeaways-and-recommendations)
- [Conclusion](#conclusion)
- [References](#references)
- [License](#license)
- [Dataset Sources](#dataset-sources)

## Installation and Setup <a name="installation-and-setup"></a>
### Requirements
- Python 3.x

### Code Setup
- Unzip the EyeT zip using a designated function.
- Store the data locally on the machine.
- Load the data into a single CSV file.

## Data Preparation <a name="data-preparation"></a>
The data originates from the EyeT4Empathy dataset, which comprises raw eye-tracking movements and a related questionnaire.

## Preprocessing <a name="preprocessing"></a>
- Introduction of the 'gaze_distance' feature.
- Handling of missing values via imputation.
- Standardization of features.
- Division of data into training and test sets.

## Visual Analysis <a name="visual-analysis"></a>
This segment showcases a correlation matrix for the 'Gaze point X' and 'Gaze point Y' features, emphasizing their interrelationships.

## Model Analysis <a name="model-analysis"></a>
This section offers a comprehensive evaluation of each machine learning model, highlighting their advantages, limitations, and appropriate use-cases. Notably, the recently introduced 'gaze_distance' feature demonstrated significant importance in models like the Decision Tree.

## Key Takeaways and Recommendations <a name="key-takeaways-and-recommendations"></a>
- Eye movement and gaze data are potent predictors of empathy scores.
- The 'gaze_distance' feature's introduction has proven advantageous.
- Deep learning models could offer further insights.
- Amassing more diverse data might enhance model generalization.

## Conclusion <a name="conclusion"></a>
The project ventured to predict empathy scores using gaze and eye movement data. Through diverse machine learning models, we discerned relationships between various features and the empathy score.

## References <a name="references"></a>
P. Lencastre, S. Bhurtel, A. Yazidi, S. Denysov, P. G. Lind, et al. EyeT4Empathy: Dataset of foraging for visual information, gaze typing, and empathy assessment. Scientific Data, 9(1):1–8, 2022.

## License <a name="license"></a>
This endeavor is protected under the MIT License. Kindly refer to the LICENSE.md file for detailed information.

## Dataset Sources <a name="dataset-sources"></a>
- Raw data
- Eye-tracking movements
- Questionnaire
