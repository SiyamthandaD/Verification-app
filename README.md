Bank of Braamfontein - Document Access Application
This repository contains a multi-step web application for the "Bank of Braamfontein" designed to manage and streamline internal document access requests, manager approvals, and verification processes.

Table of Contents
About

Features

Pages

Technologies Used

Setup and Usage

Contributing

License

About
The Bank of Braamfontein Document Access Application provides a secure workflow for employees to request access to internal documents, for managers to approve these requests, and for a final verification step before access is granted. This system aims to enhance security and accountability for sensitive document access within the organization.

Features
Employee Request Form: A user-friendly interface for employees to submit document access requests.

Manager Approval Page: A dedicated page for managers to review request details and approve or deny access.

OTP Verification: A 6-digit One-Time Password (OTP) verification step for enhanced security (simulated).

Success Confirmation: A clear confirmation page upon successful document access.

Responsive Design: Styled with Bootstrap and custom CSS for a consistent look and feel.

Form Validation: Basic client-side validation for input fields.

Pages
The application consists of the following HTML pages:

login.html: The initial page where employees request access by providing their name, email, and the document name.

manager-approval.html: Displays the employee's request details and allows a manager to input their name and email to approve the request.

verification.html: Simulates an OTP (One-Time Password) verification process, requiring a 6-digit code.

success.html: Confirms that document access has been granted and the event logged.

Technologies Used
HTML5: For the structure and content of the web pages.

CSS3: For styling and layout, including custom styles in login.css.

JavaScript: For interactive elements, form handling, data passing between pages, and OTP logic.

Bootstrap 5.3: A popular CSS framework for responsive design and pre-built components.

Font Awesome 6.4.0: For various icons used throughout the application.

Google Fonts (Montserrat): For typography.

Setup and Usage
To run this application locally, follow these simple steps:

Clone the repository (or download the files):
If you have the files locally, ensure they are in the same directory:

login.html

manager-approval.html

verification.html

success.html

login.css

logo.jpg

Open login.html:
Simply open the login.html file in your preferred web browser. No special server setup is required as this is a static web application.

Navigate the workflow:

Fill out the form on login.html and submit to proceed to manager-approval.html.

On manager-approval.html, fill in manager details and approve to go to verification.html.

On verification.html, enter any 6 digits (as the OTP is simulated) and verify to reach success.html.

Note on OTP Verification:
The OTP verification in verification.html is currently a client-side simulation for demonstration purposes. In a real-world scenario, this would involve a backend service to generate, send (e.g., via email or SMS), and validate the OTP securely. The alert() for "New verification code sent" is also a placeholder.

Contributing
Contributions to improve this application are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

License
This project is open-source and available under the MIT License.
