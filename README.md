# Code Workshop
* [Version Control](https://github.com/pdzaffina/code_workshop/blob/main/README.md#version-control)
* [Requirements gathering](https://github.com/pdzaffina/code_workshop/blob/main/README.md#)
* [Solution Architecting](https://github.com/pdzaffina/code_workshop/blob/main/README.md#)
* [Code](https://github.com/pdzaffina/code_workshop/blob/main/README.md#)
* [Continuous Integration / Continuous Delivery](https://github.com/pdzaffina/code_workshop/blob/main/README.md#)
* [Automated testing](https://github.com/pdzaffina/code_workshop/blob/main/README.md#)

 ## Version control

### Purpose
Version control, also known as source control or revision control, serves a crucial role in software development. Its primary purpose is to manage changes to a project's source code over time. Here's a step-by-step explanation of its purpose:

1. **History Tracking:**
   - Source control allows developers to track the entire history of changes made to the codebase. Each change, or "commit," is documented along with information about who made the change, when it was made, and why.

2. **Collaboration:**
   - In collaborative software development, multiple developers often work on the same codebase. Source control enables seamless collaboration by allowing different developers to work on different branches or features concurrently. It helps prevent conflicts and provides mechanisms to merge changes.

3. **Code Backup:**
   - Source control acts as a reliable backup system for code. If an error occurs or an undesired change is made, developers can revert to a previous version, ensuring that the project is not irreversibly damaged.

4. **Parallel Development:**
   - Teams can work on different features or bug fixes simultaneously without interfering with each other's work. Source control provides the ability to create branches, allowing developers to isolate changes until they are ready to be integrated into the main codebase.

5. **Code Review:**
   - Many source control systems facilitate code review processes. Developers can submit their changes for review before integration, ensuring that code quality and best practices are maintained.

6. **Traceability:**
   - Source control enhances traceability by associating each change with specific issues or tasks. This helps in understanding why certain modifications were made and their impact on the overall project.

7. **Continuous Integration/Continuous Deployment (CI/CD):**
   - Source control is often integrated with CI/CD pipelines. This allows for automated testing and deployment, ensuring that changes are validated and deployed to production efficiently.

8. **Rollback Mechanism:**
   - If a release introduces unforeseen issues or bugs, source control enables a quick and controlled rollback to a stable version, minimizing downtime and potential disruptions.

### Actions
1. Sign up for [Github](https://github.com/) account


## Requirements gathering
### Purpose

Managing requirements in an agile software development project using GitHub involves leveraging its features for collaboration, issue tracking, and documentation. Here are step-by-step instructions:

1. **Create a Repository:**
   - Start by creating a new GitHub repository dedicated to your agile project. This will serve as the central repository for all your project-related information.

2. **Establish Project Structure:**
   - Organize your repository with a clear structure. You might create folders for documentation, user stories, acceptance criteria, and any other relevant information. This ensures a systematic arrangement of project artifacts.

3. **Issues for User Stories:**
   - Use GitHub Issues to represent user stories. Each user story becomes an issue. Include a clear title, description, and labels for categorization (e.g., enhancement, feature, etc.).
   - A user story is a concise description of a feature from an end-user perspective. It typically follows the format: "As a [type of user], I want [an action] so that [benefit/value]." Here's an example:
     -  **User Story:**
       - "As a registered user, I want to be able to reset my password so that I can regain access to my account in case I forget my login credentials."
     - **Explanation:**
       - **As a [type of user]:** In this case, it's a "registered user." This specifies the category of users for whom the feature is intended.
  
       - **I want [an action]:** The desired action is "to be able to reset my password." This describes the functionality or behavior that the user is requesting.

       - **So that [benefit/value]:** The reason behind the user's request is "so that I can regain access to my account in case I forget my login credentials." This articulates the value or benefit that the user expects from the proposed feature.

    - This user story is clear, specific, and focused on the user's needs. It sets the stage for the development team to understand the context, purpose, and expected outcome of the requested feature, making it easier to plan and implement the necessary functionality.

4. **Labels for Prioritization:**
   - Utilize labels to prioritize user stories. Labels like "high priority," "medium priority," or "low priority" help in identifying and sorting issues based on their importance.

5. **Assignees and Milestones:**
   - Assign user stories to specific team members by using the "Assignees" field. Additionally, use GitHub milestones to group related user stories together and track progress over specific timeframes, such as sprints.

6. **Enhanced Descriptions:**
   - Provide detailed descriptions for each user story. Include acceptance criteria, constraints, and any additional information necessary for understanding and implementing the requirements.

7. **Discussion and Collaboration:**
   - Leverage the discussion section within each issue to facilitate collaboration. Team members can ask questions, provide feedback, and engage in discussions related to specific user stories.

8. **Use Projects for Sprint Planning:**
   - GitHub Projects can be used to create boards that represent your agile sprints. Create columns for "To Do," "In Progress," and "Done." Move issues across these columns as they progress through the sprint.

9. **Pull Requests for Changes:**
   - If a user story requires changes or updates, create a new branch, make the necessary modifications, and submit a pull request. This allows for code review and discussion before merging changes into the main branch.

10. **Documentation in the Wiki:**
    - GitHub provides a Wiki feature where you can document additional project-related information, such as requirements documentation, system architecture, and any other relevant details.

11. **Continuous Integration (Optional):**
    - Integrate GitHub Actions or other CI tools to automate testing and ensure that the implemented user stories meet the acceptance criteria before merging into the main branch.

12. **Review and Retrospective:**
    - At the end of each sprint or iteration, conduct a review of completed user stories and hold a retrospective to identify improvements for the next iteration.

By following these steps, you can effectively use GitHub as a collaborative platform for managing requirements in an agile software development project, promoting transparency, collaboration, and efficient tracking of project progress.

### Actions
1. Brainstorm a list of things you will need for your project.
2. Create User Stories for the first 3 or 4 to get a feel for the process.

## Solution Architecting
## Code
## Continuous Integration / Continuous Delivery
## Automated testing
