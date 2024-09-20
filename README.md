# Clip to QR 📋➡️📱

A Python tool that generates a QR code from clipboard text and displays it in a GUI window using Tkinter.

## Requirements

- Python 3.x
- qrcode
- pyperclip

## 🚀 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/patricnilackshan/clip-to-qr.git
    cd qrgen
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Make the script executable:
    ```bash
    chmod +x clip2qr.py
    ```

4. Add an alias to your ~/.bashrc file for easier access.

    Open the file with:
    ```bash
    nano ~/.bashrc
    ```

5. Add the following line to the end of the file:
    ```bash
    alias clip2qr='/path/to/bin/python /path/to/clip2qr.py'
    ```
    - Replace '/path/to/bin/python' and '/path/to/clip2qr.py' with actual values

6. Save and close the file.
    Then run the following command to apply the changes:
    ```bash
    source ~/.bashrc
    ```

## 🖥️ Usage

1. Copy any text to your clipboard.
2. Open a terminal and type `clip2qr`.
3. A window will appear displaying the generated QR code.


<br>

### © PATRIC NILACKSHAN (pnilackshan@gmail.com)

<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=patricnilackshan.clip-to-qr" />
