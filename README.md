**ALEXA-THE-VOICE-ASSISTANT**

Asistant that listens for the wake word “Alexa,” recognizes spoken commands, and responds using text-to-speech. It can play YouTube videos, tell the time, answer “who is” questions using Wikipedia, tell jokes, and interact with the user in real time.


**Overview**

This is a lightweight, beginner-friendly voice assistant written in pure Python that mimics basic Amazon Alexa functionality. It continuously listens for the wake word "Alexa", converts speech to text using Google's free API, and responds with offline text-to-speech (pyttsx3, female voice by default).

Key capabilities include:
- Playing any song on YouTube
- Telling the current time
- Reading short Wikipedia summaries
- Telling random jokes
- Giving funny replies to personal questions

The entire assistant is ~100 lines, runs in an infinite loop, works on Windows/macOS/Linux, and requires internet only for speech recognition and online features (speaking works offline). It's a popular educational project perfect for learning voice interfaces and quick prototyping.



### Features of This Voice Assistant Code

- **Wake Word Activation**: Triggers only when “Alexa” is spoken  
- **Play Music**: “Alexa play [song]” → instantly opens and plays on YouTube  
- **Tell Time**: “Alexa, what’s the time?” → speaks current time  
- **Wikipedia Lookup**: “Alexa, who is [person]?” → reads a short summary  
- **Jokes on Demand**: “Alexa, tell me a joke” → shares a random programmer joke  
- **Humorous Responses**: Funny replies to “Are you single?” and “Date?”  
- **Offline Speech Output**: Uses pyttsx3 – works without internet for talking  
- **Continuous Listening**: Runs in an infinite loop, always ready  
- **Cross-Platform**: Works on Windows, macOS, and Linux  
- **Beginner-Friendly**: Clean, simple, well-commented ~100-line code  
- **Easy to Extend**: Add new commands in just a few lines  
A perfect mini-Alexa for learning and fun!


**Tech & Tools Used in This Voice Assistant**

Language: Python
Speech-to-Text: speech_recognition + Google Speech API (online)
Text-to-Speech: pyttsx3 (offline)
YouTube Playback: pywhatkit
Wikipedia Search: wikipedia library
Jokes: pyjokes
Time: datetime (built-in)
Hardware: Microphone + Speakers
Internet Needed: Yes (except TTS)


### Steps to Install and Run This Voice Assistant Project 
 
1. **Install Python** (version 3.7 or higher)   
   Download from: https://www.python.org/downloads/ 
 
2. **Open Command Prompt / Terminal** 
 
3. **Create a project folder** (optional but recommended)   
   ```bash 
   mkdir MyAlexa 
   cd MyAlexa 
   ``` 
 
4. **Install required libraries** (one command):   
   ```bash 
pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes   
pip install pipwin 
pipwin install pyaudio
   ``` 
   - On Windows: `pyaudio` usually installs smoothly.   
   - On macOS:   
     ```bash 
     brew install portaudio 
     pip install pyaudio 
     ``` 
   - On Linux (Ubuntu/Debian):   
     ```bash 
     sudo apt-get install portaudio19-dev 
     pip install pyaudio 
``` 
5. **Save the code** into a file named `alexa.py` (copy-paste the full code 
you have). 
6. **Run the assistant**   
```bash 
python alexa.py 
``` 
7. **How to use**   - Wait for “Listening…”   - Say clearly: “Alexa play Shape of You” / “Alexa what’s the time” / “Alexa 
who is Elon Musk” etc.   - To stop: Press `Ctrl + C` in the terminal. 
Done! Your personal Alexa is now running. 

 

 
### Quick Testing Instructions for Your Alexa Voice Assistant 
After running `python alexa.py`, test it step-by-step like this: 
| # | What to Say (clearly, after “Listening…” appears) | Expected Result | 
|---|----------------------------------------------------|-----------------| 
| 1 | **Alexa, what’s the time?**                        
| She says the current time 
(e.g., “The current time is 10:25 PM”) | 
| 2 | **Alexa, play Despacito**                          
YouTube and starts playing the song | 
| 3 | **Alexa, who is Albert Einstein**                  
Wikipedia summary about Einstein | 
| 4 | **Alexa, who the heck is Taylor Swift**            
phrasing also works) | 
| 5 | **Alexa, tell me a joke**                          
| 6 | **Alexa, are you single?**                         
| Your default browser opens 
| She reads a short 
| Same as above (funny 
| She tells a (usually nerdy) joke | 
| Replies: “I am in a 
relationship with Wi-Fi.” | 
| 7 | **Alexa, do you want to date?** or **Alexa, date?**| Replies: “Sorry, I 
have a headache today.” | 
| 8 | Say something without “Alexa” or random noise     | She stays silent or 
asks to repeat (no false trigger) | 
**Tips for Best Results** - Speak clearly and close to the microphone (~20–30 cm). - Use English (Google STT works best with English). - Test in a quiet room first. - If nothing happens → check your microphone is set as default and not 
muted. 
**To Stop the Program** 
Press **Ctrl + C** in the terminal window. 
That’s it — if all 8 tests work, your Alexa is 100% functional!





 

