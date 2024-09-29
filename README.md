# repair-ai
RepairAI is a tech-enabled repair platform that leverages multimodal generative AI to provide real-time, expert repair guidance.

# Features
Multimodal Analysis: Automatically identifies and categorizes skin conditions based on uploaded images or videos.

Feature Extraction: Extracts features and patterns from dermatological images for detailed analysis.

Diagnostic Support Decision Support System: Provides diagnostic recommendations and differential diagnoses based on input images.

Second Opinion Tool: Offers a second opinion by comparing input images with a database of similar cases.

Integration API Integration: Allows seamless integration with existing healthcare systems or research platforms via API

Web Interface: User-friendly web interface for easy access and interaction.

# How It Works
Text Messaging: Users can directly chat with an AI doctor through text messaging.

Upload: Users can upload images or videos of their skin condition via the platform.

AI Analysis: The Gemini API processes the uploaded media to diagnose the condition.

Diagnosis & Recommendations: Users receive a detailed diagnosis and personalized treatment recommendations.

Consultation Option: If further consultation is needed, users can easily connect with a healthcare professional.

# Getting Started
To start using the platform, follow these steps:

# Cloning the repository
git clone https://github.com/Zhongheng-Cheng/SkinScan
cd SkinScan

# [Optional] Creating virtual environment
python -m venv venv
source venv/bin/activate

# Download dependencies
pip install -r requirements.txt

# Setup Gemini API key
touch .env
# Enter your Google Gemini API Key in ".env" like this:
# GOOGLE_API_KEY="..."

# Run the project
python app.py
