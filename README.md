# BSCP Chapter 1

Unzip the files in a new directory

Run ` sudo docker compose up --build` in the directory

Challenge is a available at localhost:5000

# 3 steps

## XSS
Bot uses Chromium browser - Best to test with chromium

Send XSS payload in /feedback to exfiltrate cookie

Example: `/resources#<payload>`

## SQLi
Dump database and login as admin

## Cmd execution
Flag is located in /opt/lab/flag.txt

### Take screenshot of flag output
