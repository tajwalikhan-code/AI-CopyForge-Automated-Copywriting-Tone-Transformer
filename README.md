# 🚀 AI CopyForge – AI-Powered Marketing Copy Generator

> **Generate professional, engaging, and platform-specific marketing content using Generative AI, Prompt Engineering, and Groq's Llama 3.3 model.**

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![Groq](https://img.shields.io/badge/Groq-API-orange)
![Llama](https://img.shields.io/badge/Llama%203.3-70B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

</p>

---

# 📖 Project Overview

**AI CopyForge** is an AI-powered copywriting assistant that automatically generates high-quality marketing content for different platforms using **Large Language Models (LLMs)**.

Instead of manually writing marketing copy, users simply provide product information, choose a platform, select a writing tone, and the AI instantly creates engaging content.

This project was developed as part of the **Decode Labs Generative AI Internship** while extending the official requirements with additional professional features and industry-standard project architecture.

---

# ✨ Features

## 📝 AI Content Generation

- Professional Marketing Copy
- Product Descriptions
- Promotional Posts
- Sales Copy
- Brand Messaging
- Call-to-Action Generation

---

## 🌍 Multi-Platform Support

Generate content optimized for:

- LinkedIn
- Instagram
- Facebook
- Twitter (X)
- Email Campaigns
- Website Landing Pages
- Blog Posts

---

## 🎯 Writing Tone Selection

Choose different writing styles:

- Professional
- Friendly
- Persuasive
- Luxury
- Emotional
- Startup
- Technical
- Casual
- Formal

---

## ⚙️ Prompt Engineering

The application dynamically builds prompts using user inputs such as:

- Product Name
- Product Description
- Platform
- Target Audience
- Tone
- Creativity Level
- Word Limit
- Language

instead of using static prompts.

---

## 🤖 Powered by Groq Llama 3.3

The application uses

- Groq API
- Llama-3.3-70B-Versatile

for extremely fast AI inference.

---

## 📊 Adjustable AI Parameters

Users can customize:

- Creativity Level
- Word Limit
- Language
- Platform
- Tone

allowing complete control over generated outputs.

---

# 🏗 Project Architecture

```
                User Input
                     │
                     ▼
          Prompt Builder Module
                     │
                     ▼
            Dynamic Prompt Engine
                     │
                     ▼
              Groq Llama 3.3 API
                     │
                     ▼
           AI Generated Marketing Copy
                     │
                     ▼
              Streamlit Interface
```

---

# 📂 Project Structure

```
AI_CopyForge/

│

├── app.py                     # Streamlit User Interface

├── ai_engine.py               # Groq AI Engine

├── prompt_templates.py        # Prompt Builder

├── utils.py                   # Helper Functions

├── requirements.txt

├── README.md

├── .env.example

├── .gitignore

│

├── assets/

├── screenshots/

└── .streamlit/

```

---

# ⚡ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Streamlit | Web Application |
| Groq API | AI Inference |
| Llama 3.3 70B | Large Language Model |
| Prompt Engineering | Dynamic Prompt Creation |
| Python Dotenv | Environment Variables |
| Google Colab | Development |
| GitHub | Version Control |
| Hugging Face Spaces | Deployment |

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI_CopyForge.git

cd AI_CopyForge
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Activate

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
GROQ_API_KEY=your_api_key_here
```

Get your free API key from

https://console.groq.com/keys

---

# ▶ Run the Project

```bash
streamlit run app.py
```

The application will open in your browser.

---

# 💻 User Workflow

1. Enter Product Name
2. Enter Product Description
3. Select Platform
4. Select Writing Tone
5. Select Creativity Level
6. Enter Word Limit
7. Click **Generate Copy**
8. AI generates professional marketing content

---

# 📸 Screenshots

## Home Page

```
screenshots/home.png
```

## Generated Marketing Copy

```
screenshots/output.png
```

> Add your screenshots after completing the project.

---

# 📈 Learning Outcomes

This project helped me gain practical experience in:

- Prompt Engineering
- Generative AI
- Large Language Models (LLMs)
- AI API Integration
- Groq API
- Streamlit Development
- Modular Python Programming
- Environment Variable Management
- AI Application Deployment
- GitHub Project Organization

---

# 🚀 Future Improvements

- Chat History
- Export to PDF
- Copy to Clipboard
- Multiple AI Models
- Multi-language Translation
- Team Collaboration
- Authentication
- AI Content History
- Brand Templates
- Prompt Library
- SEO Optimization
- Image Generation Integration

---

# 📚 Skills Demonstrated

- Python Programming
- Generative AI
- Prompt Engineering
- API Integration
- Streamlit Development
- Software Engineering
- AI Product Development
- GitHub Best Practices
- Modular Programming
- Deployment

---

# 👨‍💻 Developer

**Taj Wali Khan**

Artificial Intelligence Enthusiast | Python Developer | AI Automation for Business | BCS AI Student at Abdul Wali Khan University Mardan | Exploring Emerging Technologies

---

## 📫 Connect With Me

**LinkedIn**

www.linkedin.com/in/taj-wali-khan-03a7693aa

**GitHub**

https://github.com/tajwalikhan-code

---

# 🙏 Acknowledgements

Special thanks to

- Decode Labs
- Groq
- Meta AI (Llama)
- Streamlit
- Open Source Community

for providing amazing tools and learning resources.

---

# ⭐ Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork it

💬 Share your feedback

---

# 📄 License

This project is licensed under the MIT License.

---

## 💡 Quote

> *"Artificial Intelligence is not here to replace creativity—it is here to amplify it."*

---

<p align="center">

### ⭐ If you like this project, don't forget to Star the Repository ⭐

Made with ❤️ by **Taj Wali Khan**

</p>
