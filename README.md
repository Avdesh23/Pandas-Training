A simple interactive chatbot built using Python that runs in Google Colab or Jupyter Notebook. This project demonstrates basic input/output handling and conditional logic to simulate a conversation.

## 🚀 Features

* 💬 Interactive chat in terminal / notebook
* 🤖 Predefined responses (hello, sports, etc.)
* 🔁 Continuous conversation loop
* ❌ Exit option to stop chatbot
* 🧠 Beginner-friendly logic

## 🛠️ Technologies Used

* Python
* Google Colab / Jupyter Notebook

## 📦 Installation & Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Open the notebook in **Google Colab** or Jupyter Notebook

3. Run the code cell

4. Start chatting with the bot 💬

## ▶️ Example

```
🤖 Chatbot Started! Type 'exit' to stop.

You: hello  
Bot: Hi there! 👋  

You: how are you  
Bot: I'm just a program, but I'm doing great! 😄  
```

## 📂 Project Structure

```
├── chatbot.ipynb
└── README.md
```

## 🧩 Code Snippet

```python
def chatbot():
    print("🤖 Chatbot Started! Type 'exit' to stop.\n")

    while True:
        user_input = input("You: ")

        if user_input.lower() == "exit":
            print("Bot: Goodbye! 👋")
            break

        elif "hello" in user_input.lower():
            print("Bot: Hi there! 👋")

        elif "how are you" in user_input.lower():
            print("Bot: I'm just a program, but I'm doing great! 😄")

        elif "sports" in user_input.lower():
            print("Bot: I love sports! Which one do you like? ⚽🏏🏀")

        else:
            print("Bot: You said ->", user_input)

chatbot()
```
## 🔮 Future Improvements

* 🧠 Add AI/NLP-based responses
* 💾 Store chat history using Pandas
* 🌐 Convert into a web-based chatbot
* 🎯 Customize for sports event platform

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and improve it.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

* Your Name

---

⭐ If you like this project, don't forget to give it a star!
