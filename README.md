# Hospital Management System - Project Showcase

## Overview
This project is a prototype for a Hospital Management System (HMS) using a **microfrontend architecture**. The system consists of multiple React microfrontends, backed by .NET Core Web API services, and deployed on Microsoft Azure.

The main goal is to build a scalable, modular, and maintainable system that can be extended easily with new features.

---

## Architecture

- **shell-app**: React container app (host) responsible for routing and integrating microfrontends using Module Federation.
- **login-mf**: Login microfrontend for user authentication.
- **dashboard-mf**: Dashboard microfrontend displaying user data and navigation.
- **add-patient-mf**: Microfrontend to add and register new patients.
- **Backend Services**: .NET Core Web APIs handling business logic and data persistence.
- **Azure Cloud**: Hosting frontends via Azure Static Web Apps, backend APIs on Azure App Services, and data stored in Azure SQL Database.

## System Architecture

![Architecture Diagram](Architecture_Diagram_HospitalManagementSystem.png)


---

## Technologies Used

- **Frontend:** React, React Router, Module Federation, Material UI, JavaScript, CSS (including Flexbox), HTML  
- **Backend:** C#, ASP.NET Core Web API, Entity Framework, Swagger for API documentation  
- **Database:** SQL Server (local), Azure SQL Database (cloud)  
- **Development Tools:** VS Code, GitHub, npm, Postman  
- **Cloud & Deployment:** Azure Static Web Apps, Azure App Services, Azure SQL Server, Azure Resource Groups, Azure Portal  
- **Project Management & Documentation:** Jira, Confluence, Draw.io, Figma  
- **Testing:** Jest (JavaScript testing), xUnit (.NET testing), Playwright (end-to-end testing)  
- **Operating Systems:** Windows (primary development), MacOS (optional/support)  
- **Others:** Material UI (React UI library)

---

## Related Repositories

### Frontend Microfrontends
- [Shell App (Container)](https://github.com/rbpeddapalli/bs-prms-shell-app)
- [Login Microfrontend](https://github.com/rbpeddapalli/bs-prms-login)
- [Dashboard Microfrontend](https://github.com/rbpeddapalli/bs-prms-dashboard)
- [Add Patient Microfrontend](https://github.com/rbpeddapalli/bs-prms-add-patient)

### Backend Services
- [Add Patient Registration API](https://github.com/rbpeddapalli/bs-prms-add-patient-service)
- [Login Service](https://github.com/rbpeddapalli/bs-prms-login-service)
- [Dashboard Service](https://github.com/rbpeddapalli/bs-prms-dashboard-service)

### Database Scripts
- [Database Scripts](https://github.com/yourorg/db-scripts)

---

## Key Milestones Completed

- Developed patient registration form using plain HTML/CSS, then upgraded to React with Material UI.
- Created React microfrontends using Module Federation for login, dashboard, and patient management.
- Built .NET Core Web APIs with Swagger integration for easy API testing and documentation.
- Set up Azure environment with resource groups, Static Web Apps, and App Services.
- Configured CI/CD pipelines using GitHub Actions for automated deployment.
- Integrated Azure SQL Database for persistent storage.
- Designed UI/UX mockups using Figma.
- Learned and practiced C#, ASP.NET Core, SQL Server, and React fundamentals.
- Planned upcoming features: microservices communication with Azure Service Bus, containerization with Docker and Kubernetes.

---

## Screenshots

![Patient Registration Form](./docs/patient-registration-form.png)

*More screenshots and Figma design files can be added here.*

---

## Live Demo

You can access the deployed React application here:  
[https://your-app-url.azurestaticapps.net](https://your-app-url.azurestaticapps.net)  
*(Replace with actual URL if available)*

---

## Future Plans

- Implement microservices communication using Azure Service Bus.
- Add automated end-to-end testing with Playwright.
- Containerize backend services with Docker and orchestrate with Kubernetes.
- Explore advanced healthcare domain standards such as HL7 and FHIR.
- Enhance responsiveness and accessibility of the UI.
- Create Blazor frontend alternative.

---

## About Me

This repository showcases my work on a full-stack hospital management system prototype, built with modern web technologies and cloud-native architecture. The project reflects my learning journey and hands-on experience with React, .NET Core, Azure, and SQL databases.

---

*Note: Actual source code is not included due to privacy and company policies.*

---

### Contact

- GitHub: [https://github.com/yourusername](https://github.com/yourusername)  
- LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  

---

*Thank you for visiting!*
