# Milestone 2

**Table of Contents**
1. Task & Schedule Management
    - [Work Breakdown Structure](#work-breadown-structure)
    - [Gantt Chart  & Network Diagram](#gantt-chart--network-diagram)
1. [Requirements](#requirements)
1. [Use Cases](#use-cases)
1. [Use Case Diagram](#use-case-diagram)
1. [Research on other systems](#research-on-other-systems)
1. [API Descriptions](#api-descriptions)

## Work Breakdown Structure

| Task ID | Task Name | Duration (hours) | Start Date | Finish Date | Predecessors |
|---------|-----------|-----------------|------------|-------------|--------------|
| 1       | Project Initiation | 8 | 10/01/2023 | 10/02/2023 | - |
| 1.1     | Define Project Scope and Objectives | 4 | 10/01/2023 | 10/01/2023 | 1 |
| 1.2     | Identify Project Stakeholders | 4 | 10/02/2023 | 10/02/2023 | 1 |
| 2       | Requirements Gathering Phase | 40 | 10/03/2023 | 10/09/2023 | 1.1, 1.2 |
| 2.1     | Define Data Collection Methodologies | 16 | 10/03/2023 | 10/05/2023 | 2 |
| 2.1.1   | Conduct Interviews with Stakeholders | 8 | 10/03/2023 | 10/04/2023 | 2.1 |
| 2.1.2   | Collect Survey Responses | 8 | 10/05/2023 | 10/05/2023 | 2.1 |
| 2.2     | Analyze Legal and Compliance Requirements | 12 | 10/06/2023 | 10/07/2023 | 2.1, 2.1.2 |
| 2.2.1   | Review Privacy Regulations | 6 | 10/06/2023 | 10/06/2023 | 2.2 |
| 2.2.2   | Review Security Standards | 6 | 10/07/2023 | 10/07/2023 | 2.2 |
| 3       | Requirements Analysis and Documentation | 30 | 10/10/2023 | 10/16/2023 | 2.2.2 |
| 3.1     | Analyze Stakeholder Input | 12 | 10/10/2023 | 10/12/2023 | 3 |
| 3.1.1   | Analyze Interview Data | 6 | 10/10/2023 | 10/11/2023 | 3.1 |
| 3.1.2   | Analyze Survey Data | 6 | 10/12/2023 | 10/12/2023 | 3.1 |
| 3.2     | Document Functional Requirements | 18 | 10/13/2023 | 10/16/2023 | 3.1.1, 3.1.2 |
| 4       | Database Design and Implementation | 50 | 10/17/2023 | 10/26/2023 | 3.2 |
| 4.1     | Define Database Schema | 20 | 10/17/2023 | 10/21/2023 | 4 |
| 4.1.1   | Define Tables and Relationships | 12 | 10/17/2023 | 10/19/2023 | 4.1 |
| 4.1.2   | Define Data Entry Rules | 8 | 10/20/2023 | 10/21/2023 | 4.1 |
| 4.2     | Database Implementation | 30 | 10/22/2023 | 10/26/2023 | 4.1.1, 4.1.2 |
| 4.2.1   | Create Database Tables | 16 | 10/22/2023 | 10/24/2023 | 4.2 |
| 4.2.2   | Implement Data Entry Rules | 14 | 10/25/2023 | 10/26/2023 | 4.2 |
| 5       | User Interface Design and Development | 70 | 10/27/2023 | 11/09/2023 | 4.2.2 |
| 5.1     | Design User Interface Mockups | 30 | 10/27/2023 | 11/02/2023 | 5 |
| 5.1.1   | Create Mockups for Main Pages | 18 | 10/27/2023 | 10/31/2023 | 5.1 |
| 5.1.2   | Gather Feedback on Mockups | 12 | 11/01/2023 | 11/02/2023 | 5.1 |
| 5.2     | Develop User Interface | 40 | 11/03/2023 | 11/09/2023 | 5.1.2 |
| 5.2.1   | Implement Main Page UI | 24 | 11/03/2023 | 11/07/2023 | 5.2 |
| 5.2.2   | Implement Feedback-Driven Re visions | 16 | 11/08/2023 | 11/09/2023 | 5.2.1 |
| 6       | Backend Development | 90 | 11/10/2023 | 11/27/2023 | 5.2.2 |
| 6.1     | Develop Core System Logic | 40 | 11/10/2023 | 11/17/2023 | 6 |
| 6.1.1   | Implement User Authentication | 18 | 11/10/2023 | 11/13/2023 | 6.1 |
| 6.1.2   | Implement Data Handling Functions | 22 | 11/14/2023 | 11/17/2023 | 6.1 |
| 6.2     | Integrate Database Functionality | 30 | 11/18/2023 | 11/24/2023 | 6.1.2 |
| 6.2.1   | Integrate User Data Handling | 16 | 11/18/2023 | 11/21/2023 | 6.2 |
| 6.2.2   | Integrate Reporting Functionality | 14 | 11/22/2023 | 11/24/2023 | 6.2.1 |
| 6.3     | Implement Security Measures | 20 | 11/25/2023 | 11/27/2023 | 6.2.2 |
| 7       | Integration and Testing | 50 | 11/28/2023 | 12/10/2023 | 6.3 |
| 7.1     | Integrate UI, Backend, and Database | 30 | 11/28/2023 | 12/04/2023 | 7 |
| 7.1.1   | Integrate User Interface and Backend | 18 | 11/28/2023 | 12/01/2023 | 7.1 |
| 7.1.2   | Integrate Database Functionality | 12 | 12/02/2023 | 12/04/2023 | 7.1.1 |
| 7.2     | Conduct System Testing | 20 | 12/05/2023 | 12/09/2023 | 7.1.2 |
| 7.2.1   | Develop Testing Scenarios | 10 | 12/05/2023 | 12/07/2023 | 7.2 |
| 7.2.2   | Perform System Testing | 10 | 12/08/2023 | 12/09/2023 | 7.2.1 |
| 7.3     | Bug Fixing and Final Testing | 10 | 12/10/2023 | 12/10/2023 | 7.2.2 |
| 8       | Security and Compliance Implementation | 30 | 12/11/2023 | 12/15/2023 | 7.3 |
| 8.1     | Data Encryption and Security Measures | 20 | 12/11/2023 | 12/13/2023 | 8 |
| 8.2     | Compliance with Privacy Regulations | 10 | 12/14/2023 | 12/15/2023 | 8.1 |
| 9       | Training Material Development | 20 | 12/16/2023 | 12/19/2023 | 8.2 |
| 9.1     | Create Training Modules | 10 | 12/16/2023 | 12/18/2023 | 9 |
| 9.2     | Develop User Guides | 10 | 12/19/2023 | 12/19/2023 | 9.1 |
| 10      | User Training | 40 | 12/20/2023 | 12/28/2023 | 9.2 |
| 10.1    | Develop Training Schedule | 15 | 12/20/2023 | 12/23/2023 | 10 |
| 10.2    | Conduct Training Sessions | 25 | 12/24/2023 | 12/28/2023 | 10.1 |
| 11      | System Rollout | 20 | 12/29/2023 | 01/01/2024 | 10.2 |
| 11.1    | Pre-Rollout Checklist | 10 | 12/29/2023 | 12/31/2023 | 11 |
| 11.2    | Launch System to Users | 10 | 01/01/2024 | 01/01/2024 | 11.1 |
| 12      | Project Closure and Evaluation | 16 | 01/02/2024 | 01/05/2024 | 11.2 |
| 12.1    | Evaluate Project Success | 8 | 01/02/2024 | 01/03/2024 | 12 |
| 12.2    | Document Lessons Learned | 8 | 01/04/2024 | 01/05/2024 | 12.1 |
| 13      | Documentation and Knowledge Transfer | 36 | 01/06/2024 | 01/10/2024 | 12.2 |
| 13.1    | Create User Manuals | 16 | 01/06/2024 | 01/08/2024 | 13 |
| 13.2    | Develop Technical Documentation | 20 | 01/09/2024 | 01/10/2024 | 13.1 |
| 14      | Post-Implementation Review | 24 | 01/11/2024 | 01/14/2024 | 13.2 |
| 14.1    | Gather User Feedback | 12 | 01/11/2024 | 01/12/2024 | 14 |
| 14.2    | Evaluate System Performance | 12 | 01/13/2024 | 01/14/2024 | 14.1 |
| 15      | Project Closure and Reporting | 20 | 01/15/2024 | 01/19/2024 | 14.2 |
| 15.1    | Finalize Project Documentation | 10 | 01/15/2024 | 01/17/2024 | 15 |
| 15.2    | Generate Project Report | 10 | 01/18/2024 | 01/19/2024 | 15.1 |

## Gantt Chart & Network Diagram
![gantt chart](/img/wbs(1).png)

[Downloadable Project Management File](/documents/WIN%20Belize%20Project.mpp)

## Requirements

### Functional Requirements:

1. **Data Entry and Storage:**
   - The system will be able to allow authorized users to enter and store data related to violence against women, health issues, and employment.
   - The system will organize and categorize the entered data based on specified criteria.

2. **Search and Retrieval:**
   - The system will provide a search functionality enabling users to search for information based on various parameters such as date, category, location, and keywords.
   - The system will allow users to retrieve relevant data efficiently and in a user-friendly format.

3. **Reporting:**
   - The system will generate comprehensive reports based on the entered data, categorizing and summarizing the information for analysis and decision-making purposes.
   - The system will allow users to customize and export reports in various formats (e.g., PDF, Excel) for further use and sharing.

4. **User Authentication and Authorization:**
   - The system will authenticate users at login and provide access based on their roles and permissions within the organization.
   - The system will allow administrators to manage user roles and permissions.

5. **User Interface:**
   - The system will provide an intuitive and user-friendly interface for easy navigation and interaction.
   - The system will be accessible on multiple devices (desktops, tablets, smartphones) to accommodate varying user preferences.

### Non-Functional Requirements:

1. **Performance:**
   - The system will respond to user actions swiftly, ensuring minimal latency even during peak usage times.
   - The system will support a large number of concurrent users without a significant degradation in performance.

2. **Security:**
   - The system will ensure data security by employing encryption techniques to protect sensitive information during storage and transmission.
   - The system will implement user authentication and access controls to prevent unauthorized access and maintain confidentiality.

3. **Scalability:**
   - The system will be designed to scale seamlessly as the volume of data and user base grows, ensuring continued performance and reliability.

4. **Reliability and Availability:**
   - The system will have a robust backup and recovery mechanism to ensure data integrity and availability in case of failures or disruptions.
   - The system will strive for high uptime, aiming for a minimum of 99% availability to ensure users can access the system whenever needed.

5. **Compliance:**
   - The system will adhere to relevant data privacy and security regulations, ensuring compliance with local and international laws.
   - The system will support auditability, allowing tracking and monitoring of user activities for compliance purposes.
Certainly! Cultural non-functional requirements are crucial for ensuring the system aligns with the cultural context and norms of the target user base. Here are additional non-functional requirements considering cultural aspects:

1. **Language and Localization:**
   - The system will support multiple languages to cater to users from diverse linguistic backgrounds, especially considering Belize's multicultural society.
   - The system will provide an option for users to select their preferred language for the interface and data entry.

2. **Cultural Sensitivity:**
   - The system will promote cultural sensitivity by ensuring that the language, imagery, and references used in the system do not offend or exclude any specific cultural group.
   - The system will incorporate diverse perspectives and sensitivities related to gender, ethnicity, and cultural practices in its design and content.

3. **Inclusivity and Diversity:**
   - The system will embrace inclusivity by accommodating various cultural perspectives, traditions, and beliefs, ensuring that the platform is accessible and welcoming to all users, regardless of their cultural backgrounds.
   - The system will avoid any discriminatory practices, biases, or stereotypes based on cultural attributes or backgrounds.

4. **User Training and Cultural Sensitization:**
   - The system will include training modules that educate users and stakeholders about cultural nuances and sensitivities relevant to the subject matter, fostering understanding and respect.
   - The system will promote cultural awareness and understanding among users to enhance communication and collaboration within the platform.

5. **Community Involvement:**
   - The system will encourage community involvement and engagement, recognizing the importance of community values and customs in addressing women's issues, health, and employment.
   - The system will support collaborative efforts with local communities, organizations, and cultural leaders to ensure the platform's relevance and effectiveness within the Belizean cultural context.

## Use Cases
### Use Case 1: User Registration and Profile Creation
**Use Case Number:** UC-1  
**Use Case Name:** User Registration and Profile Creation  
**Description:** The system allows users to register on the Tech Connect platform, creating a profile to access mentorship, resources, and educational content.  
**Primary Actor:** User  
**Priority:** High  
**Type:** External  
**Trigger:** User's decision to join the Tech Connect platform

**Major Inputs:**
- User details (name, contact information) - **User**
- Desired skills and interests - **User**
- Educational background - **User**

**Major Outputs:**
- User profile created in the database - Stored in the **Users database**

**Basic Flow:**
1. **User** accesses the registration page on the Tech Connect mobile application.
2. **User** provides necessary information, including name, contact details, skills, and interests.
3. **User** sets up a password and security information.
4. **System** validates the information and creates a user profile in the "Users" database.
5. **User** receives a confirmation email or notification.

### Use Case 2: Mentor-Matching Process
**Use Case Number:** UC-2  
**Use Case Name:** Mentor-Matching Process  
**Description:** The system facilitates the matching of mentors with mentees based on skills, interests, and availability.  
**Primary Actor:** System  
**Priority:** High  
**Type:** Internal  
**Trigger:** User's request for mentorship

**Major Inputs:**
- User's skills, interests, and availability -  **User**
- Mentor database with skills and availability - Stored in the **Mentors database**

**Major Outputs:**
- Matched mentor and mentee pairs - Notification sent to the **Mentor** & **Mentee**

**Basic Flow:**
1. **User** expresses the desire for mentorship through the Tech Connect app.
2. **System** collects the user's skills, interests, and availability.
3. **System** queries the **Mentors database** for suitable mentors based on criteria.
4. **System** notifies potential mentors and mentees about the match.
5. **Mentors** and **Mentees** review each other's profiles and confirm the match.

### Use Case 3: Accessing Educational Content
**Use Case Number:** UC-3  
**Use Case Name:** Accessing Educational Content  
**Description:** The system allows users to access a selection of tech-related educational content on the Tech Connect platform.  
**Primary Actor:** User  
**Priority:** High  
**Type:** External  
**Trigger:** User's decision to learn

**Major Inputs:**
- User's preferred tech topics - Selected by the **User**
- Educational content database - Stored in the **Educational Content database**
- 

**Major Outputs:**
- User access to relevant educational materials - Displayed to the **User** on the app.

**Basic Flow:**
1. **User** navigates to the educational content section on the app.
2. **User** selects preferred tech topics or courses.
3. **System** queries the "Educational Content" database for relevant materials.
4. **System** displays a list of available resources to the **User**.
5. **User** selects and accesses the chosen educational content.

### Use Case 4: Reporting Technical Issues
**Use Case Number:** UC-4  
**Use Case Name:** Reporting Technical Issues  
**Description:** The system allows users to report any technical issues or glitches they encounter while using the Tech Connect app.  
**Primary Actor:** User  
**Priority:** Medium  
**Type:** External  
**Trigger:** User encounters a technical problem

**Major Inputs:**
- User's description of the issue - Entered by the **User**
- Screenshots or error logs (if applicable) - Uploaded by the **User**

**Major Outputs:**
- Technical support ticket created - Logged in the **Support Tickets database**

**Basic Flow:**
1. **User** identifies a technical issue within the app.
2. **User** accesses the support or help section on the app.
3. **User** describes the issue and attaches any relevant screenshots or error logs.
4. **System** generates a technical support ticket.
5. **User** receives a confirmation message with the ticket number.



## Use Cases Diagram

## Research on other systems

## API Descriptions
