# BI practice using different instruments and datasets

Practice working with datasets and creating dashboards using different tools such as Google Sheets, PowerBI and Looker.
I would like to show the skills of interaction and segmentation of several datasets, but I could not find suitable datasets for a correct illustration.

## Сontent and navigation

1. [Overall information](#overall-information)
2. [Spotify musica project](#-spotify-music)  
    - 2.1. [Spotify dataset](#-spotify-data)
    - 2.2. [Spotify analysis](#-spotify-analysis)
    - 2.3. [Spotify dashboard](#-spotify-dashboard)
3. [Job market project](#-job-market)
    - 3.1. [Job market dataset](#-job-market-data)
    - 3.2. [Job market analysis](#-job-market-analysis)
    - 3.3. [Job market dashboard](#-job-market-dashboard)
4. [Letterbox Movie ratings](#-letterbox-movie-ratings)
    - 4.1. [Letterbox dataset](#-movie-ratings-data)
    - 4.2. [Letterbox analysis](#-movie-ratings-analysis)
    - 4.3. [Letterbox dashboard](#-movie-ratings-dashboard)

---

## Overall information

#### Repository

To clone a repository, you can use the command:

```bash
git clone https://github.com/Impirs/Practice_BI
```

To view the cleaned data and dashboards, it is not necessary to clone the repository, you can view the results of the work using the links stored in this ReadMe file, as well as in the last request of each notebook, since it creates google sheets with cleaned data.

#### Datasets

All the necessary datasets are also saved in the corresponding folders of each project, in order to run them locally, you need to replace the data import section in the corresponding notebook with the following script:

```python
df = pd.read_csv('../datasets/ai_job_dataset.csv')
df.head()
```

You just need to change the name of the required file with the dataset.

---

## 🎧 Spotify music

> A project for analyzing spotify most popular music dataset using Python (in Colab), and Google Sheets for visualization.

### 📂 Spotify data

Source: [Kaggle - Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)
Cleaned data: [Spotify Songs 2023 data in Google Sheets](https://docs.google.com/spreadsheets/d/1OjOW38H_CAGgtLh3JRtRV2ExGYNa3v2AAvqTGTlxT-k/edit?usp=sharing)

### 📓 Spotify analysis

See [spotify_2023.ipynb](movie/notebook/spotify_2023.ipynb)

### 📊 Spotify dashboard

![image]()

<a href="#сontent-and-navigation" style="
  display: inline-block;
  padding: 6px 12px;
  background-color: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 4px;
">⬆ Go back to content summary</a>

---

## 💼 Job market

> A project for analyzing job market dataset using Python (in Colab), and PowerBI for visualization.

### 📂 Job market data

Source: [Kaggle - Global AI Job Market & Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
Cleaned data: [Global AI Job Market data in Google Sheets](https://docs.google.com/spreadsheets/d/1p17tgmPgQ7-iRgH0DqSZ-_zfiNU5vhKF9RDJttRzQFM/edit?usp=sharing)

### 📓 Job market analysis

Since the dashboard for this dataset will be processed in PowerBI, which I am slightly more familiar with than Looker, no additional analysis will be performed during data cleaning.

See [job_market.ipynb](movie/notebook/job_market.ipynb)

### 📊 Job market dashboard

Dashboard made with PowerBI, with support for bookmarks for navigation and slices (filters, sliders, drop-down lists)

![image](https://github.com/user-attachments/assets/180d93da-9e59-4c11-8efb-1e69d95a8c2c)

![image](https://github.com/user-attachments/assets/e7a92ecd-20b9-4ec4-b680-347305297e3c)

<a href="#сontent-and-navigation" style="
  display: inline-block;
  padding: 6px 12px;
  background-color: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 4px;
">⬆ Go back to content summary</a>

---

## 🎬 Letterbox Movie Ratings

> A project for analyzing movie data from Letterboxd. I use Python (in Colab), and Looker Studio for visualization.

### 📂 Movie Ratings data

Source: [Kaggle - Letterboxd Movie Classification Dataset](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset)
Cleaned data: [Letterbox movies data in Google Sheets](https://docs.google.com/spreadsheets/d/12qFLPA4N1vyGyqN7afeJnCHGJBjJfhmi0lCfqmmXemM/edit?usp=sharing)

### 📓 Movie Ratings analysis

The main analysis is done in Google Colab:

- Data import and cleaning
- Grouping by genres, years, and ratings
- Visualization using Pandas and Seaborn

See [movie_analysis.ipynb](movie/notebook/movie_analysis.ipynb)

### 📊 Movie Ratings dashboard

Looker Studio: interactive dashboard with filters  

![image](https://github.com/user-attachments/assets/5e276fcd-c190-48ad-b74b-3a87e3fc32c4)

<a href="#сontent-and-navigation" style="
  display: inline-block;
  padding: 6px 12px;
  background-color: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 4px;
">⬆ Go back to content summary</a>
