# Daily habits & GPA tracker
## Goal
The purpose of this project is to explore how daily habits( sleep, eating quality, exercises, mood, stress, menstrual cycle) may influence **academic performance (GPA)**
## Why
I always see posts on social media saying that sleep, eating habits, exercise, mood, stress, or even menstrual cycle all affect how well we can study and succeed in school. But I wondered, is that actually true for me?
So, for this project, i decided to track my daily habits for a full semester and to see if they affect my GPA.
The goal is to see whether these lifestyle factors really connect to my academic performance. This is both a personal self-improvement experiment and a data analysis project, also:
- Do better sleep patterns predict better focus?
- Does exercises improve mood and reduce stress during exam weeks?
- Are eating habits connected to academic productivity?

## How it works
- **Daily logging** in Google Sheets ( sleep, eating, exercise, mood, stress, menstrual cycle)
- **Weekly export** as CVS
- **Python analysis** ('src/analyze_tracker.py') :
  - Weekly summaries of habits
  - Correlations between habits and well-being
  - Scatter plots with trendlines
- **End of semester** : GPA data is added, and regression analysis tests the relationship between habits and GPA

## Repo Structure 
- 'src/' - analysis scripts
- 'data/' - aggregated weekly outputs ( no raw personal data)
- 'charts/' - generated plots
- 'README.md' - overview of the project
- 'METHODS.md' - details on variables and analysis

## Privacy
Raw daily logs stay private. Only anonymized oor aggregated summaries are shared

