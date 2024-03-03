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
| 1       | Project Initiation | 8 | 2/11/24| 2/1124 | - |
| 2     | Define Project Scope and Objectives | 4 | 2/12/24 | 2/12/24 | 1 |
| 3     | Identify Project Stakeholders | 2 | 2/12/24 | 2/12/24 | 1 |
| 4       | Requirements Gathering Phase | 10 | 2/12/24 | 2/13/24 | 2,3 |
| 5     | Define Data Collection Methodologies | 12 |  2/13/24 | 2/15/24| 4 |
| 6   | Conduct Interviews with Stakeholders | 8 | 2/15/24|2/16/24 |5 |
| 7   | Collect Survey Responses | 6 | 2/15/24 |2/15/24 | 5 |
| 8     | Analyze Legal and Compliance Requirements | 4 | 2/16/24 | 12/16/24 | 5,7 |
| 9   | Review Privacy Regulations | 4 | 2/16/24 | 2/16/24 |8 |
| 10   | Review Security Standards | 4 | 10/07/2023 | 10/07/2023 | 8 |
| 11       | Requirements Analysis and Documentation |10| 10/10/2023 | 10/16/2023 | 10 |
| 12     | Analyze Stakeholder Input | 5| 10/10/2023 | 10/12/2023 |11 |
| 13   | Analyze Interview Data | 5 | 10/10/2023 | 10/11/2023 | 12 |
| 14   | Document Functional Requirements |5 | 10/12/2023 | 10/12/2023 | 13 |
| 15     | Database Design and Implementation | 60 | 10/13/2023 | 10/16/2023 | 14 |
| 16     | Define Database Schema |18 | 10/17/2023 | 10/21/2023 |15 |
|17   | Define Tables and Relationships | 12 | 10/17/2023 | 10/19/2023 | 15|
| 18   | Define Data Entry Rules | 8 | 10/20/2023 | 10/21/2023 | 17 |
| 19     | Database Implementation | 20 | 10/22/2023 | 10/26/2023 | 17,18 |
| 20  | Create Database Tables | 12 | 10/22/2023 | 10/24/2023 | 19 |
| 21   | Implement Data Entry Rules | 14 | 10/25/2023 | 10/26/2023 | 19|
| 22       | User Interface Design and Development |80 | 10/27/2023 | 11/09/2023 |21 |
| 23     | Design User Interface Mockups | 20 | 10/27/2023 | 11/02/2023 | 22 |
| 24   | Create Mockups for Main Pages | 12 | 10/27/2023 | 10/31/2023 | 23 |
| 25   | Gather Feedback on Mockups | 8 | 11/01/2023 | 11/02/2023 | 23 |
| 26     | Develop User Interface | 40 | 11/03/2023 | 11/09/2023 | 25 |
|27  | Implement Main Page UI | 24 | 11/03/2023 | 11/07/2023 |26 |
| 28   | Implement Feedback-Driven Re visions | 12 | 11/08/2023 | 11/09/2023 | 27 |
| 29      | Backend Development | 90 | 11/10/2023 | 11/27/2023 |28 |
| 30     | Develop Core System Logic | 40 | 11/10/2023 | 11/17/2023 |29 |
| 31   | Implement User Authentication | 18 | 11/10/2023 | 11/13/2023 | 30 |
| 32   | Implement Data Handling Functions | 22 | 11/14/2023 | 11/17/2023 | 30 |
| 33    | Integrate Database Functionality | 30 | 11/18/2023 | 11/24/2023 | 30 |
| 34  | Integrate User Data Handling | 15 | 11/18/2023 | 11/21/2023 | 33 |
|35  | Integrate Reporting Functionality | 12 | 11/22/2023 | 11/24/2023 | 34|
| 36     | Implement Security Measures | 20 | 11/25/2023 | 11/27/2023 | 35 |
| 37      | Integration and Testing | 50 | 11/28/2023 | 12/10/2023 | 36 |
| 38    | Integrate UI, Backend, and Database | 30 | 11/28/2023 | 12/04/2023 |37 |
|39  | Integrate User Interface and Backend | 12 | 11/28/2023 | 12/01/2023 |38 |
| 40  | Integrate Database Functionality | 12 | 12/02/2023 | 12/04/2023 |39 |
| 41     | Conduct System Testing | 8 | 12/05/2023 | 12/09/2023 | 40|
| 42   | Develop Testing Scenarios | 8 | 12/05/2023 | 12/07/2023 | 41 |
| 43   | Perform System Testing | 8| 12/08/2023 | 12/09/2023 |42|
| 44    | Bug Fixing and Final Testing | 8 | 12/10/2023 | 12/10/2023 | 43 |
|  45      | Security and Compliance Implementation | 20 | 12/11/2023 | 12/15/2023 |44 |
| 46    | Compliance with Privacy Regulations | 8 | 12/14/2023 | 12/15/2023 |45 |
| 47     | Training Material Development | 8 | 12/16/2023 | 12/19/2023 | 46 |
| 48   | Create Training Modules | 8 | 12/16/2023 | 12/18/2023 | 47|
| 49   | Develop User Guides | 8 | 12/19/2023 | 12/19/2023 | 48 |
| 50     | User Training | 2| 12/20/2023 | 12/28/2023 | 49 |
| 51   | Develop Training Schedule | 1 | 12/20/2023 | 12/23/2023 | 50 |
| 52    | Conduct Training Sessions | 1| 12/24/2023 | 12/28/2023 | 51 |
| 53   | System Rollout | 10 | 12/29/2023 | 01/01/2024 | 52 |
| 54   | Pre-Rollout Checklist |5 | 12/29/2023 | 12/31/2023 | 53 |
|55  | Launch System to Users | 8 | 01/01/2024 | 01/01/2024 | 54 |
|56      | Project Closure and Evaluation |10 | 01/02/2024 | 01/05/2024 | 55|
| 57    | Evaluate Project Success | 10| 01/02/2024 | 01/03/2024 | 56 |
| 58   | Document Lessons Learned | 8 | 01/04/2024 | 01/05/2024 | 57 |
| 59      | Documentation and Knowledge Transfer | 8 | 01/06/2024 | 01/10/2024 | 58|
| 60   | Create User Manuals | 8 | 01/06/2024 | 01/08/2024 | 59 |
|61  | Develop Technical Documentation | 10 | 01/09/2024 | 01/10/2024 | 60 |
| 62      | Post-Implementation Review | 20 | 01/11/2024 | 01/14/2024 | 61 |
| 63    | Gather User Feedback | 12 | 01/11/2024 | 01/12/2024 | 62|
| 64      | Project Closure and Reporting | 12 | 01/15/2024 | 01/19/2024 | 63 |
| 65    | Finalize Project Documentation | 12| 7/25/24 | 7/26/24 | 64|
| 66    | Generate Project Report | 12 | 7/2624 | 7/29/24 | 65 |

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
Qooper - Qooper partners with companies, universities and non-profits worldwide to start and grow their mentorship programs.
Customizable Questionnaire & Matching Algorithm
Use Qooper Profile Form Builder to have participants fill our your questionnaire or select from our templates with professional and personality assessments
Select matching algorithm criteria and weights
Import users from HR systems or existing excel sheets
Curriculum Design & Templates
Create a guided mentoring experience to train mentors and mentees on the next steps in the program and provide resources from Qooper Library, or add your own. 

Linked-In Learning - LinkedIn Learning is an on-demand library of instructional videos covering the latest business, technology and creative skills. It provides personalized course recommendations and is designed to help you achieve your full potential. Learners can join course-based learning groups, share and recommend courses from inside the learning platform, and watch courses together. Online training platform dashboards can provide managers an easy way to monitor, comment on, and guide their direct report's professional development. 

## API Descriptions
Qooper API:

Description: Qooper is a mentorship and professional development platform that facilitates mentor matching, networking, and skill development.
Capabilities: The Qooper API enables integration with the Tech Connect mobile application to support mentorship matchmaking functionality. It allows users to register as mentors or mentees, create profiles detailing their skills and interests, and find compatible mentorship matches based on various criteria. The API facilitates communication between mentors and mentees, scheduling mentorship sessions, and tracking progress.
Example: Integrating the Qooper API into the Tech Connect app enables underprivileged individuals to connect with mentors in the tech industry who can provide guidance, support, and career advice. Users can create mentorship profiles, browse through a database of registered mentors, and request mentorship connections based on their specific needs and goals. The API streamlines the mentorship process, enhancing users' access to valuable mentorship opportunities and fostering their professional development in the tech sector.

LinkedIn Learning API:

Description: LinkedIn Learning is an online platform offering a vast library of courses and tutorials covering various topics, including technology, business, and professional development.
Capabilities: The LinkedIn Learning API allows integration with the Tech Connect app to provide access to tech-related educational content. It enables users to search for courses based on their interests and skill levels, view course descriptions and previews, and track their progress.
Example: By integrating the LinkedIn Learning API, the Tech Connect app offers underprivileged individuals access to a wide range of tech-related courses and tutorials. Users can explore topics such as programming languages, software development, data science, and digital literacy, empowering them to acquire valuable skills and knowledge in the tech field. The API enhances the educational component of the Tech Connect platform, providing users with resources to support their learning and skill development journey.

Location-Based Services API:

Description: APIs such Google Maps API or Mapbox API, enable the integration of mapping and geolocation functionalities into the app.
Capabilities: These APIs allow users to search for nearby community organizations, educational institutions, or tech industry partners participating in the Tech Connect program. They can view locations on a map, get directions, and explore points of interest.
Example: Integrating a location-based services API enables users to easily find resources and events in their local area, enhancing their engagement with the Tech Connect platform and facilitating access to relevant opportunities.

Communication and Collaboration APIs:

Description: Communication APIs like Twilio or SendGrid, facilitate messaging, notifications, and email functionalities within the app.
Capabilities: These APIs enable the app to send notifications about mentorship matches, upcoming events, or new educational content. They also support communication between users, mentors, and administrators.
Example: Integrating a communication API enhances user engagement by providing timely updates and facilitating interactions between participants in the Tech Connect program, fostering collaboration and support within the community.

Authentication and User Management APIs:

Description: Firebase Authentication manage user authentication and authorization processes.
Capabilities: Handle user registration, login, and authentication securely.Also manage user profiles and permissions within the app.
Example: Integrating an authentication API ensures the security of user accounts and protects sensitive information. It enables users to securely access their profiles, track their progress, and participate in mentorship activities within the Tech Connect platform.

Content Management APIs:

Description: Contentful or WordPress REST API, facilitate the management and delivery of dynamic content within the app.
Capabilities: These APIs allow us to create, edit, and organize educational content, mentor profiles, and resource listings. They also enable seamless content updates and synchronization across different platforms.
Example: Integrating a content management API streamlines the management of educational resources and mentor profiles within the Tech Connect app. It empowers administrators to curate relevant content and maintain up-to-date information, ensuring a valuable and engaging user experience for participants.

