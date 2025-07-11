# File Uploader Web App

A simple Flask web application to upload files securely.

## Setup

1. Create and activate a Python virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set environment variables in a `.env` file (optional):
   ```env
   SECRET_KEY=your_secret_key
   UPLOAD_FOLDER=uploads
   ```
4. Run the app:
   ```bash
   python app.py
   ```

## Usage
- Visit `http://localhost:5000` in your browser.
- Upload files using the form.

## Security
- Only allows certain file types.
- Limits file size to 16MB.
- Uses secure filenames.

## Project Structure
```
File_uploader/
├── app.py
├── config.py
├── requirements.txt
├── .gitignore
├── uploads/
├── static/
│   └── style.css
└── templates/
    └── upload.html
```
