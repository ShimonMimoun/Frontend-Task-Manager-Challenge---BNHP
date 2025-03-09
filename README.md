**Objective**  
Develop a web-based task management application focused on the front-end, showcasing your expertise in design and modern user interface development. The application should deliver an outstanding user experience for two distinct profiles (Admin and User) while integrating with a minimal Node.js server that provides a REST API.

**Context and Constraints**  
- **Maximum Duration**: 2 days  
- **Required Technologies**:  
  - **Front-End**: React (optionally with a UI library such as Material-UI or Ant Design) - Must : Next.Js
  - **Back-End**: Node.js (using Express or another lightweight framework)  
- **Delivery**: The project must be versioned on GitHub with collaborative access granted to the user **ShimonMimoun**.  
- **Documentation**: A detailed README file must accompany the solution.

**Functional Specifications**

1. **Front-End – Task Manager**  
   - **User Interface**:  
     - Develop a modern, responsive, and elegant interface.  
     - Implement animations and transitions to enhance the experience when creating, modifying, and deleting tasks.
   - **Features**:  
     - Ability to add, modify, and delete tasks.  
     - Mark tasks according to their status (e.g., in progress, completed, etc.).  
     - Dynamically display tasks filtered by the user's role.
   - **Role Management**:  
     - **Admin**: Full access to all features (global task management).  
     - **User**: Limited access, allowing them to view and update only their own tasks.

2. **Back-End – Minimal Node.js API**  
   Implement a basic Node.js server to support the front-end application by providing the following endpoints (note that the evaluation will primarily focus on the front-end, and backend best practices will not be rigorously assessed):
   - **POST /api/login**: Authenticate and generate a JWT token.  
   - **GET /api/tasks**: Retrieve the list of tasks, filtered according to the user's role.  
   - **POST /api/tasks**: Create a new task.  
   - **PUT /api/tasks/:id**: Update an existing task.  
   - **DELETE /api/tasks/:id**: Delete a task.

**Evaluation Criteria**  
- **Design and User Experience**:  
  - Visual quality and ergonomics of the interface.  
  - Smoothness of animations and transitions.
- **Front-End Features**:  
  - Efficient task management and a clear distinction between Admin and User roles.
- **Integration with the Back-End**:  
  - Functionality of the API endpoints and seamless integration with the front-end.
- **Code Quality and Documentation**:  
  - Clarity and organization of the code, adherence to standards, and the quality of the README.
