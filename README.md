# gemini-pro-streamlit-chatbot
 Can Google Gemini power intelligent conversational AI? This project demonstrates the power of Google's latest Gemini model through a real-time AI Chatbot built with Streamlit, featuring conversation memory and dynamic response generation using cutting-edge Large Language Model technology. Live Demo: https://deploy-llm-chatbot-app-gemini.streamlit.app/ 🤖✨

🔍 Project Overview:

LLM-Powered Conversations: Leverages Google Gemini 2.0 Flash for natural, context-aware dialogue with full chat history retention
<br>
Real-time Streaming: Instant responses with typing animation for smooth user experience
<br>
Session Persistence: Maintains conversation context across multiple interactions
<br>
Responsive Interface: Clean, mobile-friendly Streamlit UI optimized for all devices
<br>
Production Deployed: Live at https://deploy-llm-chatbot-app-gemini.streamlit.app/
<br>
Error-Resilient: Graceful handling of API quotas and network conditions

🎯 Learning Outcomes:

Integrating Google's Gemini API with Python web frameworks
<br>
Building stateful conversational AI with session management
<br>
Creating responsive web UIs using Streamlit
<br>
Deploying LLM-powered applications to Streamlit Cloud
<br>
Handling real-time API quotas and error states

⚙️ Technologies & Tools:
Python | Google Gemini API | Streamlit | google-generativeai | python-dotenv

Local Setup:
streamlit run main.py
Opens: http://localhost:8501

If dependencies missing:
pip install streamlit google-generativeai python-dotenv pillow
Add your Gemini API key to .env:
GOOGLE_API_KEY=your_api_key_here
