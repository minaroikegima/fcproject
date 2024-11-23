**Resume Website Project**

This is a personal resume website showcasing my skills, projects, and professional experience. The website is designed as a static site and deployed using Azure Static Web Apps.

**Project Details**

Purpose: To present my resume and portfolio in a professional and visually appealing format.
Technologies Used:
Frontend: HTML, CSS
Deployment: Azure Static Web Apps

**Features**:

A responsive design that works on all devices.
Sections include: About Me, Skills, Experience, Projects, and Contact.

**Live Demo**

The project is live and accessible at the following URL:
https://minaresumewebsite.z33.web.core.windows.net/


**Deployment Steps**
1. Hosting Platform
The website is deployed using Azure Static Web Apps.

2. Steps to Deploy
Create a Static Web App on Azure:

-Logged into the Azure Portal https://portal.azure.com/.

-Created a new Static Web App resource.

-Configured the deployment source (GitHub/Local Upload) and selected a custom domain (optional).

Upload Project Files:

All HTML, CSS, and images were manually uploaded to Azure via the portal.
Configure Static Web Hosting:

Configured the hosting to use index.html as the primary entry point.
Tested and verified public access.
Repository Structure

**/resume-website**


├── index.html        # Main webpage file

├── about.html        # connecting webpage file

├── resume.html        # connecting webpage file

├── styles.css        # CSS styles for the project

└── README.md         #Documentation file


**Future Improvements**
1. Integrate a contact form using a backend service like AWS Lambda or Firebase.
2. Add more interactive elements using React or Vue.js.
3. Include analytics (e.g., Google Analytics) to track user visits.
