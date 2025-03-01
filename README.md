🎥 IMDB Movie Review Sentiment Analysis
This project is a web-based application that predicts the sentiment of movie reviews as either positive or negative. Built with Streamlit and TensorFlow, it leverages a pretrained RNN model to classify sentiments based on text inputs.

🚀 Features
Interactive Web App: Enter a movie review and get real-time sentiment predictions.
Pretrained Model: Utilizes a simple RNN model trained on the IMDB dataset.
User-Friendly Interface: Built with Streamlit for an intuitive experience.
Explainable Outputs: Displays prediction scores and sentiment classification.
2024-12-02 (1)
🛠️ Tech Stack
Framework: Streamlit
Machine Learning: TensorFlow (Simple RNN)
Text Processing: Keras Preprocessing, IMDB Word Index
Programming Language: Python
📂 Project Structure
Movie-Review-Sentiment-Analysis/
│
├── main.py                     # Streamlit app script
├── requirements.txt            # Project dependencies
├── model/                      # Pretrained model
│   └── simple_rnn_imdb.h5      # RNN model file
├── utils/                      # Helper functions
│   ├── decode_review.py        # Review decoding function
│   └── preprocess_text.py      # Text preprocessing function
├── assets/                     # Images and other assets
│   └── screenshots/            # App screenshots
├── data/                       # Dataset files
│   └── imdb_word_index.json    # IMDB word index file
└── README.md                   # Project documentation
📋 Setup and Usage
1. Clone the Repository
git clone https://github.com/ayushi-mahariye/Movie-Review-Sentiment-Analysis.git
cd Movie-Review-Sentiment-Analysis
2. Install Dependencies
Ensure you have Python 3.9+ installed. Install the required libraries:

pip install -r requirements.txt
3. Run the Application Locally
Launch the Streamlit app:

streamlit run main.py
4. Interact with the App
Enter a movie review in the text box.
Click on the Classify button to get the sentiment.
🌐 Deployment
You can deploy this Streamlit application on platforms such as Streamlit Community Cloud, Heroku, or AWS.
Deployment Link : 

Deploy on Streamlit Community Cloud
Fork the Repository
Ensure the repository is available on your GitHub account.

Sign in to Streamlit Community Cloud

Go to Streamlit Cloud.
Log in with your GitHub account.
Create a New Deployment

Click on New App.
Select your repository, branch (main), and main.py as the entry point.
Configure Dependencies
Streamlit will automatically detect the requirements.txt file to install dependencies.

Launch the App
Once deployed, you’ll get a public URL for your application, e.g., https://your-app-name.streamlit.app.

💡 How It Works
Preprocessing:

Converts user input into a sequence of integers using the IMDB word index.
Pads the sequence to ensure compatibility with the model.
Prediction:

Uses a pretrained RNN model (simple_rnn_imdb.h5) to classify the sentiment.
Outputs the sentiment as Positive or Negative based on the prediction score.
🌟 Future Enhancements
Replace the RNN model with state-of-the-art transformer models (e.g., BERT).
Support multilingual sentiment analysis.
Deploy the app online using cloud platforms like AWS or Heroku.
Include more advanced visualizations for sentiment trends.
