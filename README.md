#### **Luna: an AI-Powered Virtual Assistant**  
A Python-based virtual assistant that responds to voice commands for opening applications/websites, checking calendar events, and taking notes. Luna integrates Google Calendar API for scheduling and utilizes speech recognition for hands-free interaction.  

#### **Features:**  
✅ **Voice Commands** – Perform tasks like opening apps, visiting websites, and creating notes.  
✅ **Google Calendar Integration** – Fetch upcoming events and reminders.  
✅ **Text-to-Speech (TTS)** – Reads out responses for a hands-free experience.  
✅ **Cross-Platform Support** – Works on both macOS and Windows.  

#### **Tech Stack:**  
- **Python** (Core logic)  
- **Google Calendar API** (Event retrieval)  
- **SpeechRecognition** (Voice input)  
- **Pyttsx3** (Text-to-speech)  
- **Webbrowser & Subprocess** (Opening websites and applications)  

📌 **Future Improvements:**  
- Making a visual interface using flask for better communication with the user.     

### **Installation & Usage:**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Luna-Voice-Assistant.git
   cd Luna-Voice-Assistant
   ```  
2. Install dependencies:  
   ```bash
   pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
   pip install SpeechRecognition pyttsx3 pytz
   ```  
3. Run the assistant:  
   ```bash
   python main.py
   ```  
