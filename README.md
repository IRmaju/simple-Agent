# 🤖 AI Greeting Agent

This is a simple AI-powered greeting agent that responds to user greetings using Google Gemini API. It replies with pre-defined responses for greetings and informs the user if they ask other questions.

## 📌 Features

- Responds to greetings like *hi, hello, salam* with "Salam from  Wajeeha Qadir Abbasii!"
- Says farewell when the user says *bye, goodbye, khuda hafiz*
- If asked anything else, it responds: *"Wajeeha is here just for greeting, I can't answer anything else, sorry."*
- Uses **Google Gemini API** for AI functionality

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)

```sh
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate    # For Windows
```

### 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up API Key

Get a **Google Gemini API Key** from [Google AI Studio](https://aistudio.google.com/) and add it to an `.env` file:

```
GEMINI_API_KEY=your_api_key_here
```

### 5️⃣ Run the Agent

```sh
python main.py
```

## 🛠 Project Structure

```
📂 agent_project
├── 📄 main.py       # Core script for the agent
├── 📄 .env         # Stores the API key
├── 📄 README.md    # Project documentation
├── 📄 requirements.txt  # Dependencies
└── 📂 agents       # Contains agent logic
```

## 🎯 Example Usage

```
$ python main.py
Please enter your question: hi
Salam from Wajeeha Qadir Abbasi!
```

## 🤝 Contributing

Feel free to fork this repository, submit issues, or contribute enhancements!

## 📜 License

MIT License © 2025 Wajeeha Qadir Abbasi


