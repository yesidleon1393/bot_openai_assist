# WhatsApp AI Assistant Bot Based in (BuilderBot.app)
![image](https://github.com/user-attachments/assets/a64d5b5b-c579-4473-974b-316c302f4d64)

This project creates a WhatsApp bot that integrates with an AI assistant using BuilderBot technology - thanks - Leifer Mendez. It allows for automated conversations and intelligent responses powered by OpenAI's assistant API.

### Features
- Automated conversation flows for WhatsApp: Create dynamic, multi-step conversations to guide users effectively.
- Integration with OpenAI's assistant API: Leverage OpenAI’s models to generate intelligent, human-like responses for better customer engagement.
- Agnostic to WhatsApp provider: Easily adaptable to various WhatsApp providers, enhancing flexibility and integration capabilities.
- Automated responses to frequently asked questions: Reduce response times by addressing common inquiries instantly.
- Real-time message receiving and responding: Ensure instant replies for a seamless user experience, ideal for support and lead engagement.
- Interaction tracking with customers: Track each interaction to analyze user behavior and improve future responses.
- Expandable functionality through triggers: Customize actions based on specific triggers, enabling tailored automation.

### Additional Features
- Natural Language Understanding (NLU): Enhanced NLU capabilities to interpret user intent and provide more context-aware responses.
- Sentiment Analysis: Analyze the user's tone and sentiment in real-time, adjusting responses based on mood or urgency.
- Multi-Language Support: Allow for multilingual conversations, automatically detecting and responding in the user’s preferred language.
- Customizable Response Templates: Set up predefined response templates for common queries, ensuring consistent and professional communication.
- Smart Escalation to Human Agents: Automatically hand off conversations to human agents when the AI encounters complex or unresolved queries.
- Analytics Dashboard: Gain insights into chatbot performance with analytics on response times, customer satisfaction, and conversation flow efficiency.
- Scheduled Messages and Reminders: Send automated reminders or scheduled follow-ups to engage users at the right time.
- Data Storage and Conversation Logs: Store conversation histories for compliance, training, or performance review purposes.
- Personalized Recommendations: Use user data and interaction history to suggest personalized products, services, or content.
- Opt-in Data Collection: Collect user consented data (e.g., email, preferences) for personalized future interactions and follow-ups.

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```
   pnpm install
   ```
3. Set up your environment variables in a `.env` file:
   ```
   PORT=3008
   ASSISTANT_ID=your_openai_assistant_id
   ```
4. Run the development server:
   ```
   pnpm run dev
   ```

### Using Docker (Recommended)

This project includes a Dockerfile for easy deployment and consistent environments. To use Docker:

1. Build the Docker image:
   ```
   docker build -t whatsapp-ai-assistant .
   ```
2. Run the container:
   ```
   docker run -p 3008:3008 --env-file .env whatsapp-ai-assistant
   ```

This method ensures that the application runs in a consistent environment across different systems.

## Usage

The bot is configured in the `src/app.ts` file. It uses the BuilderBot library to create flows and handle messages. The main welcome flow integrates with the OpenAI assistant to generate responses.

## Documentation

For more detailed information on how to use and extend this bot, please refer to the [BuilderBot documentation](https://builderbot.vercel.app/).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact
Helmut Yesid Lizarazo
https://synergysolutions.space
