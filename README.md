# AI ChatBot (Terminal-Based) - Java

## Overview
This is a simple terminal-based AI chatbot developed in Java, utilizing the **Groq API** powered by the **LLaMA 3 AI model**. The chatbot takes user input from the terminal, sends it to the API, and retrieves a response from the AI model.

## Features
- Interactive terminal-based chatbot
- Uses **Groq API** for AI-powered responses
- Built with **Java** and **HTTP requests**
- Easy to use and modify

## Requirements
- Java Development Kit (**JDK 8 or higher**)
- Internet connection (to access the Groq API)

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repository-url/chatbot-java.git
   cd chatbot-java
   ```
   *(Replace with your actual repository URL if applicable.)*

2. **Compile the Java Program**
   ```sh
   javac ChatBot.java
   ```

3. **Run the Chatbot**
   ```sh
   java ChatBot
   ```

## Usage
1. **Start the chatbot** by running `java ChatBot` in the terminal.
2. **Enter your message** when prompted (`You:`).
3. **Receive an AI-generated response** from the chatbot (`Bot:`).
4. **Continue the conversation** or **exit** manually (by closing the terminal).

## Code Breakdown
- **`main()`**: Handles user input and continuously loops for interaction.
- **`chatbot(String message)`**: Sends user input to the Groq API and retrieves a response.
- **`extractContentFromResponse(String response)`**: Extracts AI-generated text from the API response.

## Configuration
### API Key
Replace the placeholder API key in the following line with your own key from Groq:
```java
String apiKey = "your_api_key_here"; // Replace with your Groq API key
```

## Notes
- Ensure you have a valid **Groq API key**.
- API calls may be **rate-limited** based on your subscription.
- The chatbot currently uses `llama3-8b-8192` as the AI model, but you can update this in the `model` variable.

## Future Improvements
- Add **error handling** for network failures.
- Enhance **response parsing** for more accurate output.
- Implement a **GUI-based chatbot**.

## Author
**Ayush Singh** - Intern at CODE-ALPHA

---

Enjoy chatting with your AI bot! 🚀

