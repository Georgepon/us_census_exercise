# US Census Income Prediction

This repo contains all the files that comprise the deliverable for the US Census exercise. One can go through either the notebook, the slide deck, or both. The notebook is less formal in the language used, but still provides the same insights as the presentation. 

## The presentation
A slide deck which contains the main points of the exercise, structured to be presented to an external stakeholder, can be found at [census_exercise_presentation.pptx](census_exercise_presentation.pptx).

## The notebook
The main notebook ([dataiku_take_home_exercise.ipynb](dataiku_take_home_exercise.ipynb)) contains the code for all the steps of this exercise. The code is split into sections, as follows: 
- Imports & Setup
- Data Load & Initial Observations
- Initial Data Exploration
- Exploratory Data Analysis
- Data Preprocessing
- Data Modelling
- Model Assessment
- Feature Importance
- Next Steps
- Appendix: Some additional, interactive visualisations

At the start of each section, you can find some commentary and the main takeaways in the form of text and bullet points. My suggestion is to also look at the notebook appendix right at the bottom, as it showcases a couple interesting dynamic graphs using plotly. 

**Note 1:** The only section of the notebook that has been transformed into functions and contains a runner is the preprocessing section. The reason for this is mostly time constraints. With more time, I would split the rest of the code into functions within .py files and unit test them, then build the various pipelines and component tests. The repo would also take a more standard shape, with **src** and **tests** folders which would contain the code and tests respectively.

**Note 2:** The notebook also contains additional graphs and points of analysis that - as happens often in real life - never made it to the final slide deck.
