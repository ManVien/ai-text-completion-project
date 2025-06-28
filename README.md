# Generative AI Text Completion App (Cohere)
This is a simple Python-based Generative AI text completion application using Cohere’s Chat API to generate coherent and relevant responses based on user prompts.

## ✅ Features
- Accepts user input in an interactive session
- Uses Cohere’s command-nightly chat model
- Displays AI-generated text
- Saves the entire conversation (prompt + response) in a log file for easy review

## 🔧 Setup Instructions
1. Clone the repository
```
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Install dependencies
- Make sure you have Python 3 and Jupyter Notebook installed.
- Then install the required Python package:
```
pip install cohere
```

3. Create a Cohere account and get your API key
- Go to https://cohere.com and sign up for a free account.
- After logging in, click API Keys on your dashboard.
- Copy your API key.

4. Set up your API key as an environment variable

✅ For Windows (PowerShell):
```
setx COHERE_API_KEY "your_api_key_here"
```
Then restart your terminal or IDE so the environment variable is recognized.

5. Open the Jupyter Notebook

In your terminal or Anaconda Prompt, navigate to the project folder and run:
```
jupyter notebook
```

6. Run all cells
- Click Run (▶️) for each cell to execute the notebook.
- Enter your prompts in the provided input cells.
- View the AI’s responses printed below each cell.

## 💡 How to Use
1. Enter a prompt, such as:
- "Write a haiku about the ocean."
- "Explain photosynthesis to a 10-year-old."
2. Press Shift + Enter to run the input cell.
3. The AI response will display below.
4. To stop the app, type exit when prompted.

## 📁 Conversation Log
All prompts and responses are saved in conversation_log.txt in the project folder for your review and submission.

## 🔒 Important Notes
- Keep your API key private. Never share it in public GitHub repositories.
- This app uses Cohere’s free trial quota; heavy use may require a paid plan.

## ✨ Reflection (for your assignment)

✔️ Record at least five different prompts and responses

✔️ Evaluate:
- Coherence & relevance
- Inaccuracies or biases
- Tone or depth

✔️ Reflect on:
- When does the AI perform well?
- Where does it struggle?

## 🙌 Need help?

If you have any issues running this notebook, ensure:
- Your API key is set correctly.
- You have installed all required libraries.
- You restarted your terminal or Jupyter Notebook after setting the environment variable.
