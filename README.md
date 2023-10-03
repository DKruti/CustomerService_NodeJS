# CustomerService_NodeJS
customer support system , openAI, node.js, crawl,embedding 

## Introduction

- To satisfy the customer's needs using Leveraging Artificial Intelligence for enhanced support, the application is developed.
- Used OpenAI API_key and Org_ID to use the OpenAI API. For that, an account is created, the key and org_id are set, and the balance is credited to use the API.
- If your API_key is compromised, you can create a new key and use it in the `.env` file. You will receive an email from OpenAI that your key is compromised and has been disabled.
- The objective is to develop a web-based application for website-related queries. If information is available on that website, it prints the answer; otherwise, it prints "Don't know."
- Key Technology: ChatGPT by OpenAI, Node.js.

## Prerequisite Implementation in Node.js

**NOTE:** Work on VScode [editor] terminal only; otherwise, sometimes it gives an error.

1. Do not require creating a new virtual environment every time. If you created venv successfully in homework-1, then directly write the command:
   ```shell
   workon <your venv name>
2. Check your node and npm is installed or not using **node -v** and **npm -v** respectively. If not then install it using **brew install node** command.

## Implementation of Customer support system
To implement the customer support system, follow these steps:

1. Utilize the code provided in index.js, getResult.js, and index.module.css, which have been used for the pet name project.

2. Make necessary changes in your package.json file as shown in .pdf screenshot

3. Ensure that your jsconfig.json and next.config.js files are configured properly as shown in .pdf screenshot

## Executing the Project
**Step 1: Crawling the Website
To crawl a website, execute the following command:**
**npm run crawl**
This command is defined in the package.json file as "crawl": "python3 crawldata.py", which automatically runs crawldata.py.

**Step 2: Embedding**
Before embedding, ensure you have exported the openai_api_key to avoid errors. Then, run the following command:
**npm run embedding**
In the package.json file, the "embedding" key has the value "python3 embedding.py", which automatically runs crawldata.py.

## Testing the Application
For web-based output using Node.js, execute the following command:
**npm run dev**
The application will run on **http://localhost:3000**
To interact with the application, input a name and click the "Generate Output" button to receive a name description.
## ouputs are in output files folder


