🛠️ Tools Required
Python 3.8 or above
VS Code (or any editor)
A microphone
Internet connection for YouTube/Wikipedia
Step 1: Create Project Folder
Open VS Code → Create a new folder:

mkdir voice-desktop-assistant
cd voice-desktop-assistant

🧪 Step 2: Set Up a Virtual Environment
Run this to create a virtual environment:

python -m venv venv
Activate it:

Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
You’ll see (venv) in your terminal – that means you’re good to go!

Step 3: Install Required Libraries
Run this to install all dependencies:

pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes


->Libraries Explained

speech_recognition	    Converts voice to text
pyttsx3	                Converts text to speech (works offline)
pywhatkit	              Used to play YouTube videos via voice
wikipedia	              Fetches summary of people or topics
pyjokes	                Tells random programming jokes
os / sys	              To open apps or exit the assistant

Step 4: Create the Assistant Script
->copy SHiGO.py 
How to Run the Project
After you activate the venv, run:

python assistant.py
Then say:

"play nani songs"
"what's the time"
"open chrome"
"who is Elon Musk"

And SHiGO will respond like a pro! 🤖

Final Words
That’s it – your own voice assistant like Siri/alexa is ready! 
