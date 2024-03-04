# PHIBOG534_Bcl2401_Bcl2401-e_PhiillipBogopane_Chatbot
HTML Structure:**
  - The HTML structure defines a chat container (`<div class="chat-container">`) with a chat box (`<div class="chat-box">`), an input field (`<input type="text">`), and two buttons: one for sending messages and one for clearing the chat history.

2. **CSS Styles:**
  - The CSS styles define the appearance of the chat interface, including the layout, colors, and animations.
  - The chat messages are styled differently for the bot's messages (`bot-message`) and the user's messages (`user-message`), with different background colors.

3. **JavaScript Functionality:**
  - The `getBotResponse()` function is asynchronous and serves as a placeholder for retrieving bot responses. Currently, it always returns a default response ("I'm sorry, I couldn't find information about that.").
  - The `sendMessage()` function is called when the user clicks the "Send" button. It retrieves the user's input, displays it in the chat box, sends it to the `getBotResponse()` function, and displays the bot's response after a short delay.
  - The `clearChat()` function is called when the user clicks the "Clear" button. It clears all chat messages from the chat box.

4. **Functionality Overview:**
  - Users can type messages in the input field and send them to the chatbot by clicking the "Send" button.
  - The chatbot responds to user messages with pre-defined responses (or a default response if no matching response is found).
  - Users can clear the chat history by clicking the "Clear" button.

5. **Limitations and Future Improvements:**
  - The chatbot's functionality is limited to displaying pre-defined responses and does not include actual integration with APIs or databases for retrieving health information.
  - Future improvements could involve integrating the chatbot with NLP APIs for understanding user input and providing more relevant responses, as well as incorporating real health-related information from external sources.

 **How to use App:**
6.To get response enter input health.
   
Overall, the provided code creates a basic chatbot interface that allows users to interact with the chatbot and receive responses. However, it serves as a foundation for further development and integration with more advanced features and external resources
