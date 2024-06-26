# PDF-Chatbot
PDF query chatbot with Streamlit and generative AI - Integrated language learning tools and a custom AI model for "Langchain" query generation. Optimized for user experience and functionality, merging language learning with advanced AI capabilities.


Technologies and libraries used:
- ●	Python
- ●	Langchain
- ●	OpenAi
- ●	Hugging Face - LaMini-T5-738M
- ●	Streamlit
- ●	PyPDF2


How it works:
- ➔	PDF Loading: The app reads multiple PDF documents and extracts their text content.
- ➔	Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.
- ➔	Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.
- ➔	Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.
- ➔	Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.


-Initial page
<img width="302" alt="Picture1" src="https://github.com/tchandak03/PDF-Chatbot/assets/83765905/05016a8b-226f-462d-b775-9ccc15500838">

-Uploading the pdf
<img width="302" alt="Picture2" src="https://github.com/tchandak03/PDF-Chatbot/assets/83765905/c43723f4-0cdb-4b37-9b8c-c91801993dbb">

-Asking the question
<img width="302" alt="Picture3" src="https://github.com/tchandak03/PDF-Chatbot/assets/83765905/49a07ddf-2d4e-4d5c-9468-6009998f274c">

-Chatbot generating the answer
<img width="302" alt="Picture4" src="https://github.com/tchandak03/PDF-Chatbot/assets/83765905/36477801-d853-4934-9274-473fc55b9894">

