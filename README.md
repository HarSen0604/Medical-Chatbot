# Medical-Chatbot
An AI-powered system designed to enhance mental health support by providing real-time emotional analysis and personalized interventions through user interaction.

## Synopsis

The global mental health landscape faces significant challenges, with rising mental health illnesses and suicide rates. Traditional communication methods between mental health professionals and individuals are limited, causing delays and inadequate support. This project leverages AI-powered emotional analysis to provide immediate, personalized care and early detection of suicidal ideation, offering a transformative solution for mental health support.

## Objectives

- **Facilitate Discussion on Mental Health**: Establish an online platform for open emotional expression with AI-driven guidance.
- **Empower Self-Management**: Provide tailored resources and actionable advice using AI technology.
- **Personalized Assistance**: Analyze individual circumstances with AI to create personalized reports and recommendations.
- **On-Demand Support**: Ensure 24/7 availability of the application for immediate access to support.

## Approach

- **AI Development**: Develop a sophisticated AI system for natural, empathetic conversations.
- **User-Friendly Design**: Create an intuitive application interface for seamless user experience.
- **Personalized Adaptation**: Implement algorithms for sensitive responses to mental health conditions.
- **Iterative Enhancement**: Conduct testing and refine the application based on user feedback.

## System Requirements

### Functional Requirements

- Integration of NLP, AI, vector search databases, and PDF text extraction.
- Features like natural conversations, personalized detection of mental health states, and seamless data processing.

### Non-Functional Requirements

- Fast and stable internet connectivity.
- Compatibility with required libraries and frameworks.

---

## Hardware Requirements

#### WSL (Windows Subsystem for Linux) Deployment

- **Minimum**: Ubuntu 20.04 (or later), Intel Core i5, 8GB RAM, 256GB SSD, Python 3.7+
- **Recommended**: Ubuntu 20.04 (or later), Intel Core i5, 8GB RAM, 512GB SSD, Python 3.7+

#### macOS Deployment

- **Minimum**: macOS Mojave, Intel Core i5, 8GB RAM, 256GB SSD, Python 3.7+
- **Recommended**: macOS Catalina, Intel Core i7 or Apple M-Series, 16GB RAM, 512GB SSD, Python 3.7+

## Software Requirements

- Compatible with libraries like PyPDF2, OpenAI's Python library, FAISS.
- Use IDEs like Visual Studio Code, PyCharm, or Jupyter Notebooks.

> **Note:**  
> While the program can technically run on Windows, setting it up can be a tedious process due to various dependencies and configuration issues. We highly recommend using a Linux-based OS (such as WSL) or macOS for a smoother and more reliable experience. WSL (Windows Subsystem for Linux) is a great alternative if you're on Windows, offering a Linux-like environment without the need for a full dual-boot setup.

---

## How to Run

### 1. Clone the repo:
```sh
git clone https://github.com/HarSen0604/Medical-Chatbot.git
```

### 2. Navigate to the directory:
```sh
cd Medical-Chatbot
```

### 3. Set up a virtual environment (optional, but recommended):
   - **For WSL or Linux-based systems (Ubuntu, etc.):**
     ```sh
     python -m venv venv
     source venv/bin/activate
     ```
   - **For macOS:**
     ```sh
     python -m venv venv
     source venv/bin/activate
     ```
   - **For Windows (if using Windows natively):**
     ```sh
     python -m venv venv
     .\venv\Scripts\activate
     ```

   > **Note:** Activating the virtual environment ensures that you have a clean environment to install dependencies without interfering with your system-wide Python installation.

### 4. Install the required packages:
```sh
pip install -r requirements.txt
```

### 5. Add your OpenAI API key to `openai_key.pem`:

### 6. Run the application:
```sh
python app.py
```

### 7. Open the link shown in the terminal:
   - After running the app, you'll see a URL in the terminal. Click on or copy-paste it into your browser to access the chatbot.