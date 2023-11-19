# Chat with FAQ Section

This objective is to create a chatbot using a **custom data source** and GPT-3.5 engine.  <br>  

Why custom data source?
* Relevancy of context <br>
* Information timeliness


In this demo app, this app chat with the Unifi Home FAQ document retrieved from the [website](https://unifi.com.my/support/faq): 
<br>
<br>

<u>Comparison</u> of responses_

| Official FAQ Document|Chat GPT | [App](https://faq-chatbot.streamlit.app/) - Custom Data Source |
| ----------  |---------|--------------------------|
| <img width="600px" src="./media/unifi_FAQ.JPG" alt="faq doc" />     |![](https://github.com/amirul-ic/chatbot/blob/main/media/chat_gpt.gif)  |![](https://github.com/amirul-ic/chatbot/blob/main/media/app.gif)            |

<br>

Click [here](https://faq-chatbot.streamlit.app/) to access the app.


The app can also be extended to personal book collections, enterprise knowledge banks, etc by replacing the documents in the 'data' folders accordingly. <br>
<br>
<br>
<br>
<br>
**Reference** <br>
The code used is based on the tutorial [here](https://blog.streamlit.io/build-a-chatbot-with-custom-data-sources-powered-by-llamaindex/).
