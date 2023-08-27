# sinotorg-pro

## Local setup

1. Clone this repository

2. Open the project in [VS Code](https://code.visualstudio.com/)

3. Install VS Code extension [Live Server
](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

4. Click the <kbd>Go Live</kbd> button in the right bottom corner of the VS Code window

5. Open `http://localhost:5500` in your browser

## Deployment

1. Set up FTP user and credential via ISPManager panel, specify the root folder carefully

2. Edit the repository secrets (GitHub Repository → Settings → Secrets and Variables → Actions), input the following parameters:

`FTP_SERVER` usually contains IP address of the hosting server

`FTP_USER` username that you have created

`FTP_PASSWORD` password that you have created