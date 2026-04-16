# 🌐 Azure Translator Pro

A beautiful, professional translation web app powered by Microsoft Azure Translator API. Deployed on GitHub Pages for free, with zero server costs.
---
## ✨ Features
* 🚀 **Instant Translation** – Powered by Azure AI Translator
* 🎨 **Modern UI** – Glassmorphism design with smooth animations
* 🔒 **Secure** – API key stored locally in your browser
* 📱 **Responsive** – Works across all devices
* 🌍 **Multi-language Support** – 16+ languages supported
* ⚡ **Fast Performance** – No backend, direct API calls
* 💾 **Persistent Credentials** – Stored via localStorage
* 📋 **Clipboard Support** – Copy translated text easily
* ⌨️ **Keyboard Shortcut** – Press `Ctrl + Enter` to translate
---

## 🎯 Live Demo
👉 **Try it here:**
https://pappoobalti.github.io/Language-translator
---

## 🛠️ Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling (Flexbox + Grid + Animations)
* **JavaScript (ES6+)** – Logic & API handling
* **Azure Translator API v3.0** – Translation engine
* **Font Awesome** – Icons
* **GitHub Pages** – Hosting

---

## 📋 Prerequisites

To use this app, you need:

* A **Microsoft Azure account**
* An **Azure Translator resource (F0 free tier)**

---

## 🔑 Getting Azure API Credentials

### 1. Create Azure Account

* Go to: https://portal.azure.com
* Sign up (free tier includes credits)

### 2. Create Translator Resource

* Search for **Translator** in Azure Portal
* Click **Create → Translator**
* Configure:

  * **Region:** `global` (recommended)
  * **Pricing Tier:** `F0 (Free)`
* Click **Create**

### 3. Get API Keys

* Open your Translator resource
* Navigate to **Keys and Endpoint**
* Copy:

  * API Key (Key 1 or Key 2)
  * Region (e.g., `global`, `eastus`)

---

## 🚀 Usage

### 🌍 Online (GitHub Pages)

1. Open the live app
2. Enter:

   * Azure API Key
   * Region
3. Click **Save Credentials**
4. Enter text
5. Choose languages
6. Click **Translate** or press `Ctrl + Enter`

---

### 💻 Local Setup

```bash
# Clone repository
git clone https://github.com/pappoobalti/Language-translator.git

# Navigate into folder
cd Language-translator

# Open in browser
open index.html
```

💡 Tip: Use VS Code Live Server for better development experience.

---

## 📁 Project Structure

```
Language-translator/
│── index.html        # Main UI
│── style.css         # Styling
│── script.js         # App logic
│── assets/           # Icons / images
```

---

## 🔐 Security Note

* API keys are stored in **localStorage**
* No backend = no server-side exposure
* Never share your API key publicly

---

## ⚠️ Limitations

* Requires internet connection
* API usage limited by Azure free tier
* No offline translation support

---

## 🌟 Future Improvements

* 🌐 Auto language detection
* 🎤 Voice input & speech translation
* 📚 Translation history
* 🔄 Language swap button
* 🌙 Dark/Light theme toggle

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 💡 Acknowledgements

* Microsoft Azure Translator API
* Open-source community
* GitHub Pages for free hosting

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🧑‍💻 Share with others

---

## 👨‍💻 Author

Developed with ❤️ by **@pappoobalti**
