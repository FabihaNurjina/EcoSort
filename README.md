# ♻️ EcoSort

**EcoSort** is an AI-powered waste classification web application built with **HTML, CSS, JavaScript, TensorFlow.js, and Google Teachable Machine**.

The project uses a machine learning image classification model to identify whether everyday items are **biodegradable or recyclable**, encouraging responsible waste segregation and environmental awareness.

>  **Sort Smart. Recycle Right. Protect Our Planet.**

##  About the Project

EcoSort was created to explore how **Artificial Intelligence can be applied to real-world environmental problems**.

The application uses a machine learning model trained with **Google Teachable Machine**. When the user starts the application and allows camera access, EcoSort captures frames from the webcam and analyzes them using the trained model.

The predicted category and confidence score are then displayed in real time.

The goal is to make waste sorting more **interactive, accessible, and engaging** while encouraging people to think more carefully about how they dispose of everyday waste.

##  Features

-  AI-powered waste classification
-  Real-time webcam-based prediction
-  Machine learning model trained with Google Teachable Machine
-  Classifies items as biodegradable or recyclable
-  Displays prediction confidence
-  Environmental awareness information
-  Simple and user-friendly interface
-  Responsive webpage structure
-  Custom styling and visual design

##  Technologies Used

- **HTML5** — webpage structure
- **CSS3** — styling and layout
- **JavaScript** — application logic
- **TensorFlow.js** — machine learning framework
- **Google Teachable Machine** — image classification model
- **Poppins** — interface typography

##  How the AI Works

EcoSort follows a simple machine learning workflow:

```text
Webcam
   ↓
Capture Image
   ↓
TensorFlow.js
   ↓
Teachable Machine Model
   ↓
Class Prediction
   ↓
Confidence Score
   ↓
Result Displayed
```

### Step-by-step

1. The user clicks **Start**.
2. The browser requests access to the webcam.
3. EcoSort creates a webcam feed using the Teachable Machine image library.
4. The trained machine learning model is loaded.
5. Frames from the webcam are continuously analyzed.
6. The model predicts the waste category.
7. The predicted class and probability are displayed on the webpage.

##  Project Structure

```text
EcoSort/
│
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── images/
├── Cursor/
│   └── leaf.png
└── README.md
```

> The machine learning model is currently hosted through **Google Teachable Machine** rather than being stored directly inside the repository.

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/FabihaNurjina/EcoSort.git
```

### 2. Open the project

Open the project folder in **Visual Studio Code** or another code editor.

### 3. Run the webpage

You can open `index.html` directly, but using a local development server such as **VS Code Live Server** is recommended.

### 4. Allow camera access

Click **Start** and allow webcam access when your browser asks for permission.

##  Machine Learning Model

The classification model was created and trained using **Google Teachable Machine**.

The JavaScript application loads the model using:

```javascript
const URL = "https://teachablemachine.withgoogle.com/models/qLUVx_nri/";
```

The model provides:

- `model.json`
- `metadata.json`
- Trained model weights

These are loaded dynamically by the application.

##  Environmental Purpose

Waste management is not only a technological problem — it is also a problem of **awareness and everyday decision-making**.

EcoSort explores how AI can help make waste segregation easier by providing an interactive tool that demonstrates how technology can support sustainable habits.

The project connects **Artificial Intelligence + Environmental Sustainability** to address a simple but important real-world challenge.

##  Future Improvements

Possible future versions of EcoSort could include:

-  Image upload classification
-  Improved webcam interface
-  More detailed waste categories
-  Recycling and disposal recommendations
-  Environmental impact information
-  Multi-language support
-  Dark mode
-  Improved mobile optimization
-  Classification history and statistics
-  A larger and more diverse training dataset

##  Contributing

Contributions and ideas are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Open a Pull Request.

##  Author

**Fabiha Nurjina**

---
