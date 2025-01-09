
# **BEMP Project**

### Project Description

This **Department and Project Management System** streamlines budget tracking, project management, and resource allocation. Built with **Spring Boot (Maven)** and **MSSQL** for the backend, and **React**, **NextUI**, and **ECharts** for the frontend, it offers CRUD operations, real-time budget updates, and interactive dashboards. Ideal for optimizing financial and project workflows in organizations.

## Installation
## Backend
 To set up and run the Spring Boot backend, follow these steps:
 1. ### **Install Maven**
 Download and install Maven from the [official website](https://maven.apache.org/).

Add Maven to your system's **PATH**:

1-Search for Edit the system environment variables in the Start menu and open it.

2-In the System Properties window, click on the Environment Variables button.

3-Under System variables, find the Path variable and click Edit.

4-Click New and add the path where Maven was installed (e.g., C:\Program Files\apache-maven\bin).

5-Click OK to save the changes.

Verify the installation:


```bash
mvn -v
```

2. ### **Build the Project:**
```bash
mvn clean install
```
3. ### **Configure the Database:**

Open the application.properties file located in src/main/resources.

Update the following properties with your Microsoft SQL Server credentials:
```bash
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=your-database-name;instanceName=SQLEXPRESS;trustServerCertificate=true;encrypt=false
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.datasource.driver-class-name=com.microsoft.sqlserver.jdbc.SQLServerDriver
spring.application.name=restapi
server.port=8081
```
4. ### **Run the Spring Boot Application for the backend:**
```bash
mvn spring-boot:run
```

## Frontend
1. ### **Install Node.js:**

Download [Node.js](https://nodejs.org/)

2. ### **Deleting the node_modules and package-lock.json,then reinstalling them**

1-Deleting the files for the dependencies to work on your laptop
```bash
del package-lock.json && rmdir /s /q node_modules 
```
2-Reinstall them to work on your laptop
```bash
npm install
```

3. ### **Run the React-app for the frontend:**

```bash
npm run dev
```

## Demo

[Link For The Demo Video](https://drive.google.com/drive/folders/1s_T6uwSWIF5L4_SEDUsJj5-uWGauNrt7)


## Authors

- [@YahiaSonbol](https://www.linkedin.com/in/yahia-sonbol/)
- [@RamzyBakir](https://www.linkedin.com/in/ramzy-bakir/)
- [@YoussefHazem](https://www.linkedin.com/in/youssefsharaawy/)
- [@YoussefAhmed](https://www.linkedin.com/in/youssef-abou-elwaf/)
- [@MahmoudElShikha](https://www.linkedin.com/in/mahmoud-elshikha/)



