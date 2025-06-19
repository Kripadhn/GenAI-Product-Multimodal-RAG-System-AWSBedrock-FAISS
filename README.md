# GenAI-Product-Multimodal-RAG-System-AWSBedrock-FAISS
<H2><B> Title </B></H2> Build a Multimodal RAG System using AWS Bedrock and FAISS
<H2><B> Description </B></H2> This project aims to design and implement a Multimodal Retrieval-Augmented 
Generation (RAG) system for a restaurant aggregator app, enhancing its capability to
deliver precise food recommendations tailored to individual preferences and dietary
needs, utilizing both textual and visual data.


<H2><B> Approach </B></H2>
Data Reading and Preprocessing:
<br>
● Data Storage: Utilize Amazon S3 for scalable and reliable object storage of the
collected data and read the images and metadata.
<br>
Data Processing:
<br>
● Image Data: Use Anthropic Claude-Sonnet model to generate image descriptions
<br>
Vector Database:
<br>
● Storage and Retrieval: Use Amazon Titan Embeddings and FAISS for storing and
efficiently retrieving vectorized data, enabling fast and scalable search capabilities for
the recommendation engine.
<br>
Recommendation Engine:
<br>
● Utilizing Anthropic Claude Sonnet Multimodal Model: To create conversational
chatbot and generate recommendations from Vector DB results.
<br>

# Code Structure

![image](https://github.com/user-attachments/assets/5c968eb1-82e7-47b0-9284-31050eaf9b2f)
