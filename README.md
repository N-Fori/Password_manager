# Password Manager

This is a simple **Password Manager** application built with Python and Tkinter.

## Features

- Generate a random secure password with letters, numbers, and symbols.
- Automatically copies the generated password to the clipboard.
- Save website, email/username, and password information to a local text file (`data.txt`).
- Input validation to ensure no empty fields.
- User confirmation before saving data.
- Easy-to-use graphical user interface.

## How to Use

1. Enter the website name.
2. Enter your email or username.
3. Click **Generate Password** to create a strong password automatically (the password will be copied to your clipboard).
4. Alternatively, you can enter your own password manually.
5. Click **Add** to save the data.
6. The saved data will be stored in `data.txt` in the format:  
   `website | email/username | password`

## Requirements

- Python 3.x
- `tkinter` (usually included with Python)
- `pyperclip` (for clipboard functionality) — install via:  



## Notes

- The program displays a logo image (`logo.png`) — make sure to have this image file in the same folder as the script.
- Make sure not to leave the website or password fields empty before saving.
- The password is generated randomly with a mix of letters, numbers, and symbols for better security.
