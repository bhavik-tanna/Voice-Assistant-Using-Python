# Desktop Voice Assistant with Python

![Voice Assistant](https://user-images.githubusercontent.com/75237577/173243993-ca05aaff-22c9-4918-bc82-cdc4fc5534aa.png)

This repository contains a desktop voice assistant implemented in Python that utilizes speech recognition and text-to-speech capabilities. The voice assistant allows users to perform tasks such as launching applications and gathering information from AI models using API keys. This project aims to provide a simple and intuitive voice-controlled interface for various tasks, making it more convenient for users to interact with their desktops.

## Features

- **Voice Input**: The voice assistant supports speech recognition, enabling users to interact with their desktop by speaking commands.
- **Text-to-Speech**: The assistant uses text-to-speech technology to provide spoken responses to users' queries and actions.
- **App Launch**: Users can launch applications on their desktop by simply voicing the application's name.
- **AI Model Interaction**: The assistant can access AI models through API keys, allowing it to gather information or perform specific tasks.

## Getting Started

To use the voice assistant on your desktop, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

```bash
git clone https://github.com/your-username/desktop-voice-assistant.git
```

2. **Install Dependencies**: Install the required dependencies using `pip`.

```bash
pip install -r requirements.txt
```

3. **Add API Keys**: To enable AI model interaction, you'll need to obtain API keys for the specific AI services you want to use. Add your API keys to the configuration file (`config.json`) in the project root.

```json
{
  "api_keys": {
    "service_1": "YOUR_API_KEY_1",
    "service_2": "YOUR_API_KEY_2"
  }
}
```

4. **Run the Assistant**: Execute the main Python script to start the voice assistant.

```bash
python voice_assistant.py
```

5. **Speak Commands**: Once the voice assistant is running, start speaking commands. The assistant will process your speech and execute the corresponding actions.

## Supported Commands

The voice assistant currently supports the following commands:

- "launch [application_name]": Launch a specified application by its name.
- "information [topic]": Ask the assistant to gather information on a specific topic using the available AI models and API keys.

## Contributions

Contributions to this project are more than welcome! If you have any ideas for new features, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This project relies on external AI models, which might have usage restrictions or limitations. Ensure that you comply with the terms and conditions of the API services you use with this voice assistant.

---

We hope this voice assistant brings convenience and productivity to your desktop experience. If you encounter any issues or have any questions, please don't hesitate to reach out. Happy voice-controlling!
