# 🧠 AI Agent with SmolAgents

This project is an AI-powered agent built using **SmolAgents** and deployed on **Hugging Face Spaces**.  
It integrates various tools, including:  
✅ **City Distance Calculator** – Computes the distance between two cities  
✅ **Timezone Converter** – Fetches the current time in a given timezone  
✅ **Image Generation** – Uses a text-to-image model from Hugging Face  
✅ **Custom AI Model** – Powered by an external Hugging Face API endpoint  

## 🚀 Access the app here:  
🔗 **[AI Agent on Hugging Face](https://huggingface.co/spaces/Jade-E/First_agent_template)**  

---

## 🛠 Tech Stack
- **SmolAgents** – Lightweight AI agent framework  
- **Hugging Face Spaces** – Hosting platform  
- **Gradio** – User interface  
- **Geopy** – Location-based calculations  
- **Pytz** – Timezone conversions  
- **YAML** – Configuration and prompts storage  

---

## 🔧 Features & Tools
### 🌍 Distance Between Cities  
Uses `geopy` to calculate the distance between two cities using latitude/longitude coordinates.  

### 🕒 Timezone Converter  
Fetches the current time for any valid timezone using `pytz`.  

### 🎨 AI Image Generator  
Integrates a text-to-image generation tool from Hugging Face.  

### 🔥 AI Code Agent  
Leverages an **HfApiModel** with a pre-configured Hugging Face model endpoint for intelligent responses.  

---

## 🏗 Installation (For Local Development)
Clone the repository and install dependencies:  
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
pip install -r requirements.txt
python app.py
