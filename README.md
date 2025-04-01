# UPI-Payment-QR-Code-Generator
This Python project generates UPI payment QR codes for multiple payment apps (PhonePe, Paytm, and Google Pay) using a user-provided UPI ID.
Features

Generates QR codes for different payment apps.

Saves QR codes as image files.

Displays QR codes for easy scanning.

Supports PhonePe, Paytm, and Google Pay.

Requirements

Make sure you have Python installed along with the required libraries:
 pip install qrcode[pil]


How to Run

Clone the repository:


Run the Python script:
 python upi_qr_generator.py



Enter your UPI ID when prompted.

The generated QR codes will be saved as image files and displayed on the screen.
File Structure
upi-qr-generator/
│-- upi_qr_generator.py
│-- phonepe_qr.png
│-- paytm_qr.png
│-- google_pay_qr.png
│-- README.md

Example

When you run the script, it will prompt:
Enter your UPI ID: yourupi@bank

Then, QR codes for PhonePe, Paytm, and Google Pay will be generated and saved as image files.

License

This project is open-source. Feel free to modify and enhance it!

Made with ❤️ by Akshata Ujawane
