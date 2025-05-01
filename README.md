# NIRAMAYA: A RAG-Based Prototype for Crisis Response AI 🤖🌍

This project demonstrates a lightweight Retrieval-Augmented Generation (RAG) pipeline using LangChain and GPT-4, built as part of the NIRAMAYA initiative — an AI vision for collective wellbeing during health and humanitarian crises.

> **NIRAMAYA (निरामयाः)**: From the Sanskrit prayer “Sarve Santu Niramaya” — *May all be free from illness.*
>
> "Sarve santu niramaya" in Hindi is "सर्वे सन्तु निरामयाः". It means "May all be free from illness" or "May all be well." The full mantra, of which this phrase is part, is
> "ॐ सर्वे भवन्तु सुखिनः सर्वे सन्तु निरामयाः सर्वे भद्राणि पश्यन्तु मा कश्चिद् दुःखभाग् भवेत् ॐ शान्तिः शान्तिः शान्तिः".
> This translates to "May all be happy, may all be free from illness, may all see what is auspicious, may no one be overtaken by any suffering, Om Peace, peace, peace!". 
> This prototype is a step toward compassionate, context-aware AI for global resilience.

---

## 💡 What It Does

✅ Loads a curated knowledge base (COVID-19 symptoms, vaccine FAQ, mental health tips)  
✅ Embeds the documents using OpenAI’s `text-embedding-ada-002`  
✅ Stores vectors in FAISS and retrieves top-k relevant chunks  
✅ Sends retrieved context + user query to GPT-4  
✅ Generates grounded, trustworthy answers in real time

---

## 🔧 Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI GPT-4 API](https://platform.openai.com/)
- [FAISS (in-memory vector store)](https://github.com/facebookresearch/faiss)
- Google Colab

---

## 📁 Files

| File                                | Description                                           |
|-------------------------------------|-------------------------------------------------------|
| `NIRAMAYA_RAG_Prototype.ipynb`     | Colab notebook — full demo and walkthrough            |
| `README.md`                         | This file — overview, instructions, credits           |

---

##  Quick Start

1. Clone or open the notebook in [Colab](https://colab.research.google.com/)
2. Set your OpenAI API key when prompted
3. Run the cells to:
   - Load knowledge base
   - Embed documents
   - Ask health-related questions
   - Generate grounded answers from GPT-4

---

## 💡 Example Queries
1. What are the symptoms of COVID-19?

2. What are common side effects of COVID-19 vaccines?

3. How can I manage stress during the pandemic?



---

##  Why It Matters

In 2020, misinformation and confusion spread faster than the virus itself.  
**This prototype is my tribute** — to reimagine AI that’s not just intelligent, but *intentional* and *empathetic*.

---

## 🙌 Acknowledgments

- Inspired by RAG patterns shared by [Shivani Virdi](https://www.linkedin.com/in/shivani-virdi/)
- Built with guidance from OpenAI + LangChain tutorials

---

## 📫 Let’s Connect

Open to contributors, collaborations, and ideas:  
[LinkedIn → Akanksha Sinha](https://www.linkedin.com/in/akankshasinha247)

---

