# 🌟 Live Translator

![Live Translator Banner](assets/banner.png)

**Live Translator** is a sleek and user-friendly web application that allows users to translate text between multiple languages seamlessly. With features like auto-detecting source languages, voice input/output, dark mode, and responsive design, Cool Translator offers an engaging and accessible translation experience for both desktop and mobile users.

## 🚀 Features

- **Multi-Language Support:** Translate between a wide range of languages.
- **Auto-Detect Source Language:** Automatically identifies the language of the input text.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Interactive UI:** Smooth animations and transitions enhance user experience.
- **Copy to Clipboard:** Easily copy translated text with a single click.
- **Voice Input:** Speak directly into the translator using your microphone.
- **Voice Output:** Listen to the translated text being read aloud.
- **Dark Mode:** Toggle between light and dark themes for better accessibility.

## 📸 Screenshots

![Light Mode](assets/screenshot-light.png)
*Light Mode Interface*

![Dark Mode](assets/screenshot-dark.png)
*Dark Mode Interface*

## 🛠️ Technologies Used

- **HTML5 & CSS3:** Structuring and styling the application.
- **JavaScript (ES6):** Handling functionality and API interactions.
- **[MyMemory Translation API](https://mymemory.translated.net/doc/spec.php):** Facilitating text translations.
- **Web Speech API:** Enabling voice input and output features.
- **Responsive Design Principles:** Ensuring optimal display across devices.

## 📥 Installation

Follow these steps to set up **Live Translator** locally on your machine.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Live-translator.git
```

### 2. Navigate to the Project Directory

```bash
cd cool-translator
```

### 3. Open the Application

Simply open the `cool_translator.html` file in your preferred web browser.

- **Option 1:** Double-click the `cool_translator.html` file.
- **Option 2:** Right-click the file and choose "Open with" followed by your browser.

> **Note:** For full functionality, especially voice features, it's recommended to run the application over a local server.

### 4. (Optional) Run a Local Server

If you have Python installed, you can run a simple HTTP server:

- **For Python 3:**

  ```bash
  python -m http.server 8000
  ```

- **For Python 2:**

  ```bash
  python -m SimpleHTTPServer 8000
  ```

Open your browser and navigate to `http://localhost:8000/cool_translator.html`.

## 📝 Usage

1. **Enter Text:**
   - Type or paste the text you want to translate into the input textarea.

2. **Select Languages:**
   - **Source Language:** Choose the language of the input text or select "Auto-Detect" to let the application identify it automatically.
   - **Target Language:** Choose the language you want to translate the text into.

3. **Translate:**
   - Click the "🔄 Translate" button or press `Shift + Enter` to initiate the translation.

4. **Copy Translated Text:**
   - Click the "📋 Copy" button to copy the translated text to your clipboard.

5. **Voice Input:**
   - Click the "🎤 Speak" button and speak into your microphone. The spoken words will be transcribed and translated automatically.

6. **Voice Output:**
   - After translation, click the "🔊 Listen" button to hear the translated text spoken aloud.

7. **Toggle Dark Mode:**
   - Click the "🌙 Dark Mode" button to switch between light and dark themes.

## 🔧 Configuration

**Cool Translator** uses the [MyMemory Translation API](https://mymemory.translated.net/doc/spec.php) for translating text. By default, it uses the free public endpoint. For enhanced performance or higher usage limits, consider hosting your own instance or exploring premium translation APIs like Google Translate or DeepL.

### Changing the API Endpoint

If you decide to use a different translation API, update the `translateText` function in the `cool_translator.html` file with the new API endpoint and adjust the request parameters accordingly.

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance **Cool Translator**, follow these steps:

1. **Fork the Repository**

2. **Create a New Branch**

   ```bash
   git checkout -b feature/LiveTranslator
   ```

3. **Commit Your Changes**

   ```bash
   git commit -m "Add some feature"
   ```

4. **Push to the Branch**

   ```bash
   git push origin feature/LiveTranslator
   ```

5. **Open a Pull Request**

Provide a clear description of your changes and the motivation behind them.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📞 Contact

For any questions or suggestions, feel free to reach out:

- **Email:** speedyfriend433@example.com
- **GitHub:** [@speedyfriend433](https://github.com/speedyfriendree)

## 🎉 Acknowledgments

- **[MyMemory Translation API](https://mymemory.translated.net/doc/spec.php):** For providing a free translation service.
- **Web Speech API:** For enabling voice input and output features.
- **Inspiration:** Thanks to the open-source community for their invaluable resources and tools.

---

© 2024 [speedyfriend433](https://github.com/speedyfriend433). All rights reserved.
