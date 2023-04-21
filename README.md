# Guide to extract terms and defination.

## Description
This repository helps you to create chatGPT app with streamlite and llama_index. 
This app will extract terms and defination from the given contennt.

Reference: https://gpt-index.readthedocs.io/en/latest/guides/tutorials/terms_definitions_tutorial.html

## Prerequisite
1) Anaconda (Download from <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html"> here</a>
2) Llama Index
3) Open AI API key (get from <a href="https://platform.openai.com/account/api-keys">here</a>
## Instruction to run project

1) Create conda enviroment

```sh
conda create --name myenv
```

2) Install requirements.txt

3) Run command below

```sh
streamlit run streamlit_demo.py
```

It will open browser with localhost

4) Add your API key in field.
![image](https://user-images.githubusercontent.com/81793485/233581471-1801744a-c3cb-469c-9aec-d91f6fea7262.png)

5) Go to 'Upload/Extract Terms' tab and add file or type sample information. Then click on 'Extract Terms and Defination' button.
![image](https://user-images.githubusercontent.com/81793485/233581837-6d81c43f-8e8f-41ec-9c9c-a428fc2b2a51.png)

6) Then go to 'Query Terms' tab and enter your query related your given input and click on 'Initialize Index and Reset Terms' button. You will get answer for your query.
![image](https://user-images.githubusercontent.com/81793485/233582439-0c366d2f-e978-499d-98dd-81eeb235bf35.png)

