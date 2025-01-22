# MarkdownToDocTask

## Brief Description
This project provides a Python script designed to convert markdown meeting notes into a well-formatted Google Doc. The script is intended to run in a Google Colab environment and uses the Google Docs API for integration. It automatically applies styling rules to headers, bullet points, and checkboxes, ensuring a professional and structured output.

## Setup Instructions
1. Clone or download this repository to your local machine.
2. Upload the repository files to your Google Drive or keep them locally for reference.
3. Obtain Google API credentials:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project.
   - Enable the "Google Docs API" for the project.
   - Create credentials for an OAuth 2.0 client and download the `client_secrets.json` file.
4. Upload the `client_secrets.json` file to your Colab environment.

## Required Dependencies
Ensure you have the following Python libraries installed in your Colab environment:
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`
- `google-api-python-client`
- `markdown`

If they are not already installed, you can install them in Colab using:
```python
!pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client markdown
```

## How to Run in Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the Python script (`main.py`) to the Colab environment.
3. Upload your `client_secrets.json` file.
4. Run the script by executing the cells in the provided notebook.
5. Follow the prompts for Google API authentication.
6. Upon successful execution, the Google Doc URL will be displayed in the Colab output.

