# Virtual Assistant

This is a Python-based **Virtual Assistant** that can:
- Open websites and applications
- Perform system operations (shutdown, restart, lock screen)
- Take screenshots
- Answer general queries using **OpenAI API**

## Features
✅ Open websites like YouTube, Google, GitHub
✅ Open applications (Notepad, Calculator, VS Code)
✅ System controls (Shutdown, Restart, Lock)
✅ Take Screenshots
✅ Fetch answers using **OpenAI API**

## Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Virtual-Assistant.git
cd Virtual-Assistant
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up OpenAI API
1. Get your API key from [OpenAI](https://openai.com/api/)
2. Create a `.env` file in the project root and add:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```
3. Modify `assistant.py` to load this key:
   ```python
   from dotenv import load_dotenv
   import os
   
   load_dotenv()
   openai.api_key = os.getenv("OPENAI_API_KEY")
   ```

## Usage
Run the assistant with:
```bash
python assistant.py
```
Type a command (or use voice input if enabled), for example:
- `open youtube`
- `search Python tutorials`
- `shutdown`
- `screenshot`
- `What is machine learning?`

## Contributing
Feel free to open an issue or submit a pull request!

Contact- rjnaman03@gmail.com

