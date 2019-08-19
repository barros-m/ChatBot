## README.md

Following these tutorials:
https://medium.com/@sundarstyles89/create-your-own-google-assistant-voice-based-assistant-using-python-94b577d724f9
https://www.codementor.io/edwardzionsaji/simple-voice-enabled-chat-bot-in-python-kt2qi5oke

You need to create a Google Cloud Account (free for 1 year), and use the Speech-To-Text API (50 queries per day)

# Set up:

export GOOGLE_APPLICATION_CREDENTIALS="..." <- DOES NOT WORK FOR WINDOWS
Instead, use SET
SET GOOGLE_APPLICATION_CREDENTIALS="..." <- FOR WINDOWS (WINDOWS POWER SHELL)


Modules to be installed (using pip install OR anaconda Navigator):

- speechrecognition
- pyaudio
- pyttsx3
- wikipedia

# VERY IMPORTANT:
- Sometimes it is hard to get what is the input (voice) because of external noise.
  In order to fix this, change the Microphone Sensitivity.
