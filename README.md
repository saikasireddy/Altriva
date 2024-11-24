# **Altriva: AI-Powered Medical Assistant**
[![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-brightgreen)](https://streamlit.io)  
[![LangChain](https://img.shields.io/badge/Powered%20by-LangChain-blue)](https://langchain.com)

## **Overview**
**Altriva** is an AI-powered medical assistant that tackles critical challenges in healthcare accessibility, information overload, and self-care guidance. Leveraging state-of-the-art AI technologies, Altriva enables users to access reliable health information, manage minor health concerns, and reduce unnecessary strain on healthcare systems.

---

## **Key Features**
- **Symptom Checker**: Get fact-based, conversational answers to medical queries.
- **Document Retrieval AI**: Access trustworthy medical insights from curated knowledge bases.
- **Empathetic Guidance**: Designed to provide user-friendly advice free from complex jargon.
- **Advanced Framework**: Powered by LangChain and FAISS for efficient document search.
- **Intuitive Interface**: Built with Streamlit for an interactive user experience.

---

## **Problem Statement**
Altriva aims to resolve four major issues in healthcare:
1. **Limited Access**: Many people struggle to access accurate and comprehensive healthcare information.
2. **Information Overload**: Online health information is often contradictory and unverified.
3. **Lack of Self-Care Guidance**: There is limited knowledge of safe remedies for minor health issues.
4. **Overburdened Healthcare Systems**: Minor concerns consume critical resources in hospitals and clinics.

---

## **Technologies Used**
- **Python**: Core programming language.
- **Streamlit**: For building interactive web applications.
- **LangChain**: Framework for building AI-driven applications.
- **FAISS**: Vector-based similarity search.
- **HuggingFace Transformers**: Embedding models like `sentence-transformers/all-mpnet-base-v2`.
- **Llama Models**: Used for conversational AI responses.

---

## **Installation**
### **Prerequisites**
- Python 3.8 or later
- Virtual Environment (Optional but recommended)

### **Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Altriva.git
   cd Altriva
2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
3.Install dependencies:
```bash
pip install -r requirements.txt
4.Run the application:
bash
streamlit run MedicalChatbot.py
### **How to Use**
Launch the app in your browser after running the command.
Type your medical question into the input box.
Receive AI-generated responses based on your query.
View supporting source documents for detailed insights.
### **Folder Structure**
'''bash

.
├── MedicalChatbot.py        # Main chatbot script
├── Project_9.ipynb          # Jupyter Notebook for experiments
├── requirements.txt         # List of dependencies
├── faiss_index/             # FAISS index for document retrieval
└── README.md                # Documentation
### **Future Enhancements**
Integration with real-time medical APIs.
Multilingual support to serve diverse populations.
Personalized health advice based on user preferences.
Enhanced knowledge base with additional medical datasets.

### **Contributors**
- **Sai Manikanta Kasireddy**  
  [GitHub Profile](https://github.com/saikasireddy)


### **License**
This project is licensed under the MIT License.

### **Acknowledgments**
Streamlit and LangChain for enabling rapid development.
Open-source communities for their incredible AI tools and frameworks.
markdown

---

### **Common Markdown Formatting Guidelines**
1. Use `#` for headings (e.g., `#`, `##`, `###`).
2. Use `-` or `*` for bullet points in lists.
3. Use triple backticks (\`\`\`) for code blocks.
4. Separate sections with a blank line for better readability.
5. Test formatting using GitHub's Markdown preview.


