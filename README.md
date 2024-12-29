# Johnny Tree Planting Assistance System

This project is designed to assist in tree planting activities using advanced technologies. Follow the steps below to set up the project on your local machine.

---

## Installation Guide

### Step 1: Clone the Repository
```bash
git clone https://github.com/YourUsername/Johnny_Tree_planting_assistance_system.git
cd Johnny_Tree_planting_assistance_system
```

### Step 2: Set Up a Virtual Environment
1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

### Step 3: Install Dependencies
Install all required Python libraries using `requirements.txt`:
```bash
pip install -r requirements.txt
```

---

## Configuring API Key

The system uses the Gemini API for data access. You need to set your API key as an environment variable.

### Step 1: Replace the Placeholder in Code
Locate the placeholder for the API key in the source code and replace it with your actual API key:
```python
API_KEY = "Your Gemini API Key"
```

### Step 2: Set Environment Variable
On Windows, you can set the `GOOGLE_API_KEY` environment variable using PowerShell:
```powershell
$env:GOOGLE_API_KEY="Your Gemini API Key"
```

To make it permanent:
1. Open **System Properties** > **Advanced** > **Environment Variables**.
2. Add a new user variable:
   - **Variable name**: `GOOGLE_API_KEY`
   - **Variable value**: `Your Gemini API Key`

---

## Running the Application

Once the setup is complete, you can run the application using the following command:
```bash
python app.py
```

Ensure that your API key and dependencies are correctly configured.

---

## Troubleshooting

If you encounter any issues:
1. Verify that the virtual environment is activated.
2. Ensure the API key is correctly set and valid.
3. Check the installed dependencies using:
   ```bash
   pip list
   ```

For further assistance, please contact the project maintainer.