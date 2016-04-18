# Google-Gmail-API-Python-3+

This is the Google's Gmail API integration for python 3+

This particular integration is for retrieving the tokens present in the gmail account, creating a text mail using MIMEText( ), creating a mail with attachments, sending mail through your gmail account.


**Please add your own client_secret.json before running the file quickstart.py**

For getting your own client_secret.jason follow these steps:

1. Go to <a href=https://console.developers.google.com/start/api?id=gmail>this link</a> create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials.
2. At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button.
3. Select the Credentials tab, click the Add credentials button and select OAuth 2.0 client ID.
4. Select the application type Other, enter the name "Gmail API Quickstart", and click the Create button.
5. Click OK to dismiss the resulting dialog.
6. Download the json file through the button to the right of the client ID.
7. Move this file to your working directory and rename it client_secret.json.
