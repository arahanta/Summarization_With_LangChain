# Text Summarization using Lanchain

This code snippet showcases text summarization using Lanchain. It encompasses the following functionalities:

1. Reading the API key from a file and setting the environment variable for the Google API.
2. Generating a summary for a given speech using the Langchain Google GenerativeAI model "gemini-pro".
3. Utilizing LLMChain to translate a precise summary of the speech to a specified language.
4. Summarizing a PDF document using Lanchain with chain type "stuff".
5. Summarizing large documents using Map Reduce.

## Usage Instructions

To use this code, follow the instructions below:

1. Set up the API key by reading it from a file and setting the environment variable for the Google API.
2. Define the speech text that needs to be summarized.
3. Run the code to generate summaries and translate them to different languages.

**Note:** Ensure that you have the required dependencies installed, such as langchain_google_genai, langchain, PyPDF2, and typing_extensions.
