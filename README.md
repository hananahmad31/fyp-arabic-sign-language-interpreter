# 🤟 Real-Time Arabic Sign Language Interpreter for Learners

A real-time sign language translator designed to recognize Arabic Sign Language (ArSL) alphabet and convert it into readable text and speech. This inclusive tool is built to aid deaf and hard-of-hearing learners, promoting accessibility and better communication in educational environments.

---

## 🎯 Project Objective

To design and develop an AI-powered application that recognizes real-time alphabetic signs using computer vision and translates them into readable text and audio output. The app is tailored for educational purposes and is enriched with self-assessment and accessibility tools.

---

## 📚 Background

Deaf and hard-of-hearing students face barriers in traditional education due to limited access to sign language interpreters and tools. This project aims to provide:

- A low-cost, accessible real-time translator  
- Support for the Arabic Sign Language (ArSL) alphabet  
- Features that promote self-learning and independence

---

## 📌 Key Features

- 🔤 **Real-Time Alphabet Recognition:** Detects and interprets signs from the Arabic sign alphabet via webcam  
- 🗣️ **Text & Text-to-Speech Output:** Converts gestures into text and optionally into speech  
- 🧪 **Practice Mode:** Slow motion playback, side-by-side comparison with reference signs  
- 🧠 **ML-Based Prediction:** Uses deep learning models (TensorFlow) trained on ArSL dataset  
- 🎛️ **Accessibility Controls:** Includes adjustable font sizes, high-contrast modes, and simple UI  
- 📈 **Usage Analytics:** Tracks model accuracy, user progress, and feedback for improvement

---

## 🔍 Project Scope

1. Real-time sign recognition and translation to text/speech  
2. Enhanced accessibility through UI personalization and speech options  
3. User-centered design with support for practice and comparison  
4. Continuous learning via usage data, feedback, and model updates

---

## 🔧 Tools & Technologies

| Category            | Technologies Used                      |
|---------------------|----------------------------------------|
| Frontend            | Flutter                                |
| Backend & Auth      | Google Firebase (Auth, Firestore)      |
| Machine Learning    | TensorFlow, ARASL Dataset               |
| NLP & Text Support  | NLTK (Natural Language Toolkit)         |
| DevOps & Utilities  | Git, VS Code, Google Colab              |
| SE Methodology      | Software Engineering Design Practices   |

---

## 📦 Requirements

- The app must support:
  - Real-time recognition of Arabic sign letters via webcam  
  - Accurate mapping of signs to textual and vocal output  
  - Side-by-side sign comparison and slow-motion playback  
  - Basic practice exercises for self-assessment  

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed  
- Python environment (for training the ML model)  
- Firebase project setup  
- Pre-trained TensorFlow model based on ARASL dataset  

### Installation Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/sign-language-interpreter.git
   cd sign-language-interpreter
   ```

2. **Install Flutter Dependencies:**

   ```bash
   flutter pub get
   ```

3. **Setup Firebase:**

   Follow [FlutterFire documentation](https://firebase.flutter.dev/docs/overview/) to connect your Firebase project.

4. **Integrate ML Model:**

   Add your trained TensorFlow Lite model to the assets and load it using TensorFlow Lite Flutter plugin.

5. **Run the App:**

   ```bash
   flutter run
   ```

---

## 📊 Results & Improvements

- Achieved ~92% accuracy on real-time sign detection using ARASL dataset  
- Positive feedback from testing with real learners  
- Future updates planned:
  - Sentence-level recognition  
  - Support for full gesture-based communication  

---

## 🏁 Final Thoughts

This project is a significant step toward bridging the communication gap for deaf learners using technology. It can be extended to support full sign language conversations and integrated into educational platforms.

---

## 👥 Project Team

- **Hanan Ahmad**  
- **Usman**  
- **Mustaghees-ul-Hassan**

---

## 🤝 Contributions

Contributions, suggestions, and forks are welcome. Please open an issue or submit a pull request for improvements.

---

## 📄 License

This project is licensed under the MIT License.

---

**Made with 💙 using Flutter, Firebase, and TensorFlow**

