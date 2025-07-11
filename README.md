# Siyamthanda Dlakavu - Personal CV Website

## Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Projects](#projects)
- [Setup and Usage](#setup-and-usage)
- [Important Note for Chatbot Integration](#important-note-for-chatbot-integration)
- [Contact](#contact)

## About

This is the personal Curriculum Vitae (CV) website for Siyamthanda Dlakavu, a Junior Frontend Developer with a solid background in web technologies, IT administration, and cloud computing. The website showcases skills, experience, and projects, reflecting a passion for building responsive, user-centric web applications and maintaining robust IT environments.

## Features

* **Responsive Design:** Optimized for various devices and screen sizes.
* **Comprehensive CV Sections:** Includes About, Info, Skills, Experience, Achievements, Portfolio (Projects), and Contact sections.
* **Skill Highlight:** Detailed breakdown of both Technical and Soft Skills.
* **Interactive Chatbot:** Integration of an AI-powered chatbot (Dialogflow) to enhance user engagement and provide interactive assistance.
* **Project Showcase:** Dedicated section to highlight key projects with links to GitHub repositories and live demos.
* **Downloadable CV:** Option for visitors to download the CV in `.docx` format.

## Technologies Used

The website is built using a combination of foundational web technologies:

* **Frontend:**
    * HTML5
    * CSS3
    * JavaScript
* **Backend/Integration (for Chatbot):**
    * Dialogflow (Google Cloud)
    * JavaScript API for Dialogflow integration
    * Natural Language Processing (NLP) concepts are applied via Dialogflow.
* **Other highlighted skills in CV content that may be relevant:**
    * Python, Java, C++
    * Microsoft Azure Cloud
    * IT Support & Troubleshooting
    * Database Management (SQL)
    * Network Configuration

## Projects

### Personal CV Website
* **Description:** The website itself, designed to showcase skills, experience, and projects.
* **Technologies:** HTML5, CSS3, JavaScript, Responsive Design.
* **GitHub Repository:** [https://github.com/SiyamthandaD/My-cv-website](https://github.com/SiyamthandaD/My-cv-website)
* **Live Demo:** [https://siyamthandad.github.io/My-cv-website/](https://siyamthandad.github.io/My-cv-website/)

### AI Chatbot Integration
* **Description:** Implemented a Dialogflow-powered chatbot to enhance user engagement and provide interactive assistance.
* **Technologies:** Dialogflow, JavaScript API, Natural Language Processing.
* **GitHub Repository:** [https://github.com/SiyamthandaD/AI-Chat-Bot-Project](https://github.com/SiyamthandaD/AI-Chat-Bot-Project)
* **Try the Chatbot:** Available directly on the live demo website.

## Setup and Usage

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SiyamthandaD/My-cv-website.git](https://github.com/SiyamthandaD/My-cv-website.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd My-cv-website
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your preferred web browser. As this is a static website, no special server setup is required to view the basic content.

### Chatbot Specific Setup (For Development/Testing)

The chatbot integration uses Google Dialogflow. To get the chatbot fully functional in a local development environment:

1.  **Dialogflow Project ID:** Update the `dialogflowConfig.projectId` in `index.html` with your Dialogflow Project ID.
2.  **Authentication Token:** The current implementation uses a placeholder `YOUR_TEMPORARY_ACCESS_TOKEN`. For testing purposes, you can generate a temporary access token using `gcloud auth print-access-token` if you have the Google Cloud SDK configured.
3.  **Important:** For a production environment, it is crucial to implement a secure backend service to handle Dialogflow interactions and manage API keys. Do **NOT** expose API keys directly in the frontend code.

## Important Note for Chatbot Integration

The current chatbot implementation within `index.html` is for **demonstration purposes only**. It directly exposes a placeholder for an access token and makes direct calls to the Dialogflow API from the client-side.

**For any production deployment, you MUST:**
1.  Create a secure backend endpoint to authenticate with your Dialogflow service account.
2.  Have your frontend call that backend endpoint to obtain a token securely, preventing direct exposure of sensitive credentials.

## Contact

You can reach out to Siyamthanda Dlakavu via the contact form on the website.

**Author:** Siyamthanda Dlakavu
