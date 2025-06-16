
# Disaster Tweet Analyzer: Natural Language Processing for Crisis Communication 

## 📌 Project Description

The **Disaster Tweet Analyzer** is a machine learning application designed to classify tweets as either disaster-related or not. It leverages **Natural Language Processing (NLP)** techniques to analyze the content of tweets and extract meaningful insights such as:

- Whether the tweet is reporting a real disaster,
- The type of disaster (e.g., earthquake, flood, wildfire),
- The location mentioned in the tweet,
- And the sentiment conveyed (positive, negative, or neutral).

This tool is especially useful for:

- **Emergency responders**, who can use it to identify and prioritize urgent disaster-related information,
- **Government agencies** and **NGOs**, seeking real-time alerts and geographic targeting for disaster relief efforts,
- **Researchers** and **data scientists**, interested in studying how social media reflects crisis events,
- **Journalists**, looking to track real-time developments and public sentiment during emergencies.



## 🎯 Project Motivation

This project was developed as part of my internship under the **Infosys Springboard AI Internship Program**. 

The goal was to explore real-world applications of Machine Learning and Natural Language Processing (NLP) by building an end-to-end system that can analyze social media data for disaster-related information. 

Throughout the internship, I worked on:
- Data preprocessing and cleaning
- Feature engineering and vectorization
- Model training and evaluation
- Web application development using Flask
- Deployment of ML models for real-time prediction
- Sentiment Analysis, Named Entity Recognition (NER), and disaster category prediction

## 📚 Learning Outcomes

- Gained hands-on experience with supervised machine learning models like Logistic Regression, Random Forest, and BERT.
- Understood the practical implementation of NLP techniques such as text vectorization, named entity recognition, and sentiment analysis.
- Learned to build full-stack ML web applications using Flask.
- Improved my skills in data preprocessing, feature engineering, and model deployment.
- Developed end-to-end project development and documentation skills.


## Documentation

[Documentation](https://vitbhopalacin-my.sharepoint.com/:w:/g/personal/ashutoshkumaryadav2022_vitbhopal_ac_in/EQc-FVKrwIdGlMnAt8JVB50BVP7K9xu39HqL86zTXwZc4Q?e=bay0WH)


## 🛠️ Technologies Used

- **Python** — Core language for backend and model development
- **Flask** — Lightweight web framework used to build the web app interface
- **HTML5/CSS3/JavaScript** — Frontend design and interaction
- **scikit-learn** — Machine Learning models: Logistic Regression, Random Forest, Vectorization, Scaling
- **spaCy** — Named Entity Recognition (NER) for location extraction
- **NLTK** — Sentiment Analysis using VADER sentiment analyzer
- **pandas, numpy** — Data manipulation and preprocessing
- **pickle / joblib** — Model serialization for deployment
- **Chatbase (optional extension)** — Integrated chatbot support for user interaction
- **Infosys Springboard Platform** — Project supervision and training guidance

## ⚙️ Installation

> Before running the project, ensure you have **Python 3.8+** installed.

1. **Clone the repository:**


git clone https://github.com/AshutoshKY125/Infosys-Springboard-Disaster-Tweet-Analyzer.git
cd Infosys-Springboard-Disaster-Tweet-Analyzer

2. **Create a virtual environment (optional but recommended):**

`python -m venv venv`

`source venv/bin/activate`

On Windows: 
`venv\Scripts\activate`

3. **Install dependencies:**

`pip install -r requirements.txt`

4. **Download the spaCy language model:**
`python -m spacy download en_core_web_sm
`

## 🚀 How to Use

1. **Start the Flask server:**
`python app1.py`

2. **Open your browser and navigate to:**
`http://127.0.0.1:5000/`

3. **Usage Flow:**
* Enter a tweet in the input box.

- The model will analyze the tweet and provide:

    - Whether it's disaster-related or not.

    - Location extracted from the tweet.

    - Predicted disaster category.

     - Sentiment (Positive, Negative, Neutral).

4. **Optional Chatbot:**
The web UI includes an embedded **TARINI chatbot** to answer disaster-related questions based on `train.txt`

✅ NOTE:
The model files (`lr_model.pkl`, `vectorizer.pkl`, `scaler.pkl`, `rf_pipeline_model_bert_only.joblib`) must be placed in the same directory as `app1.py`.



    
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## 🔗 Live Demo

You can try the live hosted version here:  
👉 [Disaster Tweet Analyzer - Live](https://disaster-tweet-analyzer.onrender.com/)


## 🙏 Acknowledgements

I would like to express my sincere gratitude to:

- **Infosys Springboard** for providing this learning opportunity.
- My mentor **Mr. Nitig Singh** sir and guides for their constant support and valuable feedback.
- My fellow team members who contributed to the development and discussions.


