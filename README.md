# NovaCore AI

**Empowered by NovaCore**

NovaCore AI is a futuristic, secure, and interactive voice assistant designed for personalized user experiences, advanced security, and entertainment. It combines state-of-the-art AI technologies to deliver powerful and secure assistance.

---

## Features

### Core Functionalities
- **Voice Recognition**: Converts spoken commands into text for processing.
- **Natural Language Understanding (NLU)**: Generates human-like conversational responses using advanced AI models.
- **Text-to-Speech (TTS)**: Provides natural and expressive audio responses.
- **Offline Mode**: Offers basic tools such as note-taking, calculations, and reminders even without an internet connection.
- **Graphical User Interface (GUI)**:
  - Displays conversation history.
  - Includes a voice activity indicator.
  - Branded with the tagline: *"Empowered by NovaCore."*

### Advanced Features
- **Custom Wake Word**: Activates with "Hey NovaCore."
- **Owner-Specific Control**:
  - Voice Lock: Ensures only the owner's voice can issue commands.
  - Intruder Response: Delivers aggressive or sarcastic replies to unauthorized users.
- **Emotion Recognition**:
  - Detects emotions from voice tone and webcam facial expressions.
  - Adjusts responses dynamically based on detected mood.
- **Entertainment Module**:
  - Generates jokes, motivational quotes, and shayari for fun and inspiration.
  - Personalized greetings based on the user's name and mood.
- **API Integration**:
  - Real-time updates for weather, news, and motivational quotes.
  - Example: Fetches shayari or jokes from external APIs.
- **Modular Extensions**:
  - Easily integrate new features like smart home controls or advanced scheduling.

### Security Features
- **Voice Authorization**:
  - Wake word and Voice Lock ensure commands come only from authorized users.
  - Uses **SHA-256 encryption** to securely store voice profiles.
- **Multi-Layer Security**:
  - **SHA-256 Encryption**: Hashes sensitive data for secure storage.
  - **AES-256 Encryption**: Encrypts stored commands and logs.
  - **JWT Authentication**: Protects API access with JSON Web Tokens.
- **Facial Recognition**:
  - Authenticates users via webcam using facial features.
  - Asks for voice confirmation if facial recognition fails.
- **Event Logging**:
  - Tracks all actions, errors, and unauthorized attempts with timestamps.
  - Logs are stored securely for later review.

---

## Project Structure

```plaintext
NovaCore-AI/
├── src/
│   ├── gui.py                # Handles GUI interactions
│   ├── voice_recognition.py  # Processes voice commands
│   ├── tts.py                # Text-to-Speech engine
│   ├── nlu.py                # Natural Language Understanding
│   ├── emotion_detector.py   # Detects emotions from voice and camera
│   ├── offline_tools.py      # Tools for offline calculations, notes, and reminders
│   ├── intruder_responder.py # Handles responses to unauthorized users
│   ├── entertainment.py      # Jokes, motivational quotes, and shayari generator
│   ├── security_manager.py   # Manages encryption and security features
│   ├── logger.py             # Logs all events and errors
│   ├── setup.py              # Initializes the environment
│   ├── data_handler.py       # Manages data storage and retrieval
│   ├── authentication.py     # Manages user authentication
│   └── utils/
│       ├── api.py            # API integrations
│       ├── config.py         # Configuration settings
│       ├── camera_utils.py   # Webcam integration for emotion detection
│       └── owner_profile.py  # Stores and validates owner details
├── assets/                   # Images, animations, and sounds
├── logs/                     # Logs folder for events and errors
├── data/                     # Local data storage
├── README.md                 # Documentation and setup instructions
├── requirements.txt          # Dependency list
└── main.py                   # Entry point for the assistant


---

Setup Instructions

Prerequisites

Python 3.8 or above

Install required dependencies listed in requirements.txt


Installation

1. Clone the repository:

git clone https://github.com/your-username/NovaCore-AI.git
cd NovaCore-AI


2. Install dependencies:

pip install -r requirements.txt


3. Run the assistant:

python main.py




---

Usage

1. Activate the assistant by saying "Hey NovaCore."


2. Use voice commands for various features such as:

Setting reminders.

Taking notes.

Asking for jokes, motivational quotes, or weather updates.



3. NovaCore will log all actions and alert unauthorized access attempts.




---

Technologies Used

Speech Recognition: Converts voice commands into text.

Text-to-Speech (TTS): Outputs audio responses.

Facial Recognition: Identifies the user via webcam.

Encryption: SHA-256 and AES-256 ensure secure data handling.

API Integration: Fetches real-time information for weather, news, etc.



---

Customization

Modify settings in src/utils/config.py.

Add new APIs or features in the src/utils/api.py module.

Enable/disable aggressive intruder replies in the settings.



---

License

This project is licensed under the MIT License. See LICENSE for more details.


---

Created by Anonymous NJR 🇵🇸

I'll add the code later I've just created 
