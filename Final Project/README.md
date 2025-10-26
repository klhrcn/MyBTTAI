Machine Learning Final Project: Defining and Solving a Real-World ML Problem
- This project represents my end-to-end implementation of a machine learning workflow — from selecting a real dataset to building, training, and evaluating a predictive model. The core objective was not just to train a model, but to demonstrate my ability to think like a data scientist: define a meaningful problem, justify modeling decisions, evaluate results, and interpret outcomes.

🎯 What I Set Out to Do
- The goal of this notebook is to simulate a real-world ML project from scratch. Instead of being given a predefined task, I was required to:
- Choose a dataset
- Define the problem myself
- Explain the reasoning
- Build a model accordingly
- Evaluate performance and reflect on next steps

I selected the World Happiness Report dataset and framed the problem as:
* “Can we predict a country’s happiness score (Life Ladder) based on socioeconomic indicators?”

Results:
* GDP per capita, social support, and healthy life expectancy are consistently the most influential factors in predicting a country’s happiness score
  * Among these, social support emerged as the strongest predictor
  * → Economic strength alone does not guarantee happiness—strong community networks and trust in social institutions play an even more critical role
* Countries with high levels of generosity and freedom to make life choices also tended to rank higher in happiness
  * Personal autonomy and civic engagement are vital in overall well-being
* Conversely: high levels of perceived corruption corresonded to a lower happiness score
