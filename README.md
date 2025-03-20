Multilingual Sentiment Analysis with Llama 3.1 and Gradio
Overview
This project presents a real-time multilingual sentiment analysis system that integrates the Llama 3.1 model with Gradio for an interactive and user-friendly interface. The system is fine-tuned on the Multilingual Sentiments Dataset from Hugging Face to improve sentiment classification for both high-resource and low-resource languages.

Features
Fine-tuned Llama 3.1 model for multilingual sentiment analysis
Gradio-powered interactive interface for real-time user interaction
Support for multiple languages, including low-resource ones
Real-world applications: customer service, social media monitoring, and e-commerce
Dataset
The Multilingual Sentiments Dataset from Hugging Face is used for training, containing sentiment-labeled text across multiple languages.

Installation
Clone this repository:
sh
Copy
Edit
git clone https://github.com/your-username/multilingual-sentiment-analysis.git
cd multilingual-sentiment-analysis
Install dependencies:
sh
Copy
Edit
pip install -r requirements.txt
Usage
Run the application with:

sh
Copy
Edit
python app.py
Once started, the Gradio interface will launch in a web browser, allowing you to enter text in various languages and receive sentiment predictions in real time.

Results
High accuracy (>90%) for high-resource languages (English, Spanish, French)
Improved performance for low-resource languages
User-friendly real-time interface with instant sentiment classification
Future Improvements
Enhance handling of code-mixed texts
Improve sarcasm and emotion detection
Expand the dataset to more languages
Contributors
Akhtar Ali, Chandigarh University
Kuldip Katiyar, Chandigarh University
License
This project is licensed under the MIT License.
