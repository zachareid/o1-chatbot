O1 Chatbot
==========

O1 Chatbot is a simple web-based chat interface that allows users to interact with OpenAI's language models. It provides a clean, dark-themed UI for sending messages and receiving responses from the selected AI model.

Features
--------

-   Chat interface with support for user and AI messages
-   Selection between two OpenAI models: o1-preview and o1-mini
-   Dark mode UI for comfortable viewing
-   Responsive design that works on both desktop and mobile devices
-   Simple code block formatting in messages

Setup
-----

1.  Clone this repository or download the HTML file.
2.  Open the HTML file in a text editor.
3.  Replace `<code>` in the `Authorization` header with your actual OpenAI API key:

    javascript

    Copy

    `Authorization: "Bearer YOUR_API_KEY_HERE",`

4.  Save the file and open it in a web browser.

Usage
-----

1.  Select the desired model from the dropdown menu.
2.  Type your message in the text area at the bottom of the page.
3.  Click the "Send" button or press Enter to send your message.
4.  The AI's response will appear in the chat window above.

Note
----

This chatbot is set up with a system prompt that instructs the AI to act as an expert coding assistant. It will attempt to provide complete code files and one-shot solutions to maximize productivity.

Security Warning
----------------

Be sure not to commit or share the HTML file with your API key included. Keep your API key confidential to prevent unauthorized use.

License
-------

This project is open source and available under the [MIT License](LICENSE).
