# Secure File Upload Portal

## Project Overview
The Secure File Upload Portal is a web-based application developed using Python Flask. It allows users to upload files securely by validating file extensions, file types, file sizes, and file content.

## Technologies Used
- Python
- Flask
- HTML
- CSS
- SQLite
- Pillow
- pypdf

## Features
- Secure file upload system
- File extension validation
- File size restriction (maximum 5 MB)
- PDF and image file validation
- Detection of potentially dangerous PDF content
- Automatic file renaming
- Admin login authentication
- Admin dashboard
- Upload history and storage statistics
- Protected file downloads
- SQLite database integration

## Allowed File Types
- PDF
- PNG
- JPG
- JPEG

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder:
   ```bash
   cd Secure-File-Upload-Portal
   ```

3. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```

4. Activate the environment (Windows):
   ```bash
   .venv\Scripts\activate
   ```

5. Install dependencies:
   ```bash
   pip install Flask Pillow pypdf
   ```

6. Run the application:
   ```bash
   python app.py
   ```

7. Open your browser:
   `http://127.0.0.1:5000`

## Project Purpose
This project demonstrates basic web application security concepts, file validation, upload restrictions, and administrator access control.

## Disclaimer
This is an educational project and does not guarantee complete malware detection or protection against all malicious files.

## Developer
BCA Final Year Project
