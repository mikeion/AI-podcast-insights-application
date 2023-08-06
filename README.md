# Podcast Summarization Dashboard

## Description

The [Podcast Summarization Dashboard](https://ai-podcast-insights.streamlit.app/) is an application designed to assist busy podcast enthusiasts in discovering intriguing episodes efficiently. By generating a personalized weekly newsletter, users can gain summaries of each podcast episode released during the week. This newsletter includes details about the guest, main topics discussed, and key highlights from the episode.

You can find a link to the hosted application here: [https://ai-podcast-insights.streamlit.app/](https://ai-podcast-insights.streamlit.app/).

This project was written as part of my role as a Teaching Assistant for the following CoRise course: [Building AI products with OpenAI](https://corise.com/go/building-ai-products-with-openai-MWKY3).

## Features

- **Episode Summaries:** Get concise summaries of episodes to decide which ones to dive into.
- **Guest Information:** Learn more about the guest for each episode.
- **Key Highlights:** Discover the main points and highlights of each episode at a glance.
- **Weekly Newsletter:** A round-up of the week's podcast episodes in a digestible format.

## Setup and Installation

To set up and run the application:

1. Clone the repository:
   ```
   git clone [Your Repository URL]
   ```

2. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the app:
   ```
   python podcast_frontend.py
   ```

## Approach

The development of this application is divided into three main parts:

1. **Information Extraction:** Using OpenAI's LLM and a Speech to Text model to transcribe and extract relevant details from podcasts.
2. **Backend Deployment:** Using a simple cloud provider, the information extraction functionality runs on-demand.
3. **Front-end Deployment:** Allows users to experience the end-to-end functionality of the app.

## Contributions

Contributions, issues, and feature requests are welcome! Feel free to check the [issues](link-to-your-issues-page) page.

## License

This project is licensed under the MIT license. See LICENSE for details.
