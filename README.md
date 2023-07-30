# The Office Data Analysis - README

## Overview
The "The Office Data Analysis" project explores character interactions, sentiment, and viewer ratings in the popular TV series "The Office." The project leverages Python and Pandas for data cleaning, joining, and transformation, followed by exporting the processed data for use in Tableau to create interactive dashboards. The coding was done using Google Colab.

## Methodology
1. Data Collection:
   - [The Office Dataset](https://www.kaggle.com/datasets/nehaprabhavalkar/the-office-dataset): This dataset contains information about the characters and episodes of The Office.
   - [Dialogue Transcript](https://www.kaggle.com/datasets/nasirkhalid24/the-office-us-complete-dialoguetranscript): The dataset provides complete dialogue transcripts for The Office.
   - [The Office Episodes Data](https://www.kaggle.com/datasets/bcruise/the-office-episodes-data): This dataset includes details about The Office episodes.

2. Data Processing:
   - Python and pandas are used for data cleaning, joining, and transformation. The datasets are combined to gain insights into character interactions, sentiment, and viewer ratings. The notebook for the data processing can be found in the 'notebooks' directory.

3. Sentiment Analysis:
   - Sentiment analysis was performed using TextBlob library to analyze the sentiment of the dialogue. While the analysis provided some insights, the results were not significantly correlated with other factors. It is possible that TextBlob's basic sentiment analysis may not capture the nuances of sentiment in dialogue fully.

4. Visualizations:
   - Chord Diagram: Flourish Studio is employed to create interactive chord diagrams showcasing the relationships between characters and shared scenes (Link: [Chord Diagram Visualization](https://flourish.studio/)).

## Tableau Dashboard
The Tableau dashboard presents an in-depth analysis of The Office TV series. It offers interactive visualizations, including chord diagrams, to explore character interactions and sentiment. You can access the Tableau dashboard through the following link: [The Office Tableau Dashboard](https://public.tableau.com/app/profile/mikolaj.kasprzyk/viz/TheOfficeDataAnalysis_16905887501520/Home).

## Directory Structure
- `data/`: Contains the original datasets in CSV format.
- `notebooks/`: Google Colab notebook for data processing.
- `outputs/`: Exported files generated after data processing.

## Contributions
Contributions to the project are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

