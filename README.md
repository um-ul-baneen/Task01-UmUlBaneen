#  AI/Python Mini Projects

A collection of beginner-friendly AI/Python mini-projects covering rule-based logic, machine learning, security tools, and AI-based recognition.

---

## 1. Rule-Based AI Chatbot
**File:** `rule_based_chatbot.py`

A simple chatbot that responds to predefined user inputs using if-else logic.

**Functionality:**
- Handles greetings (`hi`, `hello`, `hey`)
- Responds to small talk (`how are you`, `your name`, `help`, `weather`, `thanks`)
- Runs in a continuous loop, taking user input each time
- Exits cleanly on commands like `bye`, `exit`, `quit`
- Falls back to a default response for unrecognized input

**Run:**
```bash
python rule_based_chatbot.py
```

---

## 2. Data Classification Using AI
**File:** `data_classification.py`

A basic supervised learning model trained to classify data using the Iris dataset.

**Functionality:**
- Loads and previews the Iris dataset (150 samples, 3 classes)
- Splits data into training (80%) and testing (20%) sets
- Trains a K-Nearest Neighbors (KNN) classifier
- Evaluates the model and prints accuracy + classification report

**Run:**
```bash
python data_classification.py
```

**Requirements:** `scikit-learn`, `pandas`

---

## 3. Random Password Generator
**File:** `password_generator.py`

A tool that generates a random, complex password based on user-specified length.

**Functionality:**
- Prompts the user for a desired password length (minimum 4)
- Validates the input
- Generates a random password using letters, numbers, and symbols
- Uses Python's built-in `random` and `string` modules

**Run:**
```bash
python password_generator.py
```

---

## 4. Text Recognition (OCR)
**File:** `text_recognition.py`

A basic text recognition tool using a pre-trained OCR engine.

**Functionality:**
- Generates a sample image containing text
- Runs Tesseract OCR (via `pytesseract`) to extract text from the image
- Displays the original text vs. the recognized text side by side
- Checks whether the OCR output matches the original

**Run:**
```bash
python text_recognition.py
```

**Requirements:** `pytesseract`, `Pillow`, and Tesseract OCR installed on the system
```bash
sudo apt install tesseract-ocr
pip install pytesseract pillow
```

---

## Overall Requirements
```bash
pip install scikit-learn pandas pytesseract pillow
```

## Skills Demonstrated
- Control flow & decision-making logic
- Data handling & supervised learning basics
- Module usage & string manipulation
- Using AI libraries & understanding model outputs
