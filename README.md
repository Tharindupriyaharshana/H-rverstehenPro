
Our GitHub repository contains:
1. Text generation with Markov Chains

2. Classification tutorial

3. Presentations of two papers

4. Three distinct final projects
    - 4.1  HörverstehenPro
    - 4.2 meme.me
    - 4.3  Blenderbot

Contribution of the team:
1. Rupaningal Tharindu Priya Harshana De Silva (Matriculation no: 5123701 ):    33.33%
2. Bibin Babu (Matriculation no: 5122732): 33.33%
3. Fikrat (Matriculation no: 5122xxxx):   33.33%

HörverstehenPro: This project focuses on enhancing German language learning. It features a sophisticated tool that converts spoken German into text, providing grammatical corrections along the way. Additionally, it identifies and highlights verbs and nouns within the text. This functionality aids students in understanding and mastering the German language, particularly its complex grammar and vocabulary.

meme.me: Aimed at creating engaging content for science-based social media campaigns, this project generates memes that are both informative and entertaining. By blending humor with scientific facts, it seeks to make science more accessible and appealing to a wider audience. This tool is perfect for educators, communicators, and social media managers who want to share scientific knowledge in a fun and relatable way.

Blender Helper: This project is a chat support tool designed specifically for users of the Blender software. It provides real-time assistance, answering queries and offering solutions to common problems encountered by Blender users. With an intuitive interface and a comprehensive knowledge base, Bender Helper aims to enhance the user experience and streamline the problem-solving process for Bender software.




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
- transcribe_and_correct: Transcribes audio to text, corrects its grammar and shows differences.
- transcribe_and_translate: Handles audio input, transcribes it to German text, corrects grammar, translates to English, and extracts nouns and verbs.


**Audio Processing:**

The code handles audio input, either as a file or a NumPy array, and processes it for transcription and language detection.

**Language Detection and Transcription:**

Whisper's language detection is hinted to focus on German.
The audio is transcribed, and the German text is obtained.

**Translation and Grammatical Analysis:**

The transcribed German text is translated into English.
Spacy's NLP model is used to extract nouns and verbs from the original German text.


# meme.me

Edtech companies often use educational memes on social media as part of their branding strategy. These memes are effective for engaging with audiences and increasing visibility. However, maintaining a daily posting schedule poses challenges. The meme creators, often individual meme makers or "trollers," struggle with consistency due to time constraints and the difficulty of continuously generating creative ideas. A frequent posting schedule is crucial as it leads to higher engagement and, consequently, a larger audience.

Fine-tuned on: open_llama_3b"
We leverage QLorA to efficiently decrease the training time

<img width="600" alt="HörverstehenPro" src="https://github.com/Tharindupriyaharshana/H-rverstehenPro/assets/45678705/7cd3ff50-a54e-44f0-b105-d5af30f27dca">

<img width="600" alt="HörverstehenPro" src="https://github.com/Tharindupriyaharshana/H-rverstehenPro/assets/45678705/eb9fd046-7736-42fb-9d38-1685daed378b">



Solution: The proposed solution is the use of AI-assisted meme creation to sustain the quality and frequency of posts. By leveraging artificial intelligence, edtech companies can overcome this by AI assistance

# Blender BOT

Fine-tune the EleutherAI Pythia-410M model to develop a chatbot specialized in answering questions related to Blender software

