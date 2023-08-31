# Chat-with-PDF-Chatbot
The process of creating your own PDF Chatbot using open-source technologies. With the power of conversational AI, you'll be able to enhance your interaction with PDF documents using just your CPU.To get started, I am using the Langchain framework for text preprocessing and handling chains. This framework provides robust capabilities for processing text, ensuring that your chatbot can understand and respond effectively to your queries.

Sentence Transformers, a powerful embedding model, to enable intelligent understanding and retrieval of information. By incorporating this model, our chatbot will be able to grasp the context of your queries and provide accurate and relevant responses.

For efficient storage and retrieval of vectorized information, we'll utilize the Chroma DB, a high-performance vector database. This will ensure quick access to the relevant information and enhance the overall responsiveness of your chatbot.

To give your chatbot its language capabilities, we'll make use of the Lamini LM 738M, a large language model known for its natural language processing capabilities. With this model as the backbone, your chatbot will be able to provide insightful and contextually relevant responses to your queries.

To create a user-friendly interface, we'll employ Streamlit, a web framework that allows for easy interaction with your PDF Chatbot. With its intuitive design and interactive features, you'll be able to seamlessly engage with your chatbot and explore its capabilities.

The knowledge and skills to build your own PDF Chatbot using open-source technologies

## How to run the Project in the local machine:
1. Clone the repo using command
#### git clone https://github.com/Kishordevaragudi/Chat-with-PDF-Chatbot.git
2. create a virtual environment in local machine
#### conda create -p venv python==3.10 -y
3. Install the python packages using txt file
#### pip install -r requirements.txt
4. Install git lfs in your local machine
#### git lfs install
6. clone the repo of LLM model (Lamini LM 738M)
#### git clone https://huggingface.co/MBZUAI/LaMini-T5-738M
7. Run the file using streamlit
#### streamlit run chatbot_app.py

# Output results
![Screenshot 2023-08-31 104805](https://github.com/Kishordevaragudi/Chat-with-PDF-Chatbot/assets/105155723/2e2a5c9b-d748-4a61-9561-6260be7b6405)

