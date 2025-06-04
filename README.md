Job Application Email Generator
A Python desktop application that streamlines the job application process by automatically generating and sending professional email applications with CV attachments.
Features

Multi-step Wizard Interface: User-friendly tabbed interface guiding you through the application process
Email Configuration: Secure Gmail integration with app password support
Smart Email Generation: Automatically creates professional job application emails based on job descriptions
CV Attachment: Support for PDF, DOC, and DOCX file attachments
Email Preview: Review and edit generated emails before sending
Application Logging: Track sent applications with timestamp and recipient details
Dark/Light Theme: Toggle between themes for comfortable usage
Input Validation: Comprehensive validation for email addresses and required fields

Requirements

Python 3.6+
tkinter (usually included with Python)
Gmail account with 2FA enabled
Gmail App Password

Installation

Clone this repository:

bashgit clone https://github.com/yourusername/job-application-email-generator.git
cd job-application-email-generator

Run the application:

bashpython job_application_generator.py
Usage

Email Setup: Enter your Gmail credentials and recipient email
Job Details: Paste the job description and upload your CV
Preview: Review the auto-generated email and make any necessary edits
Send: Send the email and optionally save to application logs

Security Notes

Uses Gmail App Passwords for secure authentication
No credentials are stored permanently
All email sending is done through official Gmail SMTP servers

Screenshots
The application features a clean, modern interface with:

Tabbed navigation for easy workflow
Dark/light theme support
Real-time status updates
Professional email templates

Contributing
Feel free to submit issues and enhancement requests!
License
This project is open source and available under the MIT License.
