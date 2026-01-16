# ?? Customer Journey AI Intelligence System

A comprehensive end-to-end system designed to analyze, predict, and visualize customer behavior paths using Machine Learning (Decision Trees).

## ?? Key Features
- **Geographic Analysis:** Identification of top-performing sales activities categorized by country.
- **AI-Powered Prediction:** Real-time prediction of the "Next Best Action" for any given customer state.
- **Strategic Roadmap Generation:** Automated generation of the most probable path to a "Won" deal, avoiding repetitive or redundant actions.
- **Advanced Visualization:** Interactive and visual roadmaps showing the sequence of sales activities.

## ??? Tech Stack
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (Decision Tree Classifier)
- **Visualization:** Matplotlib, Seaborn
- **Serialization:** Pickle, JSON

## ?? Repository Contents
- `Customer_Journey_Analysis.ipynb`: The main Google Colab notebook containing the full pipeline (Cleaning, Training, and System Class).
- `data_cleaned.csv`: Pre-processed and cleaned dataset ready for modeling.
- `top_paths_by_country.json`: Historical success paths analyzed by geographic region.
- `decision_tree_system.pkl`: The serialized trained model and encoders, ready for production deployment.

## ?? How it Works
The system uses a **Hybrid Approach**:
1. **Historical Logic:** It looks at what worked in the past for specific countries and solutions.
2. **Predictive Logic:** A Decision Tree model evaluates the current status (activity count, days since start, current activity) to suggest the most logical next step to maximize the "Win Rate".

## ?? Impact
This tool empowers sales teams to move away from guesswork, providing them with a data-backed blueprint for every customer interaction.
