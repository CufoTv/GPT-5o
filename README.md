# GPT-5o ChatBot

GPT-5o is a **JavaScript-based AI chatbot** that uses a **Markov chain algorithm** to generate **context-aware and dynamic responses**. The chatbot learns from previous conversations stored in the browser's localStorage, providing increasingly relevant and varied answers.

---

## Features

- **Offline Operation**: Runs entirely in the browser, no server required.
- **Markov Chain AI**: Generates responses based on learned patterns from previous conversations.
- **Context-Aware Responses**: Reads past chat history to improve answer relevance.
- **Dynamic Answers**: Each response is unique, evolving slightly every time.
- **Local Storage**: Saves chat history for continuity and context awareness.
- **Theme Toggle**: Switch between **dark** and **light** modes.
- **Chat Management**: Option to delete all previous conversations.
- **Custom Avatars**: User and bot avatars (`profile/user.jpg` and `profile/gpt-5o.jpg`).

---

## Folder Structure

```

GPT-5o/
│
├─ profile/
│   ├─ user.jpg          # User avatar
│   └─ gpt-5o.jpg        # Bot avatar
│
├─ index.html            # Main HTML file with embedded JS/CSS
└─ README.md             # Project documentation

````

---

## Setup & Usage

1. **Clone the repository**:

```bash
git clone https://github.com/CufoTv/GPT-5o.git
cd GPT-5o
````

2. **Open `index.html` in a browser** (Chrome, Firefox, or Edge recommended).

3. **Start chatting**: Type a message and press **Enter** or click the **send** button.

4. **Theme toggle**: Click the **light\_mode** icon to switch between dark/light mode.

5. **Delete history**: Click the **delete** icon to remove all chat history.

---

## Optional: Run on Local Server

For full functionality or if you plan to expand the project:

**Python 3 HTTP server:**

```bash
cd GPT-5o
python3 -m http.server 8080
```

**Node.js (http-server):**

```bash
npm install -g http-server
cd GPT-5o
http-server -p 8080
```

Then open `http://localhost:8080` in your browser.

---

## License

This project is open-source. You may modify and use it under the terms of the **Apache-2.0 License**.

---
