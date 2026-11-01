<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:07090d,55:0d2b25,100:3ef0a8&height=220&section=header&text=Karan%20Katore&fontSize=60&fontColor=eef3fa&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Computer%20Vision%20%C2%B7%20Generative%20AI&descAlignY=58&descSize=18&animation=fadeIn" alt="Karan Katore — AI Engineer" />
</p>

<p align="center">
  <a href="https://karankatore01.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1100&color=3EF0A8&center=true&vCenter=true&width=680&lines=AI+Engineer+%40+NymbleUp+%F0%9F%9A%80;I+teach+cameras+to+recognise+people;One+person%2C+many+cameras%2C+one+identity;RAG+chatbots+%26+LLM+applications;Models+that+leave+the+notebook" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://karankatore01.github.io"><img src="https://img.shields.io/badge/Portfolio-karankatore01.github.io-3ef0a8?style=for-the-badge&logo=googlechrome&logoColor=07090d" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/karan-katore-3a3280243"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karankatore01@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.kaggle.com/karankatore01"><img src="https://img.shields.io/badge/Kaggle-Notebooks-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/%E2%9A%A1%20currently-building%20real--time%20multi--camera%20analytics%20at%20NymbleUp-0b0f16?style=flat-square&labelColor=3ef0a8" alt="Currently building real-time multi-camera analytics at NymbleUp" />
</p>

---

### `> whoami`

```python
class KaranKatore:
    role      = "AI Engineer @ NymbleUp"
    based_in  = "Mumbai, India 🇮🇳"
    focus     = ["Computer Vision", "Multi-camera Tracking & Re-ID", "Generative AI", "RAG"]
    education = "B.Tech CSE · Sandip University · CGPA 8.68"

    def superpower(self):
        return "turning raw CCTV into answers: who, where, how many"
```

---

## 🏆 Flagship · [Multi-Camera Detection & Person Re-ID](https://github.com/karankatore01/multi_camera_detection)

> **The problem:** a person walks past five cameras — and every camera thinks it's a different person.
> **The fix:** detect everyone, describe each person by appearance, and give them **one identity across all cameras.**

```mermaid
flowchart LR
    A["📹 Cameras<br/>1…N"] --> B["🎯 YOLOv8<br/>detect people"]
    B --> D["🧬 Re-ID<br/>embedding"]
    D --> E{"🔗 Seen<br/>before?"}
    E -- "yes / no" --> G[("🧍 One global ID<br/>per person")]

    classDef node fill:#0b0f16,stroke:#3ef0a8,color:#eef3fa,stroke-width:1.5px
    classDef key fill:#0d2b25,stroke:#3ef0a8,color:#3ef0a8,stroke-width:2px
    class A,B,D node
    class E,G key
```

<p>
  <img src="https://img.shields.io/badge/YOLOv8-detection-3ef0a8?style=flat-square&labelColor=0b0f16" />
  <img src="https://img.shields.io/badge/Re--ID-embeddings-5ab4ff?style=flat-square&labelColor=0b0f16" />
  <img src="https://img.shields.io/badge/FastReID-matching-b18cff?style=flat-square&labelColor=0b0f16" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  &nbsp;<a href="https://github.com/karankatore01/multi_camera_detection"><img src="https://img.shields.io/badge/%E2%86%92%20view%20code-3ef0a8?style=flat-square" /></a>
</p>

---

## 🧪 More things I've built

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧍 Global Identity Matching</h3>
      <i>"Is this the same person I saw on camera 3?"</i><br/><br/>
      Matches people across cameras with <b>FastReID</b> embeddings and similarity search, keeping a shared registry of global identities.
      <br/><br/>
      <img src="https://img.shields.io/badge/FastReID-0b0f16?style=flat-square" /> <img src="https://img.shields.io/badge/PyTorch-0b0f16?style=flat-square&logo=pytorch" /> <img src="https://img.shields.io/badge/Similarity%20search-0b0f16?style=flat-square" />
      <br/><br/><a href="https://github.com/karankatore01/camera_detect"><b>→ code</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🎓 Real-Time Student Monitoring</h3>
      <i>"Who's confused right now — and who's cheating?"</i><br/><br/>
      Students' webcams stream to a <b>FastAPI</b> backend; a teacher dashboard shows live engagement, confusion and proctoring alerts with explainable CV logic.
      <br/><br/>
      <img src="https://img.shields.io/badge/FastAPI-0b0f16?style=flat-square&logo=fastapi" /> <img src="https://img.shields.io/badge/OpenCV-0b0f16?style=flat-square&logo=opencv" /> <img src="https://img.shields.io/badge/Live%20dashboard-0b0f16?style=flat-square" />
      <br/><br/><a href="https://github.com/karankatore01/student-monitoring-system"><b>→ code</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💬 RAG-Based AI Chatbot</h3>
      <i>"Answer from my documents, not from thin air."</i><br/><br/>
      Retrieval-augmented chatbot with <b>LangChain + FAISS</b>, served on Flask and AWS Lambda — <b>+30% response relevance</b> over plain retrieval.
      <br/><br/>
      <img src="https://img.shields.io/badge/LangChain-0b0f16?style=flat-square" /> <img src="https://img.shields.io/badge/FAISS-0b0f16?style=flat-square" /> <img src="https://img.shields.io/badge/AWS%20Lambda-0b0f16?style=flat-square&logo=awslambda" />
      <br/><br/><a href="https://github.com/karankatore01/Rag-Based-ChatBot"><b>→ code</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 MBTI Personality Prediction</h3>
      <i>"Tell me how you write — I'll tell you who you are."</i><br/><br/>
      NLP model that reads a person's text and predicts which of the <b>16 MBTI personality types</b> they are, wrapped in a Flask web app.
      <br/><br/>
      <img src="https://img.shields.io/badge/NLP-0b0f16?style=flat-square" /> <img src="https://img.shields.io/badge/scikit--learn-0b0f16?style=flat-square&logo=scikitlearn" /> <img src="https://img.shields.io/badge/Flask-0b0f16?style=flat-square&logo=flask" />
      <br/><br/><a href="https://github.com/karankatore01/MBTI-Personality-Prediction"><b>→ code</b></a>
    </td>
  </tr>
</table>

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,c,pytorch,tensorflow,opencv,sklearn&theme=dark" alt="ML stack" /><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,flask,aws,postgres,mysql,git,github,vscode,html,css,js&theme=dark" alt="Tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/YOLO-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/FastReID-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/LangChain-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/Hugging%20Face-0b0f16?style=flat-square&logo=huggingface" />
  <img src="https://img.shields.io/badge/Transformers-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/FAISS-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/Keras-0b0f16?style=flat-square&logo=keras" />
  <img src="https://img.shields.io/badge/XGBoost-0b0f16?style=flat-square" />
  <img src="https://img.shields.io/badge/Pandas-0b0f16?style=flat-square&logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-0b0f16?style=flat-square&logo=numpy" />
</p>

---

<p align="center">
  <a href="https://karankatore01.github.io">
    <img src="https://img.shields.io/badge/%F0%9F%9A%80%20Explore%20my%20portfolio%20%E2%80%94%20train%20a%20neural%20net%20in%20your%20browser-3ef0a8?style=for-the-badge&labelColor=0b0f16" alt="Explore my portfolio" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3ef0a8,45:0d2b25,100:07090d&height=110&section=footer" alt="" />
</p>
