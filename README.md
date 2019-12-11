# Project description
[This Website](https://lunahub.github.io/Friends_social_data_analysis_2019/) is the second part of the final project for the DTU course Social graphs and interactions (02805). 

## Idea
The general idea of the project is to investigate the American TV sitcom [F.R.I.E.N.D.S](https://en.wikipedia.org/wiki/Friends) in terms of both network analysis and text analysis. The network analysis will focus on comparing the networks between the characters of the show over the 10 seasons. The analysis will be held against our knowledge about the storyline of the seasons to see if the network analysis can confirm the evolution of the relationship (marriage, disputes, flirts etc.) between the characters. The analysis will also explore who and how many secondary characters are used in each seasons such as Janice Hosenstein or Carol Willick. 

<p align="center"> 
<img src="figures/friends.jpeg" width="500">
</p>

The text analysis will look at the transscript content of the spoken lines in the seasons. The analysis will reveal how the language evolved during the ten year periode the sitcom was made. Sentiment analysis and wordscloud will be used as tools for this. The wordcloud will also be compared to the storyline of the seasons to investigate if the analysis captures the main highlights of the seasons.

It will also look at the issues that are being tackled at the different locations (café, a given apartment, tbeir workplace) to see if the settings can indicate the story's development in general terms.

# Content of Website
This Website includes
* [A Network Analysis of the main characters](https://lunahub.github.io/Friends_social_data_analysis_2019/network_analysis_main_char)
* [A Network Analysis of the secondary characters](https://lunahub.github.io/Friends_social_data_analysis_2019/network_analysis)
* [A Text Analysis](https://lunahub.github.io/Friends_social_data_analysis_2019/text_analysis)

# Data
The data for this project is [transcripts](https://fangj.github.io/friends/?fbclid=IwAR2vf_96q737D1Q-z45fe8obSGk_iWVhCtdKAaz6hP6PA8B0W4udjwcUxAI) of the show F.R.I.E.N.D.S. The transripts of each episode is downloaded as .CSV files from [here](https://github.com/shilpibhattacharyya/Friends_Analysis/tree/master/transcripts_friends). Before the analysis the data files are preprocessed to one dataframe including all the episodes. The file is 10.1 MB big and contains 61264 lines, with 907 unique speakers, 2878 unique scenes, 10 seasons and 227 episodes in total. The datafiles used in the analysis can be downloaded from the [repository](https://github.com/LunaHub/Friends_social_data_analysis_2019/tree/master/data)

# Explainer notebook
Furthermore all notebooks used for the analysis can be downloaded from the [repository](https://github.com/LunaHub/Friends_social_data_analysis_2019/tree/master/Jupyter_notebook) and an explainer notebook can be found [here.](https://nbviewer.jupyter.org/github/LunaHub/Friends_social_data_analysis_2019/blob/master/Jupyter_notebook/Explainer_notebook.ipynb)
