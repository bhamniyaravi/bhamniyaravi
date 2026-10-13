Ravi Bhamniya
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:2563EB&height=220&section=header&text=Ravi%20Bhamniya&fontSize=55&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <a href="https://github.com/bhamniyaravi">GitHub</a> ·
  <a href="https://www.linkedin.com/in/ravi-bhamniya-4aa4aa34a/">LinkedIn</a> ·
  <a href="https://leetcode.com/u/bhamniyaravi8/">LeetCode</a> ·
  <a href="https://codeforces.com/profile/bhamniyaravi8">Codeforces</a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2500&pause=900&color=2563EB&center=true&vCenter=true&width=800&lines=AI+%26+Data+Science+Student;Building+Agentic+AI+Systems;Developing+RAG+%26+LLM+Applications;Exploring+AI+Security+%26+Guardrails;Machine+Learning+%7C+Deep+Learning+%7C+GenAI;Turning+Ideas+into+Real-World+AI+Solutions" />
</p>

About Me
Hi, I'm Ravi Bhamniya, a B.Tech student specializing in Artificial Intelligence and Data Science.
I am interested in building intelligent systems using Machine Learning, Deep Learning, Generative AI, Agentic AI, RAG, and Large Language Models.
My current focus is on building AI systems that are reliable, secure, tool-aware, grounded, and production-ready.
Machine Learning
Machine Learning is the foundation of my AI journey, covering data preparation, feature engineering, model training, evaluation, and deployment.
ML Workflow
```mermaid
flowchart TD
    A["Raw Data"]
    --> B["Data Collection"]
    --> C["Data Cleaning"]
    --> D["Exploratory Data Analysis"]
    --> E["Feature Engineering"]
    --> F["Train / Validation / Test Split"]
    --> G["Model Selection"]

    G --> G1["Regression"]
    G --> G2["Classification"]
    G --> G3["Clustering"]
    G --> G4["Dimensionality Reduction"]

    G1 --> H["Model Training"]
    G2 --> H
    G3 --> H
    G4 --> H

    H --> I["Hyperparameter Tuning"]
    --> J["Model Evaluation"]

    J --> K{"Performance Good?"}
    K -->|No| E
    K -->|Yes| L["Model Deployment"]
    L --> M["Monitoring & Retraining"]
```
ML Concepts
Machine Learning
│
├── Supervised Learning
│   ├── Regression
│   └── Classification
│
├── Unsupervised Learning
│   ├── Clustering
│   └── Dimensionality Reduction
│
├── Reinforcement Learning
│
├── Feature Engineering
├── Model Selection
├── Cross Validation
├── Hyperparameter Tuning
└── Model Evaluation
Algorithms
Regression
├── Linear Regression
├── Polynomial Regression
└── Ridge / Lasso

Classification
├── Logistic Regression
├── Decision Tree
├── Random Forest
├── SVM
├── KNN
└── XGBoost

Unsupervised Learning
├── K-Means
├── Hierarchical Clustering
└── PCA
Deep Learning
Deep Learning focuses on neural-network-based learning for NLP, computer vision, sequence modeling, and complex pattern recognition.
DL Workflow
```mermaid
flowchart TD
    A["Input Data"]
    --> B["Preprocessing"]
    --> C["Neural Network"]
    --> D["Forward Propagation"]
    --> E["Loss Function"]
    --> F["Backpropagation"]
    --> G["Optimizer"]
    --> H["Weight Update"]

    H --> I{"Converged?"}
    I -->|No| D
    I -->|Yes| J["Trained Model"]

    J --> K["Validation"]
    --> L["Testing"]
    --> M["Deployment"]
```
Deep Learning Structure
Deep Learning
│
├── Neural Networks
│   ├── ANN
│   ├── CNN
│   ├── RNN
│   ├── LSTM
│   └── GRU
│
├── Computer Vision
│   ├── Image Classification
│   ├── Object Detection
│   └── Image Segmentation
│
├── NLP
│   ├── Text Classification
│   ├── Sentiment Analysis
│   └── Sequence Modeling
│
├── Transformers
│   ├── Attention
│   ├── Encoder
│   └── Decoder
│
└── Transfer Learning
Deep Learning Model Lifecycle
Dataset
   ↓
Preprocessing
   ↓
Architecture Selection
   ↓
Training
   ↓
Validation
   ↓
Hyperparameter Tuning
   ↓
Testing
   ↓
Model Saving
   ↓
API / Application
   ↓
Deployment
Emotion Analyzer
Tech: Python · Deep Learning · NLP · FastAPI · TensorFlow/Keras
```mermaid
flowchart LR
    A["Text Dataset"]
    --> B["Preprocessing"]
    --> C["Tokenization"]
    --> D["Embedding"]

    D --> E["SimpleRNN"]
    D --> F["LSTM"]
    D --> G["GRU"]
    D --> H["Bidirectional GRU"]

    E --> I["Compare Models"]
    F --> I
    G --> I
    H --> I

    I --> J["Best Model"]
    --> K["Emotion Prediction"]
```
The project classifies:
Sadness · Joy · Love · Anger · Fear · Surprise
The Bidirectional GRU model achieved approximately 91.70% test accuracy.
Generative AI
Generative AI is where I work with LLMs, embeddings, RAG, vector databases, structured outputs, and AI applications.
GenAI Workflow
```mermaid
flowchart TD
    A["Foundation Models"]
    --> B["Large Language Models"]

    B --> C["Prompt Engineering"]
    B --> D["Context Engineering"]
    B --> E["Fine-Tuning"]

    C --> F["LLM Application"]
    D --> F
    E --> F

    F --> G["Embeddings"]
    --> H["Vector Database"]
    --> I["Retrieval"]
    --> J["RAG"]
    --> K["Grounded Generation"]
    --> L["Structured Output"]
    --> M["Evaluation"]
    --> N["Production AI Application"]
```
Generative AI Structure
Generative AI
│
├── Foundation Models
├── Large Language Models
├── Prompt Engineering
├── Context Engineering
├── Embeddings
├── Vector Databases
├── Semantic Search
├── Retrieval-Augmented Generation
├── Fine-Tuning
├── Structured Outputs
├── Function / Tool Calling
├── Multimodal AI
└── LLM Evaluation
RAG Architecture
```mermaid
flowchart LR
    A["Documents / PDFs"]
    --> B["Document Loader"]
    --> C["Text Splitting"]
    --> D["Embeddings"]
    --> E["Vector Database"]

    F["User Query"]
    --> G["Query Embedding"]
    --> E

    E --> H["Relevant Documents"]
    --> I["Retrieved Context"]
    --> J["LLM"]
    --> K["Grounded Response"]
```
Medical Chatbot
Tech: Python · Flask · LangChain · Groq · Pinecone · Hugging Face Embeddings · RAG
Medical PDFs
     ↓
Document Loader
     ↓
Text Splitting
     ↓
Hugging Face Embeddings
     ↓
Pinecone Vector Database
     ↓
Semantic Retrieval
     ↓
Relevant Medical Context
     ↓
Groq LLM
     ↓
Generated Answer
     ↓
Flask Chatbot UI
View Medical Chatbot
Agentic AI
Agentic AI focuses on systems that can understand goals, plan tasks, reason, use tools, maintain context, evaluate results, and take controlled actions.
Agentic AI Workflow
```mermaid
flowchart TD
    A["User Goal"]
    --> B["Understand Task"]
    --> C["Planning"]
    --> D["Reasoning"]
    --> E["Task Decomposition"]
    --> F["Agent Router"]
    --> G["Tool Selection"]
    --> H["Tool Execution"]
    --> I["Tool Result"]
    --> J["Memory / Context"]
    --> K["Evaluate Result"]

    K --> L{"Goal Complete?"}
    L -->|No| C
    L -->|Yes| M["Output Validation"]
    --> N["Guardrails"]
    --> O["Final Response"]
```
Agentic AI Components
Agentic AI
│
├── Agent
│
├── Planning
│   ├── Goal Understanding
│   ├── Task Decomposition
│   └── Step Planning
│
├── Reasoning
│   ├── Decision Making
│   ├── Reflection
│   └── Result Evaluation
│
├── Tools
│   ├── Web Search
│   ├── APIs
│   ├── Databases
│   ├── Python
│   └── Custom Functions
│
├── Memory
│   ├── Short-Term Memory
│   └── Long-Term Memory
│
├── RAG
├── Agent Routing
├── Multi-Agent Systems
├── Human-in-the-Loop
└── Guardrails & Security
Agent + Tools
```mermaid
flowchart LR
    U["User"]
    --> A["AI Agent"]
    --> R["Reasoning"]

    R --> T1["Web Search"]
    R --> T2["Database"]
    R --> T3["API"]
    R --> T4["Python"]
    R --> T5["Custom Tool"]

    T1 --> A
    T2 --> A
    T3 --> A
    T4 --> A
    T5 --> A

    A --> O["Final Response"]
```
Agent Routing
```mermaid
flowchart TD
    A["User Query"]
    --> B["Agent Router"]

    B --> C["RAG Agent"]
    B --> D["Web Search Agent"]
    B --> E["SQL / Database Agent"]
    B --> F["Code Agent"]

    C --> G["Result"]
    D --> G
    E --> G
    F --> G

    G --> H["Final Response"]
```
Multi-Agent Architecture
```mermaid
flowchart TD
    U["User Request"]
    --> S["Supervisor Agent"]

    S --> R["Research Agent"]
    S --> C["Coding Agent"]
    S --> D["Data Agent"]
    S --> W["Web Agent"]

    R --> S
    C --> S
    D --> S
    W --> S

    S --> V["Validation"]
    --> O["Final Response"]
```
AI Security & Guardrails
AI security is a dedicated part of my learning focus, especially for LLM and agentic systems.
Secure Agentic AI Pipeline
```mermaid
flowchart TD
    A["User Input"]
    --> B["Input Validation"]
    --> C["AI Agent"]
    --> D["Reasoning"]
    --> E["Permission Check"]
    --> F["Tool Selection"]
    --> G["Tool Execution"]
    --> H["Tool Result Validation"]
    --> I["LLM Response"]
    --> J["Output Validation"]
    --> K["Safety / Guardrails"]

    K --> L{"Safe?"}
    L -->|Yes| M["Final Response"]
    L -->|No| N["Block / Regenerate"]
```
Security Areas
Area	Focus
Prompt Security	Prompt injection and malicious instructions
Input Validation	Unsafe or unexpected inputs
Output Validation	Invalid or unsafe outputs
Tool Security	Restricting agent tools
Permission Control	Controlling agent actions
PII Protection	Sensitive information
Hallucination Control	Grounding responses
RAG Security	Untrusted retrieved content
Agent Security	Controlling autonomous behavior
Evaluation	Reliability and failure testing


Guardrails Mindset
User Input
    ↓
Input Validation
    ↓
Prompt / Agent
    ↓
Permission Check
    ↓
Tool Calling
    ↓
Tool Result Validation
    ↓
LLM Response
    ↓
Output Validation
    ↓
Safety Check
    ↓
Final Response
Tech Stack
Programming Languages
Python · Java · C++ · C · JavaScript · HTML · CSS · SQL
AI / Machine Learning
Machine Learning · Deep Learning · NLP · Computer Vision · Neural Networks · Model Evaluation · Data Preprocessing
Generative AI & LLM
LangChain · LangGraph · Groq · Hugging Face · Google GenAI · Mistral · RAG · Sentence Transformers · Vector Search · Tool Calling · Structured Output
Databases
MySQL · PostgreSQL · MongoDB · SQLite · Pinecone
Frameworks & Tools
Flask · FastAPI · Streamlit · Git · GitHub · VS Code · Linux · Jupyter · Docker · REST APIs
Featured Projects
CineSage — Movie Recommendation System
Tech: Python · FastAPI · Streamlit · TF-IDF · Machine Learning
A content-based movie recommendation system built using a dataset containing more than 45,000 films.
- Data cleaning and preprocessing
- TF-IDF based recommendation
- Genre-based recommendation
- Content similarity
- FastAPI backend
- Streamlit frontend
TaskBot — AI Powered Task Manager
Tech: Python · LangChain · Groq · SQLite · Streamlit
An AI-powered task management project exploring LLM interaction with application functionality through tools and structured workflows.
LLM
 ↓
Natural Language
 ↓
Tool / Function Execution
 ↓
SQLite
 ↓
Task Management
CropScan
Tech: Python · Deep Learning · Computer Vision
A hackathon project focused on crop health and disease detection using deep learning and computer vision concepts.
Competitive Programming
I practice Data Structures & Algorithms and problem solving.
- LeetCode
- Codeforces
Current DSA Focus
Arrays · Strings · Linked Lists · Stacks & Queues · Hashing · Recursion · Binary Search · Trees · Graphs · Greedy Algorithms · Dynamic Programming
GitHub Statistics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bhamniyaravi&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhamniyaravi&layout=compact&theme=tokyonight&hide_border=true" height="180"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=bhamniyaravi&theme=tokyonight&hide_border=true" />
</p>

Experience & Activities
Code4Crew — Team Leader
Participated in NexHack Hackathon 2025 as the team leader of Code4Crew, working collaboratively on an AI-focused project.
Workshops & Learning
SQL · Microsoft Excel · Linux · Web Development · Cloud Computing · AWS · Data Analytics · Professional Development
Certifications & Learning
- Deloitte Australia — Data Analytics Job Simulation
- SQL Workshop
- MS Excel Workshop
- Linux Workshop
- Web Essentials Workshop
- Cloud Computing / AWS Workshop
- Professional Development Workshop
Currently Exploring
Agentic AI
      ↓
LangGraph
      ↓
Multi-Agent Systems
      ↓
Tool Calling
      ↓
RAG
      ↓
LLM Evaluation
      ↓
AI Security
      ↓
Guardrails
      ↓
Production AI Systems
I am focused on building AI applications that are:
Reliable · Secure · Grounded · Tool-Aware · Scalable
My Development Philosophy
Build → Break → Debug → Learn → Improve → Repeat

I believe the best way to learn AI is by building real systems, understanding why they fail, and continuously improving them.
Let's Connect
<p align="center">
  <a href="https://github.com/bhamniyaravi">GitHub</a> ·
  <a href="https://www.linkedin.com/in/ravi-bhamniya-4aa4aa34a/">LinkedIn</a> ·
  <a href="https://leetcode.com/u/bhamniyaravi8/">LeetCode</a> ·
  <a href="https://codeforces.com/profile/bhamniyaravi8">Codeforces</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:1E3A8A,100:0F172A&height=120&section=footer" />
</p>

<p align="center">
  <b>AI & Data Science | Machine Learning | Deep Learning | Generative AI | Agentic AI | AI Security</b>
</p>
