# GenAI Practice App

A Python application for practicing with Generative AI using OpenAI's API.

## Setup

### 1. Create a Virtual Environment

It's recommended to use a virtual environment to isolate your project dependencies:

```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
# venv\Scripts\activate
```

### 2. Install Dependencies

```bash
# Make sure virtual environment is activated, then install dependencies
pip install -r requirements.txt
```

### 3. Environment Variables

Create a `.env` file in the project root with your OpenAI API key:

```bash
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the Application

```bash
python main.py
```

## Managing Dependencies

### Adding New Dependencies

1. Install the package:
   ```bash
   pip install package_name
   ```

2. Update requirements.txt:
   ```bash
   pip freeze > requirements.txt
   ```

### Updating Dependencies

```bash
# Update all packages to latest versions
pip install --upgrade -r requirements.txt

# Update a specific package
pip install --upgrade package_name
```

### Deactivating Virtual Environment

```bash
deactivate
```

## Project Structure

```
genai-practice-app/
├── main.py              # Main application file
├── requirements.txt     # Project dependencies
├── .env                 # Environment variables (not tracked in git)
├── .gitignore          # Git ignore rules
└── README.md           # This file
```
