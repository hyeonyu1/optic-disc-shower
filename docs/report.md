# Project Management

## **Sprint 1 Report**

All of the following tasks were completed in Sprint 1:

- Create use cases or user stories (2H): Use cases and user stories were created to define the requirements of the project. This included identifying the different types needs of the user, and the goals of the project.
- Create project plan (1H): A project plan was created to outline the steps that need to be taken to complete the project. This included identifying the tasks, milestones, and resources that are needed. Biweekly sprint was decided.
- Clear responsibility assignment (.25H): Responsibilities were assigned to each team member for the different tasks of the project to cover all tasks. The team is divided into backend and frontend.
- Create project overview description (0.5H): A project overview description was created to summarize the project, its goals, and the benefits that it will provide.
- Create meeting minutes (.25H): Meeting minutes were created to document the decisions that were made during the sprint. This helped to keep the team on track and to ensure that everyone was aware of the progress of the project.
- Create mkdocs (0.5H): Mkdocs was used to create documentation for the project. This documentation included the use cases, user stories, project plan, project overview description, and meeting minutes.

### **Meeting Minutes**

Sprint 1 had 2 meetings. First meeting was done to create user stories and to create a project plan which was around 3 hours. The second meeting was much shorter, roughly half a hour to clear responsibility and to create meeting minutes.

Overall, Sprint 1 was a success. All of the planned tasks were completed and the team is on track to meet the overall goals of the project.

## **Sprint 2 Report**

All of the following tasks were completed in Sprint 2:

- Plan documented in the git issue tracker (.5H): The sprint plan was documented in the git issue tracker. This ensures a clear plan for the sprint and ensuring the completion of required tasks
- Create project plan for sprint 3, 4 and 5 (1H): Project plans were created for Sprints 2, 3, and 4. This helped to ensure that the team is on track to meet the overall goals of the project.
- Look for specific library for react (2H): A specific library for React was found and evaluated.

  | Module Name                         | Version           |
  | ----------------------------------- | ----------------- |
  | `@fortawesome/fontawesome-svg-core` | `^6.4.2`          |
  | `@fortawesome/free-solid-svg-icons` | `^6.4.2`          |
  | `@fortawesome/react-fontawesome`    | `^0.2.0`          |
  | `@reduxjs/toolkit`                  | `^1.9.7`          |
  | `@testing-library/jest-dom`         | `^5.17.0`         |
  | `@testing-library/react`            | `^13.4.0`         |
  | `@testing-library/user-event`       | `^13.5.0`         |
  | `axios`                             | `^1.5.1`          |
  | `csv`                               | `^6.3.6`          |
  | `express`                           | `^4.18.2`         |
  | `font-awesome`                      | `^4.7.0`          |
  | `fs`                                | `^0.0.1-security` |
  | `multer`                            | `^1.4.5-lts.1`    |
  | `papaparse`                         | `^5.4.1`          |
  | `react`                             | `^18.2.0`         |
  | `react-dom`                         | `^18.2.0`         |
  | `react-dropzone`                    | `^14.2.3`         |
  | `react-redux`                       | `^8.1.3`          |
  | `react-router-dom`                  | `^6.16.0`         |
  | `react-scripts`                     | `5.0.1`           |
  | `react-typical`                     | `^0.1.3`          |
  | `reactjs-popup`                     | `^2.0.6`          |
  | `redux`                             | `^4.2.1`          |
  | `web-vitals`                        | `^2.1.4`          |

- Set up project starter (1H): A project starter was set up. This included setting up the development environment and creating the basic structure for the project.
- US 6.01 - Secure Ophthalmologist Authentication (2H): User story 6.01, which is to implement secure ophthalmologist authentication, was completed.

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

- US 7.01 - Secure Logout for Ophthalmologists (1H): User story 7.01, which is to implement secure logout for ophthalmologists, was completed. This included implementing a logout function that removes the ophthalmologist's authentication token from the browser.

  - **Logout Process:**
    - 1 **User Clicks Logout:** When a user wants to log out, they click the "Logout" button in the application's header.
    - 2 **Logout Actions:** Clicking the "Logout" button triggers the following actions:
      - The application marks the user as logged out.
      - Clears the user's full name.
      - Updates the application's local storage to reflect the user's logged-out status.
    - 3 **Redirecting to Home:** After logging out, the user is automatically redirected to the home page.
    - **Header Component:** The application's header component displays the user's full name when they are logged in and provides a "Logout" button for easy access to the logout functionality.

- US 1.01 - Fundus Image Upload (1H): User story 1.01, which is to implement fundus image upload, was completed. This included implementing a way for ophthalmologists to upload fundus images to the system.

  - When a user clicks the "Upload Folder" button, it's like opening a window on their computer to select a folder containing images. The code checks if the selected folder contains valid image files (e.g., jpg, png). If the folder is valid, it processes the images in it and shows a success message. If not, it shows an error message.
  - **Displaying Images:**
    After successful upload, the code displays the uploaded images on the webpage. Each image comes with its name.

- Create meeting minutes and update mkdocs (1H): Meeting minutes were created to document the decisions that were made during sprint planning, daily stand-up meetings, sprint review meeting, and sprint retrospective meeting. This helped to keep the team on track and to ensure that everyone was aware of the progress of the project.

### **Meeting Minutes**

We had one meeting and one in class session during this sprint. In class, project plan for sprint 3,4, and 5 were created and git issues were created. The other meeting was for 4 and a half hours where we got together to code. Most important thing to note is that during the meeting, we discuessed and the backend development has been switched to Node.js instead of Python. There are two main reasons for this switch

Overall, Sprint 2 was a success. All of the planned tasks were completed and on track to meet the overall goals of the project. Three user stories have been completed, which can be seen as a significant milestone.

## **Sprint 3 Report**

All the following taskls were completed in Sprint 3.

- US 2.01 - Optic Disc Segmentation: The segmentation algorithm of the optic disc is implemented using a deep learning model which has been developed before.
- US 3.01 - Organize Results - All results are organized in a grid format.

### **Meeting Minutes**

Meeting minutes were diligently recorded, summarizing discussions and decisions made during the sprint. Effective communication within the team was maintained, and any arising issues were promptly addressed.

Overall, Sprint 3 was executed successfully, meeting the set goals and moving the project forward.

## **Sprint 4 Report**

Sprint 4 focused on achieving a prototype that includes all "should have" user stories. The team effectively worked towards this goal, meeting the outlined tasks:

- The team ensured that the git issue tracker was up to date, providing a comprehensive overview of the project's status and any outstanding issues.
- 4.01 - User Story 4.01 was successfully implemented, allowing the display of segmentation results. This is a crucial feature for users to visually assess the outcomes of the segmentation process.
- US 4.02 - Display Past Segmentation Results: User Story 4.02, involving the display of past segmentation results, was also successfully implemented. This feature enhances the usability of the software by providing historical data.
- US 4.03 - Display Multiple Segmentation Results: The team accomplished the implementation of User Story 4.03, enabling the display of multiple segmentation results. This contributes to the versatility of the software.

### **Meeting Minutes**

Meeting minutes were consistently created, ensuring that all team members were informed about discussions and decisions made during the sprint.

Sprint 4 was a success, with the team achieving the goal of creating a prototype that includes all "should have" user stories.

## **Sprint 5 Report**

Sprint 5 was dedicated to a mid-project checkover, evaluating progress and addressing any necessary adjustments. The team successfully accomplished the following tasks:

- The team ensured the git issue tracker was up-to-date, reflecting the current status of the project and providing a clear overview of any outstanding issues.
- US 5.01 - Reset Segmentation: User Story 5.01, involving the ability to reset segmentation, was implemented successfully. This feature adds flexibility to the software by allowing users to start fresh when needed.
- Frontend Code Stylesheet Refactoring: The team executed frontend code stylesheet refactoring, enhancing the code's structure and maintainability. This contributes to the overall efficiency of the software.

### **Meeting Minutes**

Meeting minutes were consistently created, documenting discussions and decisions made during the sprint. Effective communication and collaboration within the team were maintained.

Sprint 5 provided a valuable mid-project evaluation, ensuring that the project was on track and addressing any adjustments needed for a successful outcome.

## **Sprint 6 Report**

Sprint 6 focused on implementing requested changes and finalizing the project. The team effectively completed the following tasks:

- The team ensured the git issue tracker was updated, reflecting the latest changes and addressing any remaining issues.
  - US 8.01 - Make Changes Updated on Inspection: User Story 8.01, involving making changes identified during inspection, was successfully implemented. This step is crucial for addressing any final adjustments or improvements. This includes the following:
    - Creation of a separate popup block with the details of every image.
    - Creation of a pseudo-symptom checkbox with showing the final results as it should be after the entire procedure is done.

### **Meeting Minutes**

The team successfully completed the project report, summarizing the overall project, its goals, achievements, and lessons learned.

Sprint 6 marked the final stage of the project, with all requested changes implemented and the project successfully finalized.


## **Application Walk Through**
The application workflow is described below. For the website diagram of the project, click [here](web-diagram.md).

1. Home Page (before login): The user is first greeted with a home page that has a search bar and a login button.
2. Login Page: By clicking on the login button, the user is redirected to the login page where they need to fill in their credentials and click on the login button to access their account.
3. Home Page (after login): After successful authentication, users are automatically redirected back to an enhanced version of the home page where they can now access the complete dashboard, including the names and folders of the patients.
4. Dashboard of Selected Patient: Users can click on a folder icon which takes them to a dashboard containing multiple images related to selected patients.
5. Details of Selected Image: Clicking on any image opens up detailed information about that particular image.
6. Segment Page: There’s also an option called “Segment” on the navigation bar which users can click. It leads them to a segment page where they can upload images for segmentation.
    - Users upload an image by clicking on the “dropzone” area and selecting an image from their device.
    - After selecting an image, users have options like “Reset”, “Reset All” before finally submitting it by clicking on “Submit” button.
    - Once submitted, users need to click on “Segment” button for segmentation process initiation.
    - The segmented images are then displayed after processing, then it waits for 2 seconds before automatically redirecting to the homepage.
8. There is also the "Search Bar" in the homepage wherethe user can search by name of patients, and it works on key press.


## **Short API Documentation**

The following APIs were used for the entire backend of the project.

| Method | Endpoint              | Description                                         |
| ------ | --------------------- | --------------------------------------------------- |
| POST   | /image                | Upload images for processing                        |
| POST   | /getSelectedImageName | Set the selected image name for display             |
| GET    | /displaySymptoms      | Display segmented images based on the selected name |
| POST   | /reset                | Reset the images in the processing folder           |
| GET    | /segment              | Run image segmentation and return results           |
| POST   | /getImages            | Retrieve image paths based on document and patient  |
| GET    | /displayImages        | Display images based on received paths              |
