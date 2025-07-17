# Sendbird AI Agent

**Sendbird AI Agent** is an enterprise-grade, omnichannel AI solution designed to revolutionize customer service.
Unlike traditional chatbots, Sendbird AI Agents understand intent, maintain context, take action, and adapt over time, delivering natural, human-like conversations that resolve complex issues and escalate seamlessly when needed. ([sendbird.com](https://sendbird.com/ai-agent?utm_source=chatgpt.com))

## Features

- **Omnichannel support**: Integrates with SMS, email, WhatsApp, in-app chat, web, and social messaging platforms, ensuring your AI agent is always available where your customers are. ([sendbird.com](https://sendbird.com/ai-agent?utm_source=chatgpt.com))
- **Contextual understanding**: Maintains conversation context across channels, allowing the AI agent to pick up the conversation exactly where the customer left off.
- **Proactive engagement**: Anticipates customer needs and initiates conversations on preferred channels before issues arise.
- **Unified customer insights**: Transforms omnichannel conversations into unified customer insights to inform smarter business decisions. ([sendbird.com](https://sendbird.com/?utm_source=chatgpt.com))
- **Seamless integrations**: Connects with customer support software like Salesforce, Zendesk, Notion, and Google Drive, allowing the AI agent to be trained using your existing content. ([sendbird.com](https://sendbird.com/ai-agent/builder?utm_source=chatgpt.com))

## Getting started

To integrate Sendbird AI Agent into your application, follow these steps:

1. **Create a Sendbird account**: Sign up at [Sendbird Dashboard](https://dashboard.sendbird.com/).
2. **Set up your application**: Create a new application in the dashboard to obtain your Application ID.
3. **Configure AI agent**: In the dashboard, navigate to the AI Agent section to create and configure your AI agent, obtaining the necessary Agent ID.
4. **Integrate SDK**: Depending on your platform (iOS, Android, Web), integrate the appropriate Sendbird AI Agent SDK into your application.
5. **Initialize AI agent**: Use the Application ID and Agent ID to initialize the AI agent within your application.

## Cloning the repository

```bash
git clone https://github.com/sendbird/sendbird-ai-agent.git
cd sendbird-ai-agent
```

## Installation

### JavaScript/React (Web)

1. Navigate to the `js/` directory for web/React projects.
2. Install dependencies using npm or yarn:

   ```bash
   cd js/live-example
   npm install
   # or
   yarn install
   ```

3. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

### Android

1. Follow the instructions in `android/README.md` for Gradle setup.
2. Example (see README for details):

   ```kotlin
   implementation("com.sendbird.sdk:ai-agent-messenger:1.+")
   ```

### iOS

1. Follow the instructions in `ios/README.md` for Swift Package Manager setup.
2. Example (see README for details):

   - Add the package dependency in Xcode:
     ```
     https://github.com/sendbird/sendbird-ai-agent-messenger-ios.git
     ```

**Note:**
- There is no Python dependency or `requirements.txt` for this project.
- Please refer to the platform-specific README files (`android/README.md`, `ios/README.md`, `js/README.md`) for complete integration instructions.

## Repository structure

This repository contains platform-specific implementations of the Sendbird AI Agent:

- **iOS**: Located in the `ios` directory, this includes the Swift Package Manager (SPM) compatible SDK for integrating the AI agent into iOS applications.
- **Android**: Located in the `android` directory, this includes the necessary components for Android integration.
- **Web**: Located in the `js` directory, this includes JavaScript components for web integration.

Each platform-specific directory contains its own README with detailed integration instructions.

## Documentation

For comprehensive documentation, including API references and advanced configuration options, visit the [Sendbird Documentation](https://sendbird.com/docs).

## Support

If you encounter any issues or have questions, please open an issue in this repository or contact [Sendbird Support](https://sendbird.com/contact).

## License

This project is licensed under the [MIT License](LICENSE).

---

For more information on Sendbird's AI Agent platform and its capabilities, visit the [official website](https://sendbird.com/ai-agent).
