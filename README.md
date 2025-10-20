🪶 Shakespeare Text Generator

A deep learning–based text generation web app that creates Shakespeare-style text based on user prompts. Built using TensorFlow / Keras, Flask, and a pre-trained LSTM model, this project showcases natural language generation and web deployment integration.

🚀 Features

Generate creative Shakespeare-like text from any custom prompt.

Adjustable temperature control to modify creativity.

Simple and elegant Flask-based web interface.

Integration-ready with any Keras-trained model and tokenizer.

🧠 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Flask (Python)

Model: LSTM trained using TensorFlow/Keras

Other Tools: NumPy, Pickle (for tokenizer persistence)

⚙️ Setup Instructions
1️⃣ Clone this repository
git clone https://github.com/yourusername/Shakespeare-Text-Generator.git
cd Shakespeare-Text-Generator

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Ensure model and tokenizer files are present

Place the following files in the project root:

model.h5
tokenizer.pkl

4️⃣ Run the Flask app
python app.py

5️⃣ Open in browser

Visit 👉 http://127.0.0.1:5000

🧩 Project Structure
📂 Shakespeare-Text-Generator
├── app.py
├── model.h5
├── tokenizer.pkl
├── static/
│   ├── style.css
├── templates/
│   ├── index.html
├── requirements.txt
└── README.md

🖋️ Example Prompt

Input: “To be or not to be”
Output:

“To be or not to be, that question stirs the stars and stirs the soul.”

🧑‍💻 Future Enhancements

Add real-time text streaming during generation

Deploy on Render or Hugging Face Spaces

Add multiple text generation styles (Shakespeare, Modern English, etc.)

📜 License

This project is licensed under the MIT License — free to use and modify.
