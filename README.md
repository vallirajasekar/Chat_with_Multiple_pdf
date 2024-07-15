
```markdown
# Chat with Multiple PDF

This project aims to provide a comprehensive solution for chatting with multiple PDF documents. It leverages Streamlit for the web interface and advanced AI for generating responses from the content of the PDFs.

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/vallirajasekar/Chat_with_Multiple_pdf.git
cd Chat_with_Multiple_pdf
```

### Step 2: Create the Conda Environment

Create a new Conda environment with Python 3.10.

```bash
conda create -p venv python==3.10 -y
```

### Step 3: Activate the Environment

Activate the Conda environment.

```bash
conda activate /Users/vallirajasekar/Desktop/gemini/CHAT_WITH_MULTIPLE_PDF/venv
```

### Step 4: Install Dependencies

Install the required dependencies.

```bash
pip install -r requirements.txt
```

## Usage

### Set Up API Key

Make sure to set up your Google API key. You can store it in a .env file in the root directory of your project:

```
GOOGLE_API_KEY=your_api_key
```

### Run the Streamlit Application

Start the Streamlit application by running:

```bash
streamlit run app.py
```

## Features

- **PDF Content Retrieval**: Fetches and processes the content of multiple PDF documents.
- **AI-Powered Chat**: Generates responses based on the content of the PDFs using advanced AI.
- **User-Friendly Interface**: Provides an intuitive web interface for users to upload PDF files and chat with their content.

## How It Works

1. **User Input**: Users upload multiple PDF documents.
2. **Content Retrieval**: The application processes the PDF content.
3. **AI Chat**: The content is analyzed, and responses are generated using advanced AI.
4. **Display Response**: The generated responses are displayed to the user on the web interface.

## Acknowledgements

This project utilizes the following technologies:

- **Streamlit**: An open-source app framework for Machine Learning and Data Science teams.
- **PDF Processing Libraries**: Python libraries to fetch and process PDF documents.
- **Advanced AI**: AI models for generating natural language responses.

## Project Structure

```
Chat_with_Multiple_pdf/
│
├── app.py                # Main application script
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
├── venv/                 # Conda virtual environment directory
├── .env                  # Environment variables file
├── static/               # Directory for static files (if any)
├── templates/            # Directory for HTML templates (if any)
└── .git/                 # Git version control directory
```

## Version Control with Git

This project uses Git for version control. Below are some basic commands to get you started:

- Initialize a new Git repository:

  ```bash
  git init
  ```

- Add files to the staging area:

  ```bash
  git add .
  ```

- Commit changes:

  ```bash
  git commit -m "Initial commit"
  ```

- Add a remote repository:

  ```bash
  git remote add origin https://github.com/vallirajasekar/Chat_with_Multiple_pdf.git
  ```

- Push changes to the remote repository:

  ```bash
  git push -u origin main
  ```

Feel free to reach out if you have any questions or need further assistance!
```