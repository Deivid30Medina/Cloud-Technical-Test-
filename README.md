# Title

Cloud-Technical-Test 

# Description

This project was developed as part of a technical test for the **Cloud Junior Developer** position. The primary goal was to build a simple web application for task management, enabling users to create, view, and delete tasks efficiently.  

The project includes a **frontend** for the user interface and a **backend** for the business logic, implemented using modern technologies and best practices.  

# Tabla de cotenidos

- [Title](#title)
- [Description](#description)
- [Tabla de cotenidos](#tabla-de-cotenidos)
- [Project Structure](#project-structure)
    - [Frontend](#frontend)
    - [Backend](#backend)
    - [Demo Video](#demo-video)
- [Technical Testing and Limitations](#technical-testing-and-limitations)
  - [Achieved Functionalities](#achieved-functionalities)
  - [Pending Functionalities](#pending-functionalities)

# Project Structure

### Frontend

- **`Frontend`**: This module contains the user interface (UI), developed with **React**, **TypeScript**, and **Tailwind CSS**. The design focuses on simplicity and usability, allowing intuitive interaction for task management.  

  
  - [Frontend Repository](https://github.com/Deivid30Medina/Frontend-Cloud-Technical-Test-Deploy)
  
  - [GitHub Pages Deployment](https://deivid30medina.github.io/Frontend-Cloud-Technical-Test-Deploy/#/tasks) 


### Backend

- **`Backend`**: This module implements the business logic and exposes a RESTful API for task management. It was developed using **Java 17**, the **Spring Boot** framework, and an in-memory database (**H2 Database**) for temporary data persistence.  
  
  - [Backend Repository](https://github.com/Deivid30Medina/Backend-Cloud-Technical-Test)
  
  - [Render Deployment](https://backend-cloud-technical-test.onrender.com) 

### Demo Video

In case the deployments are not operational due to limitations in requests or costs associated with the Render platform, a demo video is included to showcase the full functionality of the application.  

  - [Demo Video](https://youtu.be/s_ORDngofDU) 

# Technical Testing and Limitations

## Achieved Functionalities

All the technical requirements outlined in the test were successfully implemented:

1. **Endpoints RESTful:**  
    
    - POST /tasks: Create a new task. 
  
    - GET /tasks: List all tasks.
  
    - DELETE /tasks/{id}: Delete a task.
  
2. **Backend Testing:**  

   - Integration tests were developed to validate the correct functionality of the endpoints. 
  
3. **Frontend:**  

   - A minimalist and functional design optimized for user-friendly interaction.
 
## Pending Functionalities

- **Frontend Testing:**  

  - Automated tests for the frontend were not implemented due to time constraints.  
