# pdf-to-audio-py

Using Python's _**pypdf2**_, _**pikepdf**_, _**pttsx3**_ and _**gtts**_ modules I've built this application. It:
1. **Decrypts** the pdf file with _**pikepdf**_ in case it was encrypted.
2. **Converts** the PDF to text using _**pypdf2**_.
3. Then converts the text to audio using _**pyttsx3__*.
4. And finally _saves_ the audio file using _**gTTs**_.