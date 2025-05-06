# Geopolitical Research And Analysis Using The World Bank API

### Abstract:
This notebook demonstrates a dynamic use of generative models to access to World Bank data, using a human friendly interface and a free chat.
The notebook here provides a chatbot that you to ask any information from the World Bank data base, manipulate it and present it in graphs, tables or free text, according to your own choice.

Here we make a use of the Gemini models family and the Google AI-Studio.

### Usage:
A demonstration of the notebook is available here.

For a general use, run all cells and then in the last cell you should have a conversation prompt. Follow the instructions provided in the conversation and in the Markdown cell above it, and ask for whatever economical data you desire. For example:

Prompt: "Give me the GDP per capita of the USA, UK and Canada, from 2010-2020, and plot it all in a graph."

### How AI is used to make it possible?
The system uses several AI agents to process the user requests, interact with the WB database API and perform farther operations and analysis.

The first AI agent handles your request and answer it (once it gets the data). It calls behind the scenes another AI agent that translates your prompt into a structured format that matches the WB API, and yet another AI agent to fetch the data from the WB API. The agents comunicate between each other in a clever way, to make sure that your request is fulfiled as best as possible, even if you didn't provide the most accurate names (for example, you can say "The Aussie state" instead of "Australia" and the system will understand). You can also specify how you want the results to be presented to you: As a graph? a short textual summary? structured output of your choice? You name it.

In addition, per your request, farther analysis can be done, such as normalizing the results, subselection and more.

### Key functionality:
##### The notebook demonstrates the following functionalities:
* Interacting with external APIs.
* Prompt engineering.
* Few-shot prompting.
* Structured outputs.
* Context caching.
* Gen AI evaluation.
* Function calling.
* AI Agents.
