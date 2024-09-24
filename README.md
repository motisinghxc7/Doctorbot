# Doctorbot
**DoctorBot**
DoctorBot is a chatbot specifically designed to assist users with health-related inquiries. By integrating medical knowledge, symptom databases, and wellness tips into a large language model (LLM), this chatbot provides users with personalized health advice, symptom checks, and recommendations for medical consultations.

**Features**
Interactive chatbot interface for health-related questions.
Symptom checker based on a vast medical database.
General health advice and wellness tips.
Personalized recommendations for seeking medical attention or treatments.
Integration with online health resources and emergency contact suggestions.

**Installation**
To get started with DoctorBot, follow these steps:

**Clone the repository:**
git clone https://github.com/motisinghxc7/doctorbot.git
cd DoctorBot

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the chatbot by typing your health-related questions (e.g., "I have a headache and fever, what should I do?" or "What are the symptoms of diabetes?").

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
