# Resume Parser using Spacy NLP Library with Streamlit Integrated

Resume analyses have been around for decades now. Having a well-balanced and aesthetic resume can make or break your career. A personalized resume analyzer helps us evaluate and maintain a proper resume that might help us get a job in top MNCs.
In this project, we explain the tools that help analyze resumes and provide better feedback to increase the skills we are lacking and also change the resume pattern to stay one step ahead of others.

# Base Paper

* [Resume Parser with Natural Language Processing](https://www.researchgate.net/publication/313851778_Resume_Parser_with_Natural_Language_Processing)

# Methodology

## Streamlit

Streamlit is a small and easy web framework that helps us build beautiful websites.
The main reason for using Streamlit is its user-friendly interface — no need for prior knowledge of HTML, CSS, or JavaScript.

Streamlit is mostly used for deploying machine learning models without external cloud integrations.
Some applications include:

* Deploying ML and DL models
* Building frontends for Python code
* Viewing output locally in the browser

## Resume Parser

A resume parser is an NLP model used to extract key information from resumes such as personal details, education, experience, and skills.
We train the NLP model using a dataset to efficiently manage and process resumes sent electronically.

Resume parsers scan, analyze, and extract data important to recruiters, allowing them to search and match candidate profiles effectively. They are low-cost and essential for modern HR systems.

References

* [How to Build a Resume Parser using Python – GeeksforGeeks](https://www.geeksforgeeks.org/project-how-to-build-a-resume-parser-using-python/)
* [Streamlit Documentation](https://docs.streamlit.io/library/get-started/main-concepts)

# How to Execute?

Before execution, ensure you have the following prerequisites installed:

* Anaconda
* Python
* Code Editor (VS Code or PyCharm)

 Anaconda

Anaconda is a package manager that allows data engineers to create multiple environments and install libraries easily.
Download: [https://www.anaconda.com/](https://www.anaconda.com/)

 Python

Python is a popular programming language known for its readability and large community support.
Download: [https://www.python.org/downloads/](https://www.python.org/downloads/)

 Code Editor

A code editor allows writing, running, and debugging code efficiently.
Recommended editors:

* [Visual Studio Code](https://code.visualstudio.com/Download)
* [PyCharm](https://www.jetbrains.com/pycharm/download/#section=windows)

# How to Create a New Environment and Configure Jupyter Notebook

An environment is a collection of libraries required for a project.
Creating separate environments avoids version mismatches between projects.

Example:

* Project A: TensorFlow 2.4, Keras 2.4
* Project B: TensorFlow 2.6, Keras 2.6

To prevent conflicts, create a new environment for each project.



 Steps to Create an Environment in Anaconda

1. Type:

   ```
   conda create -n <env_name>
   ```

   Example:

   ```
   conda create -n myenv
   ```
2. Type `y` to confirm environment creation.
3. Activate the environment:

   ```
   conda activate myenv
   ```
4. Install required libraries:

   ```
   pip install <library_name>
   ```
5. To install multiple libraries at once:

   ```
   pip install -r requirements.txt
   ```
6. Navigate to the project directory:

   ```
   cd <project_path>
   ```
7. To configure Jupyter Notebook in the new environment:

   ```
   conda install -c conda-forge jupyterlab
   conda install -c anaconda python
   ```

Now Jupyter Notebook will work within your new environment.

# Steps to Execute

Note: Make sure to add the installation path to your system environment variables.

1. Install all required software.
2. Open Anaconda Prompt.
3. Create a new environment:

   ```
   conda create -n project_1
   conda activate project_1
   ```
4. Navigate to the project folder:

   ```
   cd A:\project\AI\Completed\project_name
   ```
5. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
6. To train your own model, use `lstm.ipynb`.
7. Run the main file:

   ```
   python main.py
   ```

# Data Description

No external dataset was used in this project.
External links in the code are provided to build a recommendation system that suggests courses to users based on their resume score.

# Issues Faced

1. Errors while installing specific libraries.
2. Python version mismatches (recommended: Python 3.8 or latest).
3. Missing environment variable paths in editors like VS Code.



