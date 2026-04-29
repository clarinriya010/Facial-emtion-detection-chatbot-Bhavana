😊 Facial Emotion Detection Chatbot – Bhavana
📌 Overview

Bhavana is an emotion-aware AI chatbot that detects a user’s facial expressions in real time and generates context-aware responses. By combining computer vision and natural language processing, the system creates more personalized and empathetic interactions compared to traditional chatbots.

🚀 Features
🎭 Real-time facial emotion detection using webcam
🤖 AI chatbot with emotion-based responses
💬 Dynamic and personalized conversations
🧠 Emotion classification (Happy, Sad, Angry, Surprise, Neutral, etc.)
📊 Chat history storage for interaction tracking
🧠 How It Works
Captures live video input from the user
Detects face using OpenCV
Processes facial features and predicts emotion using a trained model
Sends detected emotion to chatbot logic
Generates a context-aware response
📸 Application Preview

Replace this image with your actual project screenshot (UI or webcam + chatbot output)

🏗️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Flask
Database: MongoDB
AI/ML: OpenCV, Deep Learning
NLP: GenAI / Rule-based chatbot
📂 Project Structure
Facial-emtion-detection-chatbot-Bhavana/
│── static/              # CSS, JS, images
│── templates/           # HTML files
│── model/               # Trained emotion detection model
│── app.py               # Main Flask application
│── utils/               # Helper functions
│── requirements.txt     # Dependencies
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/clarinriya010/Facial-emtion-detection-chatbot-Bhavana.git
cd Facial-emtion-detection-chatbot-Bhavana
2. Install dependencies
pip install -r requirements.txt
3. Run the application
python app.py
4. Open in browser
http://127.0.0.1:5000/
📊 Results
Real-time emotion detection with reliable performance
Improved user interaction using emotion-aware responses
Seamless integration of computer vision and chatbot system
⚠️ Limitations
Sensitive to lighting and camera quality
Emotion detection may vary across users
Limited conversational depth depending on chatbot logic
🔮 Future Improvements
Integrate advanced LLMs (GPT / LangChain)
Improve accuracy with larger datasets (FER-2013, AffectNet)
Add voice-based emotion detection
Deploy as a scalable web application
Enhance personalization using user history

⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
