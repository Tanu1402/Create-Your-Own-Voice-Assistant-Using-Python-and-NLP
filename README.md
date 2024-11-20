# Create-Your-Own-Voice-Assistant-Using-Python-and-NLP
Description of Main Functionalities:
Voice Command Recognition:

The assistant listens to user commands using the sounddevice library for audio capture and the speech_recognition library for speech-to-text conversion.
It identifies commands starting with the keyword "Alexa" and processes them accordingly.
Text-to-Speech Conversion:

Uses pyttsx3 to convert text responses into speech, enabling the assistant to communicate effectively.
Media Playback:

Recognizes commands containing "play" and uses pywhatkit to search and play songs on YouTube.
Time Inquiry:

Responds to queries about the current time, providing the time in a 12-hour AM/PM format.
Wikipedia Search:

Handles commands like "Who is...", fetching a short summary from Wikipedia using the wikipedia library.
Includes error handling for ambiguous results, missing pages, or other issues.
Joke Generator:

Shares jokes in response to commands containing "joke" using the pyjokes library.
Exit Command:

Stops the program when the user says "stop".
Error Handling:

Manages cases where the user's speech isn't clear or when external services (like Google’s speech recognition or Wikipedia) encounter issues, ensuring robust performance.
This assistant uses modern Python libraries to provide a fun and interactive experience, demonstrating practical applications of Natural Language Processing and voice automation.
