
# 🗣️ Speech-to-Text Model  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Status](https://img.shields.io/badge/Status-Active-success)]()

The **Speech-to-Text Model** is a Python-based voice recognition system that listens to your microphone input and automatically types text into any active text editor or document.  
It also includes a **floating microphone icon** built with PyQt5 for starting and stopping the transcription process with a single click.

---

## 🚀 Features

✅ **Real-Time Speech Recognition** – Converts spoken English to text instantly.  
✅ **Command Support** – Special voice commands:  
   - `"next line"` → Adds a line break  
   - `"full stop"` → Adds a period  
   - `"delete"` → Deletes last word  
   - `"redo"` / `"undo"` → Redo or undo text changes  
   - `"next subtitle"` / `"title"` → Creates formatted headings  
   - `"stop"` → Terminates the program  
✅ **GUI Control** – Floating microphone icon to start/stop transcription.  
✅ **Automatic Formatting** – Applies bold and font size formatting to titles/subtitles.

---

## 🛠 Built With

- **Python 3.x**
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) – Speech-to-text processing  
- [PyAutoGUI](https://pypi.org/project/PyAutoGUI/) – Automating keyboard typing and formatting  
- [PyQt5](https://pypi.org/project/PyQt5/) – Floating microphone GUI  
- **Google Speech API** – For accurate speech recognition

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/SathishK-official/Speech-to-Text-Model.git
cd Speech-to-Text-Model

# Install dependencies
pip install -r requirements.txt
````

**Requirements:**

* Working **microphone**
* Python 3.8+
* Active internet connection (for Google Speech API)

---

## 📜 Usage

### ▶ Run via Floating Mic (GUI)

```bash
python app.py
```

* Click the mic icon to start/stop speech recognition.
* Drag the icon anywhere on your screen.

### ▶ Run Directly

```bash
python main.py
```

* Focus your text editor within **5 seconds**.
* Start speaking — the program will type your speech in real-time.

---

## 📸 Demo

### Floating Mic GUI

![Floating Mic GUI](img.png)



---

## ⚠ Notes

* **Internet Required** – Google Speech API requires an active internet connection.
* Works best in quiet environments for higher accuracy.
* Tested on Windows with MS Word, Notepad, and Google Docs.

---

## 🤝 Contributing

1. Fork this repository
2. Create a new branch (`feature/YourFeature`)
3. Commit your changes
4. Push to your branch and open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
