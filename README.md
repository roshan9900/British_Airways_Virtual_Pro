# Customer Buying Behaviour Prediction

**Introduction**:
In this project, I embarked on a journey to extract meaningful insights from a collection of 2090 customer reviews using a combination of web scraping, data preprocessing, machine learning techniques, and data visualization.

### Features That Affect The Buying Price 
<div>
    <img width="441" alt="Screenshot 2023-08-17 191027" src="https://github.com/roshan9900/British_Airways_Virtual_Pro/assets/115538447/6f213b58-3eb2-4581-a648-f71c427b5ba1" alt="feature importance" width="300" />
    </div>


**Step 1: Data Collection**
I started by employing Beautiful Soup to scrape customer reviews. This raw data formed the foundation for our analysis.

**Step 2: Data Preprocessing**
To ensure clean and consistent data, I executed thorough data preprocessing. This included eliminating converting text to lowercase and tokenizing the text into meaningful units.

**Step 3: Text Encoding**
In order to work with the textual data effectively, I utilized the TF-IDF technique to encode the tokenized text. This transformation allowed me to numerically represent the text, making it compatible with machine learning algorithms.

**Step 4: Topic Modeling**
Topic modeling, an essential step, helped uncover hidden themes within the reviews. I employed Latent Dirichlet Allocation (LDA) to identify key topics and their prevalence across the reviews.

**Step 5: Text Classification**
To categorize reviews and gauge sentiment, I chose the Random Forest algorithm for its robustness. After training the model on labeled data, I achieved an impressive 92% accuracy in classifying reviews. This meant that the model could accurately identify sentiments or categories associated with each review.

**Step 6: Named Entity Recognition (NER)**
Implementing Named Entity Recognition enriched our analysis by pinpointing significant entities like names, locations, and dates within the reviews. This provided valuable context to the overall sentiment and topics discussed.

**Step 7: Power BI Dashboard**
In order to present these findings in a comprehensible manner, I constructed an interactive Power BI dashboard. This dashboard featured dynamic visualizations, such as bar charts, line chart and pie charts.

Conclusion:
This project exemplified the power of data-driven decision-making. Through the strategic use of web scraping, preprocessing, machine learning, and visualization techniques, I was able to extract meaningful insights from customer reviews, providing the company with a clear roadmap for enhancing its services and aligning them with customer preferences. The journey from raw text to actionable insights demonstrated the potential of data analysis in driving impactful business transformations.


### Count Of Reviews Per Hour
<div align="left">
    <img width="429" alt="image" src="https://github.com/roshan9900/British_Airways_Virtual_Pro/assets/115538447/57430662-44c4-45a1-9bcb-af21eb2a472a" alt="Image " width="300" />
    </div>

### Count Of Reviews Per Country
<div align="left">
    <img width="429" alt="image" src="https://github.com/roshan9900/British_Airways_Virtual_Pro/assets/115538447/45fe5309-a244-4da0-942a-65c27504b796" alt="Image " width="300" />
    </div>



