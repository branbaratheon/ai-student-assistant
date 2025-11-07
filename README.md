# Vulnerable AI Student Assistant
A vulnerable AI app for testing purposes.

## Getting Started

Follow these instructions to get the application running on your local machine.

### Prerequisites

* Python 3.7+
* An active Gemini API key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/vulnerable-ai-student-assistant.git
   cd vulnerable-ai-student-assistant
   ```

2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a `.env` file:**
   Create a file named `.env` in the root of the project and add your Gemini API key:
   ```
   GEMINI_API_KEY="YOUR_API_KEY_HERE"
   ```

4. **Run the application:**
   ```bash
   uvicorn main:app --host 0.0.0.0 --port 8000 --reload
   ```

5. **Open the application in your browser:**
   Navigate to `http://localhost:8000` to use the Student Assistant chatbot.

## Securing the App
Check out https://github.com/mikebiox/secure-student-assistant to see implemented mitigations.
