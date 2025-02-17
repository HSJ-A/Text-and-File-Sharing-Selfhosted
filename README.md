# Text-and-File-Sharing-Selfhosted
Text and File Sharing Self-hosted on Linux

A self-hosted website that generates random QR codes and URLs, and allows users to share and edit text and files simultaneously.
No login or credentials required.

Prerequisites for Linux server:

sudo apt update && sudo apt upgrade -y

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -

sudo apt install -y nodejs

cd /path/to/qr-code-app

npm install

to run:

cd qr-code-app

node server.js
