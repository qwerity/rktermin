# Telegram Mini WebApp for Visa Application

This repository contains the source code for a Telegram Mini WebApp that allows users to fill out and apply for a visa through a Telegram bot.

![image](https://github.com/qwerity/rktermin/assets/2309929/f1b4051a-b45a-40d8-addc-3dd3ecc8d022)


## Features

- User-friendly interface for visa application.
- Integration with Telegram bot for seamless user experience.
- Form validation and error handling.

## Requirements

- A Telegram bot (code for the moment is private)

## Usage

1. Start a conversation with your Telegram bot.
2. The bot will provide a link to the Mini WebApp.
3. Click the link to open the Mini WebApp.
4. Fill out the visa application form.
5. Submit the form to apply for a visa.

## HTML Files

### userdata.html

This file contains the form for visa application. It includes fields for first name, last name, passport number, email, phone number, and desired visa period. The form is validated using JavaScript and jQuery UI for date picking.

### contact_admin.html

This file contains the form for user feedback. It allows users to provide feedback or report issues with a text area field.

## Scripts

- **Initialization**: The web app initializes by setting up the Telegram WebApp environment and making the main button visible.
- **Form Submission**: The form submission process includes validation of input fields and confirmation prompts before sending data to the Telegram bot.
- **Validation Functions**: Custom functions are used to validate names, email addresses, and phone numbers.

## License

This project is licensed under the MIT License.
