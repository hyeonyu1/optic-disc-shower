# Project Management

## **Sprint 1 Report**

All of the following tasks were completed in Sprint 1:

* Create use cases or user stories (2H): Use cases and user stories were created to define the requirements of the project. This included identifying the different types needs of the user, and the goals of the project.
* Create project plan (1H): A project plan was created to outline the steps that need to be taken to complete the project. This included identifying the tasks, milestones, and resources that are needed. Biweekly sprint was decided. 
* Clear responsibility assignment (.25H): Responsibilities were assigned to each team member for the different tasks of the project to cover all tasks. The team is divided into backend and frontend.
* Create project overview description (0.5H): A project overview description was created to summarize the project, its goals, and the benefits that it will provide. 
* Create meeting minutes (.25H): Meeting minutes were created to document the decisions that were made during the sprint. This helped to keep the team on track and to ensure that everyone was aware of the progress of the project.
* Create mkdocs (0.5H): Mkdocs was used to create documentation for the project. This documentation included the use cases, user stories, project plan, project overview description, and meeting minutes.

### **Meeting Minutes**
Sprint 1 had 2 meetings. First meeting was done to create user stories and to create a project plan which was around 3 hours. The second meeting was much shorter, roughly half a hour to clear responsibility and to create meeting minutes. 

Overall, Sprint 1 was a success. All of the planned tasks were completed and the team is on track to meet the overall goals of the project.


## **Sprint 2 Report**

All of the following tasks were completed in Sprint 2:

* Plan documented in the git issue tracker (.5H): The sprint plan was documented in the git issue tracker. This ensures a clear plan for the sprint and ensuring the completion of required tasks
* Create project plan for sprint 3, 4 and 5 (1H): Project plans were created for Sprints 2, 3, and 4. This helped to ensure that the team is on track to meet the overall goals of the project.
* Look for specific library for react (2H): A specific library for React was found and evaluated.
    - fontawesome
    - testing-library
    - axios
    - react-dom
    - react-redux
    - react-router-dom
    - react-script
    - react
    - redux
    - web-vitals
* Set up project starter (1H): A project starter was set up. This included setting up the development environment and creating the basic structure for the project.
* US 6.01 - Secure Ophthalmologist Authentication (2H): User story 6.01, which is to implement secure ophthalmologist authentication, was completed.
    - **Login Process:**
        - 1 **User Visits Login Page:** When a user wants to access the Optic Disc Segmenter application, they start by visiting the login page.
        - 2 **Providing Credentials:** On the login page, the user enters their username and password.
        - 3 **Checking Credentials:** The application checks if the provided username and password match with any of the valid users' credentials stored in its configuration.
        - 4 **Successful Login:** If the provided credentials are correct, the application:
            - Records the user's full name.
            - Marks the user as logged in.
            - Stores this information so that the user remains logged in even after closing the application.
            - Redirects the user to the home page.
        - 5 **Error Handling:** If the credentials are incorrect, the application displays an error message. This message disappears as soon as the user starts typing in the username or password field again.

* US 7.01 - Secure Logout for Ophthalmologists (1H): User story 7.01, which is to implement secure logout for ophthalmologists, was completed. This included implementing a logout function that removes the ophthalmologist's authentication token from the browser.
    - **Logout Process:**
        - 1 **User Clicks Logout:** When a user wants to log out, they click the "Logout" button in the application's header.
        - 2 **Logout Actions:** Clicking the "Logout" button triggers the following actions:
            - The application marks the user as logged out.
            - Clears the user's full name.
            - Updates the application's local storage to reflect the user's logged-out status.
        - 3 **Redirecting to Home:** After logging out, the user is automatically redirected to the home page.
        - **Header Component:** The application's header component displays the user's full name when they are logged in and provides a "Logout" button for easy access to the logout functionality.

* US 1.01 - Fundus Image Upload (1H): User story 1.01, which is to implement fundus image upload, was completed. This included implementing a way for ophthalmologists to upload fundus images to the system.
    - When a user clicks the "Upload Folder" button, it's like opening a window on their computer to select a folder containing images. The code checks if the selected folder contains valid image files (e.g., jpg, png). If the folder is valid, it processes the images in it and shows a success message. If not, it shows an error message.
    - **Displaying Images:**
    After successful upload, the code displays the uploaded images on the webpage. Each image comes with its name.

* Create meeting minutes and update mkdocs (1H): Meeting minutes were created to document the decisions that were made during sprint planning, daily stand-up meetings, sprint review meeting, and sprint retrospective meeting. This helped to keep the team on track and to ensure that everyone was aware of the progress of the project.

### **Meeting Minutes**
We had one meeting and one in class session during this sprint. In class, project plan for sprint 3,4, and 5 were created and git issues were created. The other meeting was for 4 and a half hours where we got together to code. Most important thing to note is that during the meeting, we discuessed and the backend development has been switched to Node.js instead of Python. There are two main reasons for this switch

Overall, Sprint 2 was a success. All of the planned tasks were completed and on track to meet the overall goals of the project. Three user stories have been completed, which can be seen as a significant milestone.



## **Sprint 3 Report**

All the following taskls were completed in Sprint 3.