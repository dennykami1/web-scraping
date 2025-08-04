# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Key Tasks
- Web Scraping: Extracts HTML from Wayback Machine and saves to pickle file
- Text Processing: Uses BeautifulSoup to extract clean text from HTML
- Token Analysis: Identifies 5 most frequent tokens using spaCy (excluding stopwords/punctuation)
- Lemma Analysis: Finds 5 most frequent lemmas with same filtering
- Scoring Functions: Creates sentence scoring methods based on token/lemma frequency ratios 6-7. Statistical Visualization: Generates histograms of sentence scores
- Theoretical Analysis: Discusses filtering for nouns only

## Technologies
- requests/BeautifulSoup: Web scraping and HTML parsing
- spaCy: NLP processing and tokenization
- matplotlib: Data visualization
- Counter: Frequency analysis
- The notebook demonstrates a complete pipeline from web scraping to text analysis and visualization.

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

# **How to run the project yourself:**

**Cloned and Opened my Github project**
```
cd \Projects
git clone https://github.com/dennykami1/web-scraping
cd web-scraping
code .
```

**Commited Changes to Github**
```
git add .
git commit -m "Add message"
git push -u origin main
```

**Created Virtual Environment and Activated**
```
py -m venv .venv
.venv\Scripts\activate
```

**Upgrade pip & install requirements.txt**
```
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

**Update Kernel in Jupyter Notebook**
**Export to html using the Jupyter menu**