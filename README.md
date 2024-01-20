# HörverstehenPro
Semantic Data Processing and Representation- MAI-THWS Groupwork

<img width="600" alt="HörverstehenPro" src="https://github.com/Tharindupriyaharshana/H-rverstehenPro/assets/45678705/c837e36d-a642-4b6f-85d1-c18093716b50">


This code represents a sophisticated tool designed for helping students, particularly those learning German, to understand spoken German better. It's a Gradio-based web application named "HörverstehenPro," incorporating various AI models for tasks like speech recognition, grammar correction, translation, and grammatical analysis.

This tool seems particularly useful for students learning German, enabling them to practice listening, understand spoken German better, correct their grammar, and translate to their native language, all while identifying key parts of speech.


**The models used**

- Whisper Model: A large-v3 model from OpenAI's Whisper series is loaded for speech recognition.

- Spacy Model: The de_core_news_sm model from Spacy, tailored for German language processing, is loaded for grammatical analysis.

- T5 Grammar Correction Model: A model specialized in correcting German grammar.

- Translation Model: This is used to translate German to English, specifically the Helsinki-NLP/opus-mt-de-en model.


**Function Definitions:**

- correct_grammar: Corrects grammar in a given German text using the T5 model.
generate_diff: Generates a textual difference between original and corrected text.
- transcribe_and_correct: Transcribes audio to text, corrects its grammar, and shows differences.
- transcribe_and_translate: Handles audio input, transcribes it to German text, corrects grammar, translates to English, and extracts nouns and verbs.


**Audio Processing:**

The code handles audio input, either as a file or a NumPy array, and processes it for transcription and language detection.

**Language Detection and Transcription:**

Whisper's language detection is hinted to focus on German.
The audio is transcribed, and the German text is obtained.

**Translation and Grammatical Analysis:**

The transcribed German text is translated into English.
Spacy's NLP model is used to extract nouns and verbs from the original German text.

