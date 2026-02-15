<img width="1468" height="468" alt="Capture1" src="https://github.com/user-attachments/assets/4abbdc7f-4ee4-49a6-99d3-eed323836656" /># 🧠 Local RAG System using LlamaIndex + HuggingFace

A fully local Retrieval-Augmented Generation (RAG) system built using **LlamaIndex**, **HuggingFace Transformers**, and **Sentence Transformers**.

This project allows you to:
- Load documents from a local directory
- Convert them into vector embeddings
- Store them in a vector index
- Query them using a local LLM
- Generate context-aware responses

Everything runs locally — no OpenAI API required.
------------------------------------------------------------------

## About the company

One Energy is the largest installer and operator of wind-generated electricity directly supplied to customers from outside the grid in North America.

One Energy builds, owns, and operates major electrical infrastructure for industrial energy users on their side of the meter. One Energy is already building the customer-centric power grid of the future. One Energy is building Utility 2.0. 

A Utility 2.0 company:
- enables, operates in, and improves upon a decentralized power grid.
- provides a physical solution that operates on the power grid.
- embraces the sustainable development of their company and their products.
- is not entitled to monopolistic protections – of any kind.
- innovates to ensure the cost of delivered energy goes down over time.

---

## Sample conversations

<img width="1468" height="468" alt="Capture1" src="https://github.com/user-attachments/assets/15894227-132f-4d71-aa20-9ff39fce5d0f" />
<img width="1470" height="442" alt="Capture2" src="https://github.com/user-attachments/assets/78972d65-21d5-452f-b3d2-3e35528ed80c" />
<img width="1463" height="446" alt="Capture3" src="https://github.com/user-attachments/assets/8418b0f4-7f07-4dd5-a223-b60ad05961d4" />
<img width="1467" height="437" alt="Capture4" src="https://github.com/user-attachments/assets/4ec86939-10eb-4fdf-9f23-60e28a8de7f0" />
<img width="1471" height="431" alt="Capture5" src="https://github.com/user-attachments/assets/15042a13-1ec4-483d-8eaf-b867e1a479f9" />
<img width="1463" height="425" alt="Capture6" src="https://github.com/user-attachments/assets/63e49968-b557-480d-b862-5f96c5e855a5" />
<img width="1466" height="427" alt="Capture7" src="https://github.com/user-attachments/assets/ad53e4bf-a177-484f-a0a3-cb71742b24e3" />
<img width="1471" height="536" alt="Capture8" src="https://github.com/user-attachments/assets/3fcae353-a895-4ae8-9670-a5ff4c797f2c" />


---

## 🚀 Features

- ✅ Local document ingestion
- ✅ Embedding using sentence-transformers
- ✅ Vector index creation with LlamaIndex
- ✅ Local HuggingFace LLM integration
- ✅ Query engine for intelligent responses
- ✅ Works on CPU (no GPU required)
- ✅ No paid APIs

--------

## Key Features

- Responds to customer inquiries using state-of-the-art OpenAI language models
- 24/7 availability, ensuring customers can get assistance anytime
- Has multilingual support, making it accessible to a global customer base
- Can be integrated with existing customer support systems for a seamless user experience.
- Can be extended to be a wind turbine maintenance support chatbot
- Simple code, just 10 lines for the custom training and 10 lines for the chatbot UI


---

## 🏗️ Tech Stack

- Python 3.10+
- LlamaIndex
- HuggingFace Transformers
- SentenceTransformers
- PyTorch

----

## Benefits of Chatbot

- Improved customer service response time, with quick and accurate responses.
- Reduced workload on human agents, allowing them to focus on more complex tasks.
- Cost savings due to fewer human resources needed for support.
- Enhanced customer experience, leading to higher customer satisfaction and retention.

---

## 📂 Project Structure
    project/
    │
    ├── docs/ # Folder containing input documents
    │ ├── sample.txt
    │ └── ...
    │
    ├── main.py # Main script to build index
    ├── requirements.txt
    └── README.md
    
----

## Next steps

- Expanding the chatbot's capabilities to handle more complex queries.
- Gathering more training data for the chatbot
- Continuous monitoring and updates to keep the chatbot relevant and efficient.
- Potential opportunities to integrate the chatbot with other company systems, such as CRM or sales platforms.
- Translate all the training data into other languages like Spanish, so that the chatbot can converse in other languages
- Add maintainance manuals to training data, so that the chatbot can aid in troubleshooting wind turbines or other machinery

---

## How to run the code

- Add your API key to the api_secret.py file
- Create a folder named "docs" in the same path as your code
- Add all the training documents to the "docs" folder
- Install all the necessary libraries
- Run the python notebook
- Click on the URL that Gradio creates
- Have fun

---

## 💡 Why This Project Matters

- This project demonstrates:
  - Retrieval-Augmented Generation (RAG)
  - Vector search systems
  - Local LLM deployment
  - Embedding models
  - Index persistence
  - AI system architecture

- These skills are highly relevant for:
  - AI Engineer
  - LLM Engineer
  - NLP Engineer
  - GenAI Developer
  - ML Engineer roles

## 🧠 Learning Outcomes

- By building this project, you understand:
  - Difference between embeddings & LLMs
  - Causal LM vs Seq2Seq LM
  - Chunking strategies
  - Context windows
  - Vector similarity search
  - Local vs API-based LLM systems

## 👨‍💻 Author

# Sarfraz Khan
- Aspiring AI Engineer | Machine Learning Enthusiast
