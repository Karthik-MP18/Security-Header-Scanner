# Security Header scanner

## First Step

Git clone the repo for linux or Download Zip file


Run requirements.txt first to make sure all modules used in the script are installed

`pip install -r requirements.txt`

## Usage

`python header_scanner.py https://www.example.com` 

It will check if following Basic Security Headers are present/missing in the application response:

X-Frame-Options

X-XSS-Protection

X-Content-Type-Options

Strict-Transport-Security

Content-Security-Policy
