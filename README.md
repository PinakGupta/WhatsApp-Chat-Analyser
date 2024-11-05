# 📊 WhatsApp Chat Analyser

Welcome to the **WhatsApp Chat Analyser**! This tool allows you to gain insights from your WhatsApp chat history by analyzing messages, activity trends, and various other metrics.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## 🌟 Introduction
The WhatsApp Chat Analyser is designed to process exported WhatsApp chat data and provide meaningful statistics and visualizations. This tool helps you understand patterns in your conversations, such as your most active days, the most frequently used words, and much more.

## ✨ Features
- **Message Analysis**: Number of messages sent and received.
- **Activity Trends**: Daily, weekly, and monthly activity trends.
- **Word Frequency**: Most frequently used words in the chats.
- **Response Times**: Average response times.
- **Participant Analysis**: Analysis of contributions from each participant in group chats.

## 🛠 Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/whatsapp-chat-analyser.git
    cd whatsapp-chat-analyser
    ```
2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage
After setting up the environment, follow these steps to analyze your WhatsApp chats:

1. Export your WhatsApp chat to a text file and place it in the project directory.
2. Run the chat analyser:
    ```bash
    python analyse_chat.py --file chat.txt
    ```
3. View the generated analysis reports and visualizations in the `output/` directory.

## 📊 Examples
Here are some examples of the analyses you can perform:

- **Message Frequency Over Time**: Identify your busiest chatting periods.
- **Top Words**: See which words you and your friends use the most.
- **Response Times**: Find out how quickly participants respond to messages.

## 💻 Technologies Used
- **Python**: For data processing and analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For creating visualizations.
- **NLP Libraries**: For natural language processing tasks.

## 🤝 Contributing
We welcome contributions! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your commit message"
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements
Special thanks to the developers and contributors who made this project possible. Your support and feedback are invaluable.

---

Feel free to explore, use, and contribute to this project. Happy analyzing! 📈
