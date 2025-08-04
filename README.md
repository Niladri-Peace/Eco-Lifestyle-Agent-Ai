#  Eco Lifestyle Agent – IBM Watsonx RAG Project

This project implements an AI-powered Eco Lifestyle Agent using **IBM Watsonx.ai** and **Retrieval-Augmented Generation (RAG)**. It provides users with personalized, reliable advice on how to live more sustainably by answering natural language questions using a custom knowledge base.

---

##  Problem Statement – PS No. 6

Build an Eco Lifestyle Agent that empowers users to adopt a greener lifestyle through practical, local, and personalized suggestions using RAG. It should support queries such as:

- “How can I reduce plastic use at home?”
- “What are eco-friendly travel options in my city?”

---

##  Features

-  Personalized answers on sustainable living
-  Retrieves trusted info from uploaded documents (plastic waste, travel, recycling)
-  RAG-based response using IBM Granite + custom prompt templates
-  Natural language interface for easy interaction

---

## Technologies Used

- **IBM Watsonx.ai Studio**
- **IBM Cloud Lite Services**
- **RAG (Retrieval-Augmented Generation)**
- **Prompt Engineering**

---

##  Files Included

- `Eco lifestyle Agent.ipynb`: Main notebook with agent logic and sample queries
- Embedded knowledge documents (e.g., `plastic_waste_management.txt`, `green_travel.txt`)
- Prompt configuration and retrieval logic

---

##  Sample Query

```text
User: How can I reduce plastic use at home?

Agent:
Here are some tips to reduce plastic use at home:
- Use reusable cloth or jute bags instead of plastic.
- Avoid single-use plastic bottles or containers.
- Opt for metal or glass storage containers.
- Buy in bulk to reduce packaging waste.
