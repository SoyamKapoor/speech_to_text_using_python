# Speech to Text

Welcome to the **Speech to Text** project! This project is built using **Python** and the **SpeechRecognition** library to convert speech input from a microphone into text. The system uses Google Web Speech API to recognize speech and provide the transcribed text.

## Features

1. **Real-time Speech Recognition**: The program listens to the user's voice through a microphone and converts the speech into text.
2. **Error Handling**: The program provides feedback if it cannot understand the speech or if there's an issue with the speech recognition service.
3. **Multiple Speakers**: The system adjusts to ambient noise and can recognize speech from different users.
4. **Customizable Language**: The speech recognition can be customized to different languages (currently set to English).

## How It Works

1. **Microphone Input**: The program listens for speech input from the default microphone device.
2. **Speech Processing**: The audio input is processed using the `speech_recognition` library.
3. **Text Output**: The recognized speech is outputted as text in the console.

### Process Flow

1. **Initialize**: The program initializes the recognizer and sets up the microphone for input.
2. **Listen**: The system listens to the microphone and processes any speech.
3. **Recognize**: The speech is sent to the Google Web Speech API, which transcribes it into text.
4. **Display**: The transcribed text is printed to the console.

## Technologies Used

- **Python**: The programming language used to develop the speech-to-text system.
- **SpeechRecognition**: A Python library used for performing speech recognition.
- **Google Web Speech API**: The API used to transcribe speech into text.
