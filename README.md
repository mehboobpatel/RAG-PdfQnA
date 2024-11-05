# Retrieval Augmented Generation (RAG) for chatbots
RAG enabled Chatbots using [LangChain](https://www.langchain.com) and [Databutton](https://databutton.com/login?utm_source=github&utm_medium=avra&utm_article=rag)
![](https://github.com/avrabyt/RAG-Chatbot/blob/main/thumbnail.webp)

- For the front-end : `app.py`
- PDF parsing and indexing : `brain.py`
- Indexed are stored over session state 

Oversimplified explanation : (**Retrieval**) Fetch the top N similar contexts via similarity search from the indexed PDF files -> concatanate those to the prompt (**Prompt Augumentation**) -> Pass it to the LLM -> which further generates response (**Generation**) like any LLM does. **More in the blog!**

**Blog Post - [Here](https://medium.com/databutton/why-your-next-ai-product-needs-rag-implemented-in-it-9ee22f9770c8)**

**YouTube video - [Here](https://youtu.be/Yh1GEWqgkt0)**

To get started quickly, you can use the “Chat with PDF” [template](https://databutton.com/new?templateId=pt-x2Rh7dEYwIuCxXaR) within Databutton 🚀

> Alternatively, you can use [Streamlit](https://streamlit.io) to build and deploy! In that case few changes such as `st.secrets` needs to be implemented!
