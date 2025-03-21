Email Automation Bot

This project is a Python-based Email Automation Bot using Streamlit for the front-end interface and smtplib for email sending functionality. It supports sending single or bulk emails, scheduling emails, and attaching PDF files.

Features
- Send Single or Bulk Emails: Supports sending emails to one or multiple recipients.
- Schedule Emails: Allows scheduling emails at a specific time.
- Attachment Support: Attach multiple PDF files.
- Streamlit Interface: User-friendly interface for email configuration.

Requirements
Ensure you have the following installed:

- Python 3.8+
- Streamlit
- smtplib
- pandas
- schedule
- email

You can install the required packages using the following command:
bash
pip install streamlit pandas schedule

Project Structure

├── final.py  # Main application script
└── README.md  # Project documentation
|__ saved_attachments

Setup and Execution
1. Clone the Repository
bash
git clone <repository-url>

2. Navigate to the Project Directory
bash
cd path/to/project

3. Run the Streamlit App
bash
streamlit run final.py

4. Access the Web Interface
- Open the URL displayed in your terminal (usually http://localhost:8501).

Configuration
- Enter your SMTP server details (e.g., Gmail: smtp.gmail.com, Port: 587).
- Provide your email address and app password for authentication.
- Fill in the recipient(s), subject, message body, and optionally upload PDF attachments.
- Choose to send instantly or schedule the email for a specified time.

 Troubleshooting
- Ensure your SMTP settings are correct.
- If using Gmail, enable less secure apps or generate an app password.
- Check firewall or antivirus settings if emails fail to send.

License
This project is licensed under the MIT License.

Acknowledgments
- Developed using Python and Streamlit.
- Special thanks to the Streamlit community for their resources and support.


