# 🧠 Multi-Model AI Image Analyzer / 🌟 AI Vision Assistant

> Compare how the world’s top AI models “see” your images — powered by **GPT-5-Pro**, **Gemini 2.5 Flash**, and **Grok-4 Fast**.  
> Built by [Tanmay Kshirsagar](https://www.linkedin.com/in/tanmay-kshirsagar) • Powered by [OpenRouter.ai](https://openrouter.ai)

---

## 🚀 Overview

**Multi-Model AI Image Analyzer** is a cutting-edge web app that lets users upload an image and instantly view how three leading multimodal AI models interpret it — all side-by-side.

Built using **Python 3.10**, **Gradio**, and **OpenRouter’s unified API**, it supports:
- ⚡ **Parallel async API calls** for 3× faster response time  
- 🎨 **Responsive, fixed-size image preview**  
- 🧩 **GPT-5-Pro summary generation** comparing model responses  
- 💾 **Downloadable analysis report** (UTF-8 safe)  
- 💻 **Clean, recruiter-ready UI** built with Gradio Blocks  

---

## 🖼️ Demo Preview

![App Screenshot](assets/demo-screenshot.png)

*(Optional: replace this with your Gradio app screenshot)*

---

## 🧩 Tech Stack

| Layer | Tools |
|-------|-------|
| **Frontend** | Gradio (Blocks UI, custom theme) |
| **Backend** | Async Python + OpenRouter API |
| **Models Used** | GPT-5-Pro (OpenAI), Gemini 2.5 Flash (Google), Grok-4 Fast (xAI) |
| **Infra** | Google Colab / Local Python Environment |
| **Output** | Text comparison + summary + downloadable report |

---

## 🧠 How It Works

1. User uploads an image.  
2. The app sends the image simultaneously to:
   - **GPT-5-Pro**
   - **Gemini 2.5 Flash**
   - **Grok-4 Fast**
3. Each model returns a description.  
4. **GPT-5-Pro** generates a comparative summary of all three outputs.  
5. Results appear in real time — ready to download or analyze further.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/Tanmay1112004/multi-model-ai-image-analyzer.git
cd multi-model-ai-image-analyzer
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

*(If using Colab, dependencies auto-install inside notebook)*

### 3️⃣ Add your API key

Edit `app.py` and replace:

```python
OPENROUTER_API_KEY = "YOUR_API_KEY"
```

Get your key from 👉 [https://openrouter.ai](https://openrouter.ai)

### 4️⃣ Run the app

```bash
python app.py
```

Or, inside Colab:

```python
!python app.py
```

### 5️⃣ Launch the Gradio link

Click the public URL — upload an image — enjoy the analysis 🚀

---

## 🧾 Requirements

```text
openai
gradio
aiohttp
nest_asyncio
```

*(included in `requirements.txt`)*

---

## 📊 Features Breakdown

| Feature                      | Description                                        |
| ---------------------------- | -------------------------------------------------- |
| 🧠 GPT-5-Pro Summary         | Automatically compares outputs                     |
| ⚡ Parallel Async Calls       | All 3 models run simultaneously                    |
| 🖼️ Fixed-Size Image Preview | Keeps layout uniform & neat                        |
| 💾 Downloadable Report       | UTF-8 encoded text file                            |
| 🎨 Modern Blue Theme         | Recruiter-friendly interface                       |
| 🧱 Built for AI Engineers    | Demonstrates both backend & frontend design skills |

---

## 💼 Recruiter Notes

This project demonstrates:

* Strong grasp of **AI API integrations** (OpenRouter / OpenAI / Google / xAI)
* Expertise in **Python async, I/O, and performance optimization**
* Clean **frontend design principles** via Gradio
* Product-grade engineering discipline (structured code, documentation, UX)

Perfect fit for roles in:

* **AI Engineering / ML Engineering**
* **Generative AI Applications**
* **Full-Stack ML Development**
* **Data Science + LLM Ops**

---

## 🔗 Connect

👤 **Tanmay Kshirsagar**
📧 [tanmaykshirsagar001@gmail.com](mailto:tanmaykshirsagar001@gmail.com)
🌐 [Portfolio](https://tanmayportfolio.ccbp.tech)
💼 [LinkedIn](https://www.linkedin.com/in/tanmay-kshirsagar)
🐙 [GitHub](https://github.com/Tanmay1112004)

---

## ⭐ Show Some Love

If this project inspired you, drop a ⭐ on the repo — it helps more people discover it!

---

````

---

## ✅ **requirements.txt**
```text
openai
gradio
aiohttp
nest_asyncio
````

---

## 🧱 Suggested `.gitignore`

```
__pycache__/
*.pyc
.env
*.txt
.colab/
.ipynb_checkpoints/
```

---

## ⚡ Summary for Recruiters

| Value                    | Why It Matters                                         |
| ------------------------ | ------------------------------------------------------ |
| **AI Model Integration** | Proves you can handle complex APIs + multimodal inputs |
| **Async Python**         | Shows performance-focused coding                       |
| **Frontend Polish**      | Indicates UI/UX understanding                          |
| **OpenRouter Expertise** | Signals comfort with latest AI model APIs              |
| **Project Branding**     | Recruiters love clean docs + visual appeal             |

---

