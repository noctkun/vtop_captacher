# Captcha-er v1.0

This Chrome extension automates the process of solving captcha images on websites. It uses image processing techniques to recognize and solve captchas efficiently. Once a captcha is recognized, the extension automatically fills the solution into the appropriate input field.

## Features

- **Captcha Recognition**: Uses image processing to recognize captcha characters from an image.
- **Auto-fill Captcha**: Automatically fills the captcha input field with the correct solution.
- **Captcha Refresh Handling**: Detects and solves new captchas when the page refreshes or when a new captcha is generated.

## How It Works

1. **Injecting Scripts**: The extension injects `bitmaps.js` and `content.js` into the webpage when a captcha is detected.
2. **Captcha Image Detection**: The extension identifies captcha images by checking for `img` elements with specific alt attributes (e.g., `vtopCaptcha`).
3. **Image Processing & Recognition**: The captcha image is converted to pixel data, which is then analyzed using predefined bitmaps for character recognition.
4. **Auto-fill**: Once recognized, the captcha input field is automatically filled with the solution.
5. **Captcha Refresh**: The extension listens for refresh events, automatically solving the new captcha.

## Installation

1. **Clone the Repository**

   Download or clone the repository to your local machine:

   ```bash
   git clone https://github.com/noctkun/vtop_captchaer.git

### Demo

https://github.com/user-attachments/assets/162adfeb-d4d4-490c-8ea5-8a2fa98286ad

