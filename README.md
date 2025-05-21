# 🤖 AskAI - Your Personal AI Chat Companion

AskAI is a sleek Android app built with Kotlin that lets you interact with OpenAI's GPT-3 model in real time. Simply type your queries and get intelligent, instant responses powered by the OpenAI API.

---

## 🚀 Key Features

- **Real-time AI responses:** Chat with GPT-3 using the latest OpenAI API.
- **User-friendly interface:** Clean and intuitive UI for easy question input and response viewing.
- **Network aware:** Checks for internet connectivity before sending requests.
- **Loading indicator:** Shows progress while fetching AI responses.
- **Clear conversation:** Easily reset your input and response fields.
- **Exit confirmation:** Prevent accidental app closures with a confirm dialog.

---

## 🛠️ Tech Stack

| Component          | Technology                         |
|--------------------|----------------------------------|
| Language           | Kotlin                           |
| Networking         | OkHttp, Coroutines               |
| UI Framework       | Android Views, Material Design   |
| API                | OpenAI GPT-3 Completions         |

---

## ⚙️ How It Works

1. User inputs a question and taps **Send**.
2. App checks network connectivity.
3. If online, sends a POST request to OpenAI API with user prompt.
4. Receives GPT-3's generated text response asynchronously.
5. Displays the AI response on screen.
6. User can clear inputs or exit with confirmation.

---

## 🔧 Setup & Run

1. Clone the repo.
2. Open in Android Studio.
3. Replace `API_KEY` in `MainActivity.kt` with your OpenAI API key.
4. Build and run on your Android device or emulator.

---

## License 📄
Copyright 2023 Haider Qadir

---
