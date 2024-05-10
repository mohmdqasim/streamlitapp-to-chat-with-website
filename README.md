# streamlitapp-to-chat-with-website

A streamlit Application to ask from Multiple Documents
The application is live at this [link](https://appapp-to-chat-with-website-jgbbb3u4q5hsfmzqbwpnrx.streamlit.app/)

This application uses the OpenAI GPT-3 to create the embeddings and then use those Embeddings to ask from the documents.
On this application, you can upload multiple documents and then click "Process" to create the embeddings of the documents and then you can ask the questions.

To run this application locally, follow the following steps:
1. Clone this repo.
2. Install the requirements using the `pip install -r requirements.txt` command.
3. Create an `.env` file and paste the OpenAI API key there `OPENAI_API_KEY=<API_KEY_HERE`
4. Use the `streamlit run app.py` to run the application.
