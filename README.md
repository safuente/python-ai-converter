# python-ai-converter
Convert python code to C++ language. You can run the code in both language and the option to select between GPT and Claude models.

## Run code
Create a virtual env and install all the packages in requirements.txt:

    pip install -r requirements.txt

Create a .env file with the following content:
    
    OPENAI_API_KEY=<API_KEY>
    ANTHROPIC_API_KEY=<API_KEY>
    

OpenAI API key could be generated in the following way:
https://gptforwork.com/help/knowledge-base/create-openai-api-key
Anthropic API key could be generated in the following way:
https://www.merge.dev/blog/anthropic-api-key


Execute the following command:

    python python_ai_converter.py

