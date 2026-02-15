## Week 2 – Backend Development and API Setup (MollyLimpets)

### Tasks Completed
During Week 2, development focused on implementing the backend infrastructure for the MollyLimpets system. An **ASP.NET Core Web API** project was configured and structured to support modular route handling and database connectivity.

Key API routes were created for core entities, including **Items, Collections, Customers, Colours, and Locations**. Each route was designed following RESTful principles to support standard HTTP methods such as GET and POST.

Database connectivity was configured using credentials stored in `appsettings.json`, and a central database utility class was implemented to manage connections securely. Static file handling was also configured to allow the backend to serve image assets from a dedicated directory.

Additionally, **CORS (Cross-Origin Resource Sharing)** was configured to allow requests from the frontend application during development. The backend server was successfully launched and tested locally on `http://localhost:3300`.

### Why This Stage Was Important
1. **Core System Logic** – Established the foundation for all data handling.
2. **API Availability** – Enabled frontend development to begin API integration.
3. **Security Awareness** – Introduced controlled CORS policies.
4. **Scalable Structure** – Modular routes support future feature expansion.

### Technologies Used
- **ASP.NET Core Web API**
- **C#**
- **SQL Database**
- **RESTful API Design**
- **CORS Configuration**

### Tasks To Do
Further backend testing will be carried out to validate API responses. Improvements to error handling and data validation will also be implemented.

### Issues Encountered
Some configuration warnings were encountered related to framework versions and package vulnerabilities. These were noted for later resolution and did not block development progress.
