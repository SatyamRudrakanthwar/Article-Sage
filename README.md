Article Sage 📈  

Overview  

Article Sage is an advanced research assistant designed for analyzing and extracting insights from online news articles. By processing URLs, it enables users to ask questions about the content and get precise answers with source references. This tool is ideal for researchers, journalists, and individuals seeking to delve deep into multiple articles efficiently.  

---

Features  

- URL-Based Content Analysis:  
  - Input up to 3 URLs for article analysis.  
  - Fetch and process content from the provided links.  

- Text Splitting and Embedding:  
  - Splits content into manageable chunks for efficient querying.  
  - Generates embeddings using OpenAI embeddings for accurate retrieval.  

- Intelligent Query System:  
  - Use FAISS (Facebook AI Similarity Search) for quick and scalable document retrieval.  
  - Ask questions about the articles and receive detailed answers with references.  

- Streamlit-Based User Interface:  
  - Simple and intuitive UI for data input, processing, and querying.  

---

Tech Stack  

- Programming Language: Python  
- Libraries:  
  - Streamlit: User interface  
  - LangChain: Text processing and retrieval chain  
  - FAISS: Vector database for storing and retrieving embeddings  
  - OpenAI: Embeddings and language models  

---

 Installation  

Prerequisites  
- Python 3.8+  
- OpenAI API Key  

Steps  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/Article-Sage.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd Article-Sage  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Create a `.env` file and add your OpenAI API key:  
   ```bash  
   OPENAI_API_KEY=your_openai_api_key  
   ```  

5. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  

---

Usage  

1. Enter URLs:  
   - Input up to 3 news article URLs in the sidebar.  

2. Process Articles:  
   - Click the "Process URLs" button to fetch and process content.  

3. Ask Questions:  
   - Enter your query in the main input box to get an AI-generated response.  

4. View Sources:  
   - The tool also provides references to the articles used for generating the response.  

---

Example Output  

Input  
Question: "What is the impact of recent technology advancements?"  

Output  
Answer:  
"Recent advancements in AI technology have improved healthcare diagnostics and revolutionized customer support systems with AI-driven chatbots."  

Sources:  
1. [Source 1](https://example1.com)  
2. [Source 2](https://example2.com)  

---

Project Structure  

```
Article-Sage/  
├── app.py                     # Main Streamlit application  
├── requirements.txt           # Dependencies  
├── .env                       # Environment variables (user-created)  
├── faiss_store_openai.pkl     # Saved FAISS vector store  
└── README.md                  # Documentation  
```  

---

Limitations  

- Accuracy depends on the quality and relevance of the input URLs.  
- The tool may not function well with inaccessible or invalid links.  
- Limited by OpenAI API's token constraints and processing limits.  

---

Future Enhancements  

- Support for more than 3 URLs at a time.  
- Add multilingual support for non-English articles.  
- Improve query results by integrating advanced summarization techniques.  
- Add an option to export results as a report.  

---

Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Add feature-name"  
   ```  
4. Push to the branch:  
   ```bash  
   git push origin feature-name  
   ```  
5. Submit a pull request.  

---

Contact
If you have any questions or suggestions, feel free to reach out.

--- 
