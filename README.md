# Cold-Email-Generator-RAG

💼 End-to-End Cold Email Generator
An intelligent system that automates the generation of personalized cold emails for job postings using Retrieval-Augmented Generation (RAG) techniques.

🔧 Key Features
Retrieval-Augmented Generation (RAG): Built a RAG pipeline using LLaMA-3 (via Groq) and LangChain to generate tailored cold emails for job postings.

Information Extraction via Prompting: Extracted job roles, required skills, and descriptions from scraped career page content using LLaMA-3, and structured the output into JSON for downstream use.

Semantic Search with ChromaDB: Employed ChromaDB as a vector store to perform semantic similarity search across a technical portfolio, ensuring relevance and personalization based on job requirements.

Personalized Email Generation: Combined job-required skills with a user’s background to prompt the LLM again for crafting a highly relevant cold email.

Streamlit Web App: Developed a responsive Streamlit app to accept job posting URLs and display generated emails in real time.


