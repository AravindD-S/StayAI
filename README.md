
#  AI-Driven Guest Experience Personalization System for Hospitality

Welcome to the AI-Driven Guest Experience Personalization System project! This system is designed to provide personalized experiences for guests using advanced AI models. It utilizes cutting-edge technologies to enhance customer satisfaction and streamline operations.



## Features

- 🏨 **Personalized Guest Experience**: AI-driven recommendations and personalized experiences for guests based on their preferences and behaviors.
- 🧠 **Advanced AI Models**: Leverage powerful models to predict guest needs and optimize the hospitality experience.
- 💬 **Real-Time Interaction**: Enables real-time communication with guests through AI chatbots and dynamic content.



## 🛠️ Installation

🔀 Clone the Repository
```bash
git clone https://github.com/yourusername/AI-Driven-Guest-Experience-Personalization.git

```
## 📥 Install Required System Dependencies
⚠️ Python Compatibility: This project requires Python version 3.10 (other versions may cause compatibility issues).

To check your Python version, run:
```bash
python --version  # Windows
python3 --version  # macOS/Linux

```
Create a virtual environment with Python 3.10:
```bash 
py -3.10 -m venv venv
```
Activate the virtual environment:
```bash
venv\Scripts\activate
```
Upgrade pip:
```bash
python -m pip install --upgrade pip
```
### 📦 Install Dependencies
Install the required packages:
```bash
pip install -r requirements.txt
```

### 🚀 Usage
To run the project, follow these steps:

1️⃣ Start the Backend
Open a terminal and navigate to the project directory. Then, run:
```bash
python main.py
```
Keep this terminal open as it runs the backend.

2️⃣ Start the Frontend (Streamlit)
Open another terminal in the project directory and run:
```bash
streamlit run frontend/app.py
```
This will launch the Streamlit UI in your browser.


### 📂 Project Structure
📂 StayAI/
├── 📄 main.py – The main script to run the project
├── 📄 requirements.txt – List of dependencies
├── 📄 README.md – Project description and setup guide
├── 📄 .gitignore – Ignore unnecessary files
├── 📄 .env – Environment variables (should be in .gitignore)
├── 📄 env_template.txt – Template for environment variables

📂 backend/ – Backend logic and API
│ ├── 📂 chroma/ – Stores vector database files
│ │ ├── 📄 chroma.sqlite3
│ ├── 📂 mem0_db/ – Database storage
│ ├── 📄 init.py – Initializes the backend module
│ ├── 📄 api.py – API-related backend logic
│ ├── 📄 processing.py – Core backend functions
│ └── 📄 utils.py – Utility functions

📂 frontend/ – UI-related components
│ ├── 📂 components/ – Reusable UI components
│ ├── 📂 pages/ – Frontend pages
│ ├── 📄 init.py – Initializes frontend module
│ ├── 📄 ui.py – UI logic and components


### 🧰 Dependencies
- Langchain: For AI model integration and text processing.
- Sentence-Transformers: For semantic search and recommendation generation.
- Chromadb: For managing and storing the guest experience data.
- Mem0ai: For AI-powered guest experience prediction.
- CrewaI: For advanced guest interaction and personalization.

### 📝 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

### 📧 Contact

For any inquiries or feedback, please reach out to [Aravindraj](https://github.com/AravindD-S)
