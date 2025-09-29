<h1 align="center">✨ Arindam Singh</h1>
<h3 align="center">AI & Machine Learning Engineer | Building Intelligent Applications</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira%20Code&size=24&pause=1000&color=38C2FF&center=true&vCenter=true&width=707&lines=AI/Machine+Learning+%7C+Web+Dev+%7C+Electronics+Engg.;Python+%7C+PyTorch+%7C+FastAPI;Building+Intelligent%2C+Responsive...;and+Scalable+Applications.;From+Data+to+Deployment;Creating+Seamless+AI-Powered+Experiences" alt="Typing SVG" />
</p>

<!-- <img src="https://readme-typing-svg.herokuapp.com?font=Fira%20Code&size=24&pause=1000&color=38C2FF&center=true&vCenter=true&width=700&lines=AI/ML+%7C+Web+Dev+%7C+Electronics;Python+%7C+PyTorch+%7C+FastAPI;Building+intelligent+apps.;From+data+to+deployment%2C+AI-powered+experiences" alt="Typing SVG" /> -->

<!-- <p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira%20Code&size=24&pause=1000&color=38C2FF&center=true&vCenter=true&width=700&lines=AI%2FML%20Developer%20%7C%20Web%20Development%20%7C%20Deep%20Learning%20%7C%20;Crafting%20Intelligent%2C%20User-centric%20Solutions;Code%20that%20Learns;Systems%20that%20Scale;Experiences%20that%20Delight" alt="Typing SVG" />
</p> -->

-----

## 🌟 About Me

<!-- I am a passionate and results-oriented engineer with a strong foundation in **Machine Learning** and **Web Development**. My focus is on building robust, end-to-end AI-powered applications, from fine-tuning Large Language Models (LLMs) to deploying them in scalable, containerized environments. I thrive on architecting efficient back-end systems and creating intuitive user experiences. -->

I'm a passionate and results-oriented engineer with a broad foundation spanning **Machine Learning**, **Web Development**, and Software Engineering principles. I specialize in building robust, end-to-end AI-powered applications, from fine-tuning **Large Language Models (LLMs)** to deploying them in scalable, **containerized environments**. I also thrive on architecting efficient back-end systems and leveraging Python for **data-intensive tasks** and **hardware design** automation, always focused on delivering intuitive and high-performance solutions.




<!-- 🛠️ Currently engineering with:

- **Python + PyTorch** – from quick-and-dirty notebooks to production LLM inference 
- **Hugging Face Transformers** powered by **LoRA / QLoRA (Unsloth)** for lean, accurate models 
- **FastAPI & WebSockets** – async back-ends that keep latency in the sub-second sweet spot 
- **Docker / Docker Compose** for one-command, cloud-to-laptop reproducibility 
- Laser-focus on **model optimisation**, **container-native deployments**, and **sub-10 ms on-device AI performance** so users get GPU-class magic on everyday hardware -->

<!-- 🛠️ Currently engineering with:

* **Python (Full-Stack & Specialized)**: Building robust, high-performance applications.
    * **Core Development**: Strong in OOP, data structures, algorithms, and testing (`pytest`).
    * **Web Services**: Developing fast, asynchronous back-ends with **FastAPI & WebSockets**, plus experience with **Django/Flask**.
    * **Data Science & AI**: Leveraging **Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn**, and **PyTorch**. Specializing in **LLM inference** and fine-tuning with **Hugging Face Transformers (LoRA/QLoRA)**.
* **Software Development Engineering (SDE)**: Applying best practices in design patterns, **Git/GitHub**, CI/CD, and API design for scalable systems.
* **Hardware Design Automation**: Using Python for scripting and automation in **Digital Design** and **VLSI flows**, including testbench generation, data parsing, and regression management.
* **DevOps & Optimization**: Deploying with **Docker/Docker Compose** for reproducibility. Focused on **model optimization** and achieving **sub-10 ms on-device AI performance**. -->


🛠️ Currently engineering with:

* **Python (Full-Stack & Specialized)**: Building robust, high-performance applications.
    * **Core Development**: Strong in OOP, data structures, algorithms, and testing (`pytest`).
    * **Web Services**: Developing fast, asynchronous back-ends with **FastAPI & WebSockets**.
    * **Data Science & AI**: Leveraging **Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn**, and **PyTorch**. Specializing in **LLM inference** and fine-tuning with **Hugging Face Transformers (LoRA/QLoRA)** and **Unsloth**.
* **Software Development Engineering (SDE)**: Applying best practices in design patterns, **Git/GitHub**, CI/CD, and API design for scalable systems.
* **Hardware Design Automation**: Using Python, Verilog, VHDL, C, and C++ for scripting and automation in **Digital Design** and **VLSI flows**, including testbench generation, data parsing, and regression management.
* **DevOps & Optimization**: Deploying with **Docker/Docker Compose** for reproducibility. Focused on **model optimization** and achieving **optimized on-device AI performance**.



## 🚀 Projects

### 🤖 MediQueryBot: Multi-LLM Medical-Query Chatbot

**[Live Demo](https://huggingface.co/spaces/ArindamSingh/MediQuery)** | **[GitHub](https://huggingface.co/spaces/ArindamSingh/MediQuery)**

  * Designed a mobile-responsive glass-morphic web app for medical query answering using switchable LLM back-ends (Gemma 1B, Qwen 0.6B, Mistral 7B Q4 KM, Gemini Flash 2.5). 
  * Implemented an asynchronous FastAPI server that autoloads Hugging Face Transformers and quantized GGUF models, persisting chat histories in JSON. 
  * Fine-tuned multiple checkpoints with LORA, QLORA, and the Unsloth library; achieved 100+ downloads for my Gemma-1B LORA model on Hugging Face. 
  * Containerized the entire stack with Docker and deployed on Hugging Face Spaces (Docker runtime). 

### ✍️ ScribbleSense: On-device AI Whiteboard

**[Live Demo](https://singharindam.github.io/ScribbleSense/frontend/index.html)** | **[GitHub](https://github.com/SinghArindam/ScribbleSense)**

  * Developed an open-source canvas (Excalidraw + React) recognizing hand-written digits (<10 ms) or performing local OCR on CPU-only devices. 
  * The FastAPI back-end serves ONNX Runtime digit CNN and EasyOCR pipelines, featuring automatic model download and checksum verification. 
  * Established a single-service Docker Compose setup, achieving benchmarks of digit recognition in 79-133 ms and OCR in 153-178 ms on an Intel i3-6006U CPU. 

### 📊 Canvas Lytics: Natural-Language Data-Exploration Canvas

**[Live Demo](https://singharindam.github.io/CanvasLytics/)** | **[GitHub](https://github.com/SinghArindam/CanvasLytics)**

  * Created an infinite Excalidraw-style canvas enabling users to explore data and build baseline ML models via natural-language commands. 
  * Developed a React / Next.js SPA communicating via WebSockets with an agent orchestrating two micro-services: pandas-eda and sklearn-lab. 
  * Implemented features including one-click Titanic CSV load, visual analytics (histograms, correlation heatmaps), a scikit-learn pipeline wizard, and shareable boards.

-----

## 🧠 Technical Stack

### 🤖 Machine Learning & AI

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFCA28?style=flat-square\&logo=huggingface\&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikit-learn\&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-00A35C?style=flat-square\&logo=llama\&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-444444?style=flat-square\&logo=code\&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA-8E44AD?style=flat-square\&logo=code\&logoColor=white)
![QLoRA](https://img.shields.io/badge/QLoRA-8E44AD?style=flat-square\&logo=code\&logoColor=white)
![Unsloth](https://img.shields.io/badge/Unsloth-555555?style=flat-square\&logo=code\&logoColor=white)
<!-- ![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square\&logo=onnx\&logoColor=white) -->

---

### 🖥️ Backend & Web Development

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-6DB33F?style=flat-square\&logo=socketdotio\&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-000000?style=flat-square\&logo=api\&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-000000?style=flat-square\&logo=python\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

---

### 🗄️ Databases & Data Analysis

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square\&logo=apache\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square\&logo=plotly\&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-1F77B4?style=flat-square\&logo=python\&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square\&logo=plotly\&logoColor=white)

---

### 🧰 Platforms & Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square\&logo=visualstudiocode\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square\&logo=jupyter\&logoColor=white)
![Hugging Face Spaces](https://img.shields.io/badge/HF_Spaces-FFCA28?style=flat-square\&logo=huggingface\&logoColor=black)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square\&logo=kaggle\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)

-----

## 🏆 Achievements

  - **GATE 2025 ECE Score: 518 | AIR: 2724** (February 2025)
  - **Smart India Hackathon 2024 Grand Finalist** (December 2024)
  - CodeGeeks Hackathon Participant (May 2023)
  - Vihaan 6.0 Hackathon Participant (March 2023)

-----

## 📈 GitHub Snapshot

<!-- ## 📊 GitHub Stats

![Arindam's GitHub stats](https://github-readme-stats.vercel.app/api?username=SinghArindam&show_icons=true&theme=tokyonight)

## 📘 Top Languages -->
<p align="center">

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SinghArindam&layout=compact&theme=tokyonight)

</p>

-----

## 🐍 Contributions Flow

<p align="center">
  <img src="https://raw.githubusercontent.com/SinghArindam/SinghArindam/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</p>

<!-- ## 📈 Contribution Graph

<p align="center">

![GitHub Activity Graph](https://github-readme-activity-graph.cyclic.app/graph?username=SinghArindam&theme=react-dark)

</p> -->

<!-- <p align="center">
<img src="[https://raw.githubusercontent.com/arindam-singh/arindam-singh/output/github-contribution-grid-snake.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/arindam-singh/arindam-singh/output/github-contribution-grid-snake.svg)" />
</p> -->

## 🔥 Streak Stats
<p align="center">

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=SinghArindam&theme=tokyonight&hide_border=false)
</p>
