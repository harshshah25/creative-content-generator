# creative-content-generator

### Project Overview

Creative Content Generator is an intelligent content generation application designed to empower users to create dynamic and engaging content based on their input. By leveraging the power of the LLAMA2-7B model, a state-of-the art Large Language Model (LLM), users can generate essays, poems, blogs, or jokes tailored to their requirements. With modularity and versatility at its core, the application ensures flexibility and ease of use, making it a perfect tool for 
students, writers, marketers, and content creators. 

This project utilizes key frameworks and tools such as LangChain, Streamlit, and sentence-transformers, among others, to streamline interaction between the user and the model. The application runs efficiently with the LLAMA2-7B model deployed locally via ctransformers and uses prompt engineering for fine grained control over the outputs. For this project, the focus is on the LLAMA-2 7B model, a versatile LLM available on Hugging Face. 

**Setting up the project:**
1. Create a virtual Python environment: 
conda create -p venv python==3.9 -y 
2. Activate the conda environment: 
conda activate venv/ 
3. Create a requirements.txt file in your working directory with the following 
libraries: 
sentence-transformers 
uvicorn 
ctransformers 
langchain 
python-box 
streamlit 
4. Install all the libraries from requirements.txt: 
pip install -r requirements.txt
5. Launch the application:
streamlit run app.py 
