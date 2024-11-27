

The Role-Based Access Control (RBAC) Dashboard is a modern and intuitive platform designed to manage users, roles, and permissions efficiently. Built using React with TypeScript and styled with Tailwind CSS, this dashboard provides a streamlined and secure approach for administrators to control user access within a system.

This application offers a variety of features to enhance the user management experience. You can easily create, update, and delete users, as well as assign them specific roles based on their responsibilities. The Role Management feature allows you to define and assign permissions to various roles, ensuring that each user has the appropriate level of access to the system. The system also supports dynamic role assignments, with a visual interface for managing permissions, making it both easy and intuitive for administrators to configure access rights.

The Dashboard offers real-time analytics and insights, including a comprehensive overview of the number of users per role, with interactive charts and metrics to help visualize the data. This allows administrators to quickly assess the system’s state and take necessary actions. The user interface has been designed with a mobile-first approach, ensuring that the application works seamlessly across all devices, with touch-friendly elements and adaptive layouts.

Security is at the forefront of this system. Input validation is handled using Zod to ensure that only valid data is processed, and the application also has built-in error handling mechanisms that provide clear feedback to users. The entire system is protected by Role-Based Access Control (RBAC), ensuring that only authorized users can access sensitive sections of the application. The use of Axios ensures that all API requests are made securely, with appropriate error handling and response management.

The project is developed with a clean and modern design, ensuring that the interface is both user-friendly and functional. Tailwind CSS ensures that the styling is responsive, while React Icons add a consistent and visually appealing set of icons throughout the application. The system includes advanced features like sorting, filtering, and real-time searching for users and roles, making it easier to manage large datasets. Additionally, loading states and tooltips are implemented for a better user experience, offering helpful information and ensuring smooth transitions between actions.

Getting Started

To get started with the RBAC Dashboard, first clone the repository to your local machine. Once cloned, navigate into the project directory and install the necessary dependencies with npm install. Afterward, you can start the development server by running npm run dev. This will launch the application locally at http://localhost:5173, where you can begin using the dashboard and explore its features.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Rohiitkr2416/rohit-assignment.git
cd rohit-assignment

```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Start Development Server

```bash
npm run dev
```


Project Structure

The project is structured in a clean and organized manner. The src folder contains all the core functionality of the application. Inside, the components directory holds the various React components responsible for rendering the UI, including user and role management components. The services folder is used for API communication, while the schemas folder contains the Zod validation schemas. The types directory defines TypeScript interfaces and types for better type safety throughout the application. Additionally, the assets folder stores any static files, such as images and icons.

Security and Error Handling

Security has been prioritized in the development of this dashboard. Input validation is enforced using Zod schemas, ensuring that only valid data is submitted. API requests are made securely through Axios, and any errors encountered during API calls are handled gracefully, with appropriate feedback provided to users. Role-Based Access Control ensures that each user can only access the resources assigned to their role, protecting sensitive data and functionality.

