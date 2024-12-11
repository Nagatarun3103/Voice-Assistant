# Voice Assistant in Python

This repository contains the source code for a Python-based voice assistant application. The script leverages speech recognition and text-to-speech technologies to perform various tasks, such as telling the time, telling jokes, playing music, and more.

## Features

- **Voice-based Authentication**: Authenticate users through a spoken password.
- **Task Automation**:
  - Open websites like YouTube and Instagram.
  - Tell jokes.
  - Play random songs from a specified directory.
- **Conversational Abilities**:
  - Respond to inquiries like its name or age.
  - Provide the current time.

## Getting Started

### Clone the Repository

Download or clone this repository to your local machine:

```bash
git clone https://github.com/Nagatarun3103/Voice_assi
```

### Prerequisites

Ensure you have Python 3 installed. Install the required dependencies using:

```bash
pip install -r requirements.txt
```

### Running the Application

To run the voice assistant:

```bash
python Voice_assi.py
```

### Example Usage

1. Start the assistant by running the script.
2. Speak commands, such as:
   - "What's your name?"
   - "What time is it?"
   - "Tell me a joke."
   - "Play a song."
3. The assistant will respond or perform the requested action.

## Customization

- **Password**: Modify the password for voice authentication in the `authenticate()` function.
- **Music Directory**: Update the path in the "play song" functionality to point to your music library.
- **Add Commands**: Enhance the assistant by adding more commands and their corresponding actions.

## Troubleshooting

- Ensure your microphone is configured correctly.
- Install the required dependencies listed in `requirements.txt`.
- Test the script in a quiet environment for accurate speech recognition.

## Issues and Contributions

If you encounter any issues, feel free to raise them in the issues tab. Contributions to improve the script are welcome through pull requests.

## Credits

Created by [Nagatarun3103](https://github.com/Nagatarun3103). Special thanks to the Python community for the amazing libraries that made this project possible.



