## Week 1 – Project Initiation and Technology Research (MollyLimpets)

### Tasks Completed
During Week 1 of the MollyLimpets project, initial research and planning activities were carried out to establish the technical direction of the system. The focus was on understanding the project requirements and selecting appropriate technologies for both the frontend and backend components.

Research was conducted into modern web application architectures, with particular attention given to separating the frontend and backend to improve scalability, maintainability, and development efficiency. As a result, a full-stack approach was selected, consisting of a dedicated API backend and a standalone frontend application.

The backend was planned and set up using **ASP.NET Core Web API**, chosen for its performance, security, and suitability for building RESTful services. The backend is responsible for handling business logic, database connections, and API endpoints such as items, collections, customers, locations, and image handling.

For the frontend, **SvelteKit** was selected after researching modern JavaScript frameworks. SvelteKit offers fast performance, a component-based structure, and smooth API integration, making it suitable for building a responsive and maintainable user interface for the MollyLimpets system.

### Why This Technology Stack Was Chosen
1. **Separation of Concerns** – Frontend and backend are developed independently, improving maintainability.
2. **Performance** – ASP.NET Core provides efficient API handling, while SvelteKit delivers fast rendering.
3. **Scalability** – The REST API allows future expansion, including mobile or third-party integrations.
4. **Modern Development Tools** – Supports debugging, hot reloading, and environment-based configuration.

### Technologies Used in the MollyLimpets Project
- **Frontend Design**: Initial UI planning and layout concepts
- **Frontend Development**: SvelteKit (JavaScript / TypeScript)
- **Backend Development**: ASP.NET Core Web API (C#)
- **Database**: SQL-based relational database
- **API Integration**: RESTful endpoints for frontend–backend communication

### Tasks To Do
Further development will focus on completing backend API routes, improving frontend components, and ensuring correct API connectivity using environment variables. Additional research will be carried out on deployment and security configurations.

### Issues Encountered
Initial issues were encountered when configuring communication between the frontend and backend during development, particularly with API base URLs and CORS settings. These issues are being investigated and resolved through testing and configuration updates.
Week 1 PSP content
