# Project-3-CRUD-functionality-for-Web-Application-management

Project Overview

In this project, I enhanced and improved an existing web application by implementing architectural patterns and adhering to coding principles. The primary focus was on restructuring the application to promote better separation of concerns and improve maintainability.

1. Repository Pattern Implementation:

Project Repository: Created a repository class dedicated to handling all data access operations related to Projects.
Client Repository: Created a repository class dedicated to handling all data access operations related to Clients.

2. Controller Refactoring:

Transferred all data access operations from the Project Controller to the Project Repository class.
Transferred all data access operations from the Client Controller to the Client Repository class.

3. Integration of Repositories:

Implemented the use of the Project Repository within the Project Controller, replacing the direct data access operations with repository calls.
Implemented the use of the Client Repository within the Client Controller, ensuring that all data operations are now handled through the repository pattern.
These changes enhance the application's structure, making it more modular, testable, and easier to maintain.

reference list: https://github.com/SelloNkitseng/CMPG323-Project-3-30776538/blob/main/Reference%20list%20document.docx  
