## 📝 Blog Generator with LLaMA-2-7B and Streamlit(PROMPT ENGINEERING)
This project is a simple web app that generates blogs using a locally hosted LLaMA 2 model via the Langchain and CTransformers libraries. The app is built using Streamlit, which provides an interactive interface for users to input a topic, desired word count, and select a target audience.

## 🚀 Features
Generate blog posts using the LLaMA 2 model locally.

Customizable:

Input your own topic.

Choose a word count.

Select the blog audience (Researchers, Data Scientists, or Common People).

Fast and lightweight, thanks to CTransformers.

## 🛠️ Tech Stack
Streamlit – UI framework

Langchain – Prompt templating

CTransformers – Local LLaMA model loading and inference

LLaMA 2 – The language model used for text generation



They choose the number of words and the audience style.

On clicking the "Generate" button, the app:

Loads the LLaMA model.

Formats a prompt using Langchain.

Generates the blog via CTransformers.

The blog is then displayed in the app.

## ✅ Prerequisites
1.Python 3.8+

2.LLaMA model file (e.g., llama-2-7b-chat.ggmlv3.q2_K.bin)
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/b616819cd4777514e3a2d9b8be69824aca8f5daf
(YOU GET THE MODEL FROM ABOVE LINK)

## Install dependencies:
pip install streamlit langchain ctransformers

## ▶️ Running the App :
streamlit run blog_generator.py
⚠️ Notes
Ensure the LLaMA model file is placed correctly in the models/ directory.


## RESULTS :
![Screenshot 2025-05-17 144449](https://github.com/user-attachments/assets/14b3221f-6748-4183-b7c4-f876a67d500f)


This app assumes you're using a quantized .bin version of the LLaMA model compatible with CTransformers and Using prompt engineering (PromptTemplate) to guide the response.
