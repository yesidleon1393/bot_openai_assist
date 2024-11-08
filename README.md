# WhatsApp AI Assistant Bot Based in (BuilderBot.app)
![image](https://github.com/user-attachments/assets/a64d5b5b-c579-4473-974b-316c302f4d64)

This project creates a WhatsApp bot that integrates with an AI assistant using BuilderBot technology - thanks - Leifer Mendez. It allows for automated conversations and intelligent responses powered by OpenAI's assistant API.

## Features

- Automated conversation flows for WhatsApp
- Integration with OpenAI's assistant API
- Agnostic to WhatsApp provider
- Automated responses to frequently asked questions
- Real-time message receiving and responding
- Interaction tracking with customers
- Expandable functionality through triggers

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
