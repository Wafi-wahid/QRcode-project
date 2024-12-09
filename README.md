# QRcode Generator

## Overview
The **QRcode Generator** project is a simple Node.js application that allows users to generate a QR code based on a URL they input. The URL entered by the user is saved in a `URL.txt` file, and the corresponding QR code is generated and saved as a `qr_image.png` file. 

This project uses the `qrcode` package to generate the QR code, making it a quick and easy way to create a scannable code for any URL.

## Features
- Accepts a URL input from the user.
- Saves the URL in a text file (`URL.txt`).
- Generates and saves the QR code image as `qr_image.png`.
- Easy to run with Node.js.

## Prerequisites
- [Node.js](https://nodejs.org/en/) (version 14 or higher) installed on your machine.
- A text editor or IDE (such as Visual Studio Code) for editing the code.

## Installation

### Step 1: Clone the Repository
Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/yourusername/QRcode-Generator.git
cd QRcode-Generator
```
### Step 2: Run the Code
Run the project using the following command:
```bash
node index.js
```
### Step 3: Enter URL
Enter the url whose qr is to be generated:
```bash
www.example.com
```


