# README.txt

## Project Overview
This project is a web application developed using JSP for the front end and MySQL for the backend. The application allows users to interact with a database, performing operations such as data retrieval and manipulation.

## Software Requirements
- **IDE**: NetBeans 8.2
- **Database**: MySQL 5.7
- **Operating System**: Windows 8 and above
- **Server Deployment**: GlassFish Server

## Technologies Used
- **HTML**: Integrated in JSP for structuring text-based information in documents, including text, graphics, and hyperlinks.
- **JavaScript**: A scripting language used for developing both client and server applications. It is used on the client side to write programs executed by a web browser within the context of a web page.
- **CSS (Cascading Style Sheets)**: A style sheet language used for describing the presentation of documents written in markup languages like HTML and XHTML.
- **SQL**: Used to manipulate relational databases, including data definition and data manipulation.
- **JSP (JavaServer Pages)**: A technology for creating and maintaining dynamic-content web pages, based on the Java programming language. It consists of HTML tags and JSP tags, providing more functionality than servlets.

## Instructions to Compile and Run the Code

### Prerequisites
1. Ensure you have the following software installed:
   - NetBeans IDE 8.2
   - MySQL 5.7
   - GlassFish Server
   - Java Development Kit (JDK)

2. Set up your MySQL database:
   - Create a database and necessary tables as per the project requirements.
   - Update the database configuration in your project to match your MySQL setup (e.g., database URL, username, password).

### Steps to Compile and Run
1. **Open the Project in NetBeans:**
   - Launch NetBeans IDE.
   - Open the project by navigating to `File > Open Project` and select the project directory.

2. **Configure GlassFish Server:**
   - In NetBeans, go to `Services` tab.
   - Right-click on `Servers` and select `Add Server`.
   - Choose `GlassFish Server` and follow the prompts to add the server.

3. **Build the Project:**
   - In the `Projects` tab, right-click on your project and select `Clean and Build`.
   - Ensure there are no build errors.

4. **Deploy the Project to GlassFish Server:**
   - Right-click on your project and select `Run`.
   - NetBeans will deploy the project to the configured GlassFish Server and open it in a web browser.

5. **Access the Application:**
   - Once deployed, the application should be accessible in your web browser at `http://localhost:8080/your_project_name`.

### JDBC Connection
Ensure that the JDBC connection between the front end and back end is correctly configured in your project:
- Update the database URL, username, and password in the JDBC connection settings.
- Verify that the MySQL JDBC driver is included in your project's library.

## Additional Information
- For detailed information on configuring GlassFish Server and MySQL, refer to their respective documentation.
- If you encounter any issues, check the server logs for detailed error messages.

## Support
For any queries or support, please contact the me.

