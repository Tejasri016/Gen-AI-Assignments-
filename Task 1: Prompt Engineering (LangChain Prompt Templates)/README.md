# 🚀 Mini Prompt Engine using LangChain

## 📌 Overview
This project demonstrates how to build a **dynamic and reusable prompt system** using LangChain.  
Instead of hardcoding prompts, we use **PromptTemplate** and **ChatPromptTemplate** to generate structured and flexible prompts.

---

## 🎯 Objective
- Replace hardcoded prompts with reusable templates  
- Build dynamic prompt systems  
- Design real-world LLM prompt pipelines  

---

## 🛠️ Tech Stack
- Python 🐍  
- LangChain  
- Groq (LLM)  

---

## 📚 Features Implemented

### ✅ Task 1: Basic PromptTemplate
- Created a reusable prompt template for simple explanations  

### ✅ Task 2: Multi-Input Prompt System
- Handled multiple inputs: `topic`, `audience`, `tone`  

### ✅ Task 3: Prompt Variations Engine
- Generated prompts in different styles:
  - Teaching  
  - Interview  
  - Storytelling  

### ✅ Task 4: ChatPromptTemplate
- Implemented role-based prompting:
  - Teacher  
  - Interviewer  
  - Motivator  

### ✅ Task 5: Input Validation
- Validated inputs and assigned default values  
- Ensured robustness of prompt system  

### ✅ Task 6: Prompt Generator Function
- Built a function to dynamically generate prompts based on style  

### ✅ Task 7: Template Reusability
- Used a single template with multiple inputs  
- Demonstrated scalability and flexibility  

---

## 🔄 Pipeline Flow
User Input → Validation → Prompt Template → Model → Output

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install langchain langchain-groq
```
2. Run the notebook in Jupyter/Colab
3. Enter your Groq API key when prompted

---

## 💡Key Learnings
- Importance of reusable prompt design
- Difference between PromptTemplate and ChatPromptTemplate
- Role-based prompting techniques
- Input validation in AI pipelines
- Building scalable prompt systems

---

## 🌟 Future Improvements
- Add UI for user input
- Integrate with web apps
- Support more prompt styles

---

## 🔗 Author

**Tejasri Somarouthu**

## 📢 Acknowledgement

This project is part of my **GenAI Internship – Prompt Engineering Assignment using LangChain**.
