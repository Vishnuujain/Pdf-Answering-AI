# Chat with PDF

This Python project that allows you to chat with a chatbot about the PDF you uploaded. and generate a PDF transcript of the conversation. The project is built using Python and Streamlit framework.


## Installation

To run this project, please follow the steps below:

1. Clone the repository:

```shell
git clone "https://github.com/Vishnuujain/Pdf-Answering-AI"
cd Pdf-Answering-AI
```

2. Create and activate a conda virtual environment (optional but recommended):

```shell
conda create -n env1 python=3.10
conda activate env1
```

3. Install the dependencies from the `requirements.txt` file:

```shell
pip install -r requirements.txt
```

4. You will need a HUGGINGFACEHUB_API_TOKEN for this next step. To obtain one for free, got to https://huggingface.co/ and Sign Up for a free account. Then, go to Settings > Access Tokens. Create a New token. Then, create a file in this directory, name is `.env` and enter `HUGGINGFACEHUB_API_TOKEN = "token"`,  replacing `token` with your User Access Token. Save the `.env` file. The `.gitignore` file will ignore the `.env` for git operation.

## Running the Project

Once you have installed the required dependencies, you can run the project using Streamlit, which should have been installed with `requirements.txt`. Streamlit provides an easy way to create interactive web applications in Python.

To start the application, run the following command:

```shell
streamlit run app.py
```

This will start the Streamlit server and open the application in your default web browser..  

https://www.loom.com/share/eee0227d6e554582a8d09719d3a0c9d9?sid=2bc131e4-502d-496f-b8be-a12f37780284

### Git flow
`.gitit.sh` can be used for easy pushing updates to remote repo.  

Activate with:  
```shell
chmod +x .gitit.sh
```
Then, to add, commit, and push to remote repo:
```
./gitit.sh
```

## License

This project is licensed under the [MIT License](LICENSE).

