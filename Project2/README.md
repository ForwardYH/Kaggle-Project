# Sentiment Analysis on Movie Reviews
  * https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews

- 프로젝트 기간 : 2017-05-03 ~ 2017-06-26

"There's a thin line between likably old-fashioned and fuddy-duddy, and The Count of Monte Cristo ... never quite settles on either side."

The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis, originally collected by Pang and Lee [1]. In their work on sentiment treebanks, Socher et al. [2] used Amazon's Mechanical Turk to create fine-grained labels for all parsed phrases in the corpus. This competition presents a chance to benchmark your sentiment-analysis ideas on the Rotten Tomatoes dataset. You are asked to label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive. Obstacles like sentence negation, sarcasm, terseness, language ambiguity, and many others make this task very challenging.

---

# Prerequisite
  * Python 2.7
  * Graphlab Package(https://turi.com/)
  * Jupyter Notebook
  
# Project Flow

* Data Exploration -> Data Preprocessing & Modeling(2) -> Make Corpus(2-1) -> Corpus Adaptation & Modeling(2-2) -> Final Test

# File Description

- Data Exploration & Textmining - Sentiment Analysis.ipynb : 영화 리뷰에 대한 데이터 탐색 및 텍스트 마이닝
- Preprocessing & Modeling - Sentiment Analysis.ipynb : 데이터 전처리
- Make Corpus.ipynb : Harvard corpus 이용하여 corpus 구축
- Corpus Adaptation & Modeling : 기존 데이터에 corpus 추가하여 모델링
- Final Test - Sentiment Analysis.ipynb : Kaggle Submission
