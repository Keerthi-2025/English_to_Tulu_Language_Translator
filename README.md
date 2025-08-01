🗣️ English to Tulu Language Translator

Project URL: https://eng2tulu.streamlit.app/

Tulu is a regional language spoken primarily in parts of Karnataka and Kerala, India. Unfortunately, it remains underrepresented in most language technology platforms. This project aims to bridge that gap by developing a translator that supports English to Tulu translation, promoting both communication and the preservation of the Tulu language.

🔍 Project Overview

🔸 A machine learning-based translator was developed using a K-Nearest Neighbors (KNN) classifier along with TfidfVectorizer.

🔸 The model takes English text input and returns Tulu translations for words and phrases available in the dataset.

🔸 The dataset was carefully curated and cleaned from aligned English-Tulu text files to ensure accurate translations.

🔸 Special care was taken in preprocessing and alignment checking to avoid mismatches between source and target texts.

💻 Features

🔹 Developed using Streamlit to provide a clean, user-friendly web interface.

🔹 Hosted on Streamlit Cloud: https://eng2tulu.streamlit.app/

🔹 Users can input English words/phrases, and the app returns corresponding Tulu translations (if available in the dataset).

🔹 Translations are limited to the vocabulary present in the training dataset, and the model does not currently support out-of-dataset phrases.

🌐 Tech Stack

⚙️ Python

⚙️ Scikit-learn (KNN Classifier)

⚙️ TfidfVectorizer

⚙️ Streamlit

⚙️ Custom-aligned English-Tulu Dataset

🎯 Goals

✅ Preserve and promote the Tulu language through technology.

✅ Demonstrate the potential of machine learning in regional language translation.

✅ Encourage future expansion to include support for Kannada, Hindi, and other local languages.
