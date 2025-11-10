![image](https://github.com/DiscordPanda/Innov8tors/assets/158240988/e92145fc-df48-4338-8780-70aa4ae24196)


The purpose behind this this program is to allow a user to create a list of important tasks that adhers to their schedule, improve time management, and increase focus.
It will allow you to create, update, save, delete, and add timers to tasks. The number of tasks you can create is unlimited.

This application is accessible to any user!


**This is a web-based application, so your login and password is essential to access your stored tasks.**


In order to use the application, you must register your information by entering your first and last name, email address, and a unique password. 
![image](https://github.com/DiscordPanda/Innov8tors/assets/158240988/13c261aa-b095-4c3a-b7bc-e23d94424bf3)


Once your login is created, you will have access to your own personalized to-do list and all of the information entered will be saved and secured, even if you log out!

![image](https://github.com/DiscordPanda/Innov8tors/assets/158240988/ed7b4975-a53f-47ef-b423-d90fdea22270)



**Features**

Login: Create a username and password to keep all of your tasks stored in one place.
![image](https://github.com/DiscordPanda/Innov8tors/assets/158240988/33e6b3da-cca6-43a1-8f74-dc08b78ed4e7)


Organization: All tasks are listed on a sinlge page and organized by priority.

Timer: Set a timer for each task based on priority. Once the timer is complete, you will be notified with a custom sound to indicate completion, as well as a pop-up banner. A timer may also be reset if more time is needed to complete a task.

Editing: Details of each task can be edited and updated based on user needs at anytime

Deletion: Tasks that are completed can be checked off at will, clearing up space to add more tasks.




# 📋 Full-Stack To-Do App with User Authentication

## 🚀 Overview

This is a **full-stack web application** designed to help users manage their personal and professional tasks efficiently. It emphasizes time management, focus improvement, and organization by providing a persistent, personalized to-do list.

The application includes robust user authentication and utilizes a database to ensure all user data and tasks are securely saved and retrieved upon login.


## ✨ Key Features

* **User Authentication:** Secure login and registration system to give each user a personalized space for their tasks.
* **Persistent Storage:** All tasks are stored in a relational database (MySQL/SQL), ensuring data is saved even after logging out.
* **Task Management (CRUD):**
    * **Create:** Add new tasks easily.
    * **Update/Edit:** Modify the details of existing tasks at any time.
    * **Delete/Complete:** Check off or permanently remove completed tasks.
* **Priority Organization:** Tasks are listed and organized by their priority level for better focus.
* **Integrated Timer:** Set a timer for individual tasks to improve time management. Includes a custom sound and pop-up banner notification upon completion.
* **Unlimited Tasks:** Users can create an unlimited number of tasks to adhere to any schedule.

## 🛠️ Tech Stack

This application is built using a classic LAMP-stack inspired architecture:

* **Frontend:** HTML5, CSS (specifically `styles.css` and `style1.css`), JavaScript
* **Backend:** PHP (using files like `login.php` and `ToDo.php`)
* **Database:** MySQL/SQL (implied by file structure, likely for user and task data)

## ⚙️ Installation & Setup

To run this application locally, you will need a web server environment that supports PHP and MySQL, such as XAMPP, WAMP, or MAMP.

### Prerequisites

1.  A local web server environment (e.g., XAMPP).
2.  A configured MySQL database instance.

### Setup Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/PrinceShawtz/Full-stack-todo-app-with-user-login-and-database.git](https://github.com/PrinceShawtz/Full-stack-todo-app-with-user-login-and-database.git)
    cd Full-stack-todo-app-with-user-login-and-database
    ```

2.  **Server Placement:**
    Place the cloned directory into your web server's root directory (e.g., `htdocs` for XAMPP).

3.  **Database Configuration:**
    * Create a new MySQL database (e.g., `todo_db`).
    * Run the provided SQL script (`upgrade_tables_mysql_4_1_2+.sql` or similar) to set up the necessary tables for users and tasks.
    * **Crucially:** Update the database connection details within your PHP files (`login.php`, `ToDo.php`, etc.) to match your local database credentials (server name, username, password, database name).

4.  **Access the Application:**
    Open your browser and navigate to the local server path:
    ```
    http://localhost/Full-stack-todo-app-with-user-login-and-database/login.html
    ```
    You will need to register first before you can access the main to-do list page (`ToDo.html`).

## 📚 Documentation & Diagrams

The repository includes several detailed design and planning documents:

* `Entity Relationship Diagram.pdf`
* `Test Cases.pdf`
* `Use Cases & Sequence Diagrams.pdf`
* `Wireframes and Test Scenarios.pdf`

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests with improvements.

## 📄 License

*(The license information is not explicitly provided in the repository's files, but standard practice is to use a common open-source license.)*
Please refer to the repository owner for licensing details.



                                                  copyright: Innov8tors 2024
