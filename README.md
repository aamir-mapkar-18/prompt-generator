# prompt-generator
A tool to generate OpenAI compatible training data out of unstructured sources such as audio recordings, video recordings or conversation transcripts.

## Setup and Use
1. Setup a Virtual Environment
2. Install the packages from requirements.txt
3. Generate an OpenAPI key
4. Create a file name .env. Insert the below in the file:
    ```
    FLASK_APP=app
    FLASK_ENV=development
    OPENAI_API_KEY=<OPEN_API_KEY>
    ```
5. Start the app using `flask run`
