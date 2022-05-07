# earnings-call-audio-modeling
This is a repository for an exploratory project with sentiment analysis of earnings call audio data using transformer models.

# Quick navigation
[Goal](#goal)  
[Background](#background)  
[Current Status](#current-status)  
[Data](#data)  
[Transformer](#transformer)  
[Timeline](#timeline)  
[Future Work](#future-work)  
[Repo Structure](#repo-structure)  
[Contact](#contact-info)

# Goal

Throughout the semester, the goals of this project have shifted. Initially, the plan was to create a predictive model to determine stock price performance based on sentiments gathered from audio data for earnings calls. What has been done so far is sentiment extraction from earnings call audio data and exploratory analysis of said sentiments. Given the findings from exploratory data analysis, modeling may not be very reliable using just these audio data sentiments. There are numerous possibilities of future work to be done to build on the foundation that was developed by this project. These are datailed further throughout the readme and within the code notebooks on the repo.

# Background  

A topic of interest in the finance community has been extracting sentiments from various sources such as earnings calls in order to predict performance of companies. Previous work has been done with NLP to generate sentiments from text data, however transformers now make it possible to generate sentiments from audio data. These sentiments can be used to model performance of stock prices. Application of these state-of-the-art transformer models will work to solve an existing problem in the finance community while also opening the door for future improvement on this project and other new projects. 

# Current Status

Sentiment analysis has been conducted on nearly 200 earnings calls from Q4 of 2021. The resulting sentiment datasets have been explored in detail within the [20-eda.ipynb file](https://github.com/kingla6/earnings-call-sentiment/blob/main/20-eda.ipynb). It was discovered that the large hubert model used to generate sentiments was likely making its predictions based on volume and tone of the speaker rather than any of the content of their spoken words. It is unclear whether or not these audio sentiments alone will be useful for predictive modeling. I am under the assumption that a pairing of textual sentiment analysis with audio sentiment analysis may be more useful in making predictions than audio sentiments alone. More detail regarding my process and findings is provided in each of the code notebooks within the repo. 

# Data

The data contains 193 company earnings calls for Q4 of 2021 that were available in January 2022. All audio files are stored in the [audio-files section](https://github.com/kingla6/earnings-call-sentiment/tree/main/data/audio-files) of the [data folder](https://github.com/kingla6/earnings-call-sentiment/tree/main/data). Within the data folder, a [detailed log of all the audio files](https://github.com/kingla6/earnings-call-sentiment/blob/main/data/data.csv) is contained as well as the [output file for sentiment scores of company earnings calls](https://github.com/kingla6/earnings-call-sentiment/blob/main/data/audio_sentiment.csv).

## Data security

All data used within this course is publicly available from [earningscall.biz](https://earningscall.biz).

# Transformer

The transformer model used for this project was a [large hubert model trained on the superb-er dataset](https://huggingface.co/superb/hubert-large-superb-er), all available on huggingface. 

# Timeline

Work for the project to this point has taken place furing the Vanderbilt 2022 Spring Semester. Work is expected to continue following the conclusion of the semester pendkng promising results or outside interest. 

# Future Work

Future enhancements to the project are listed as issues on the [project board](https://github.com/kingla6/earnings-call-sentiment/projects/1). This board shows what has already been done and what has yet to be completed. 

# Repo Structure

Give a description of how the repository is structured. Example structure description below:

The repo is structured as follows: Notebooks are grouped according to their series (e.g., 10, 20, 30, etc) which reflects the general task to be performed in those notebooks. These code notebooks contain both code, explanations, and detaild writeups of findings. Data used for the project is also made available in the [data folder](https://github.com/kingla6/earnings-call-sentiment/tree/main/data).


# Contact Info

Logan King, M.S. in Data Science Candidate  
Vanderbilt University  
logan.a.king@Vanderbilt.Edu  
