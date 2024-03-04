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
| 10   | Review Security Standards | 4 |  2/16/24 |  2/16/24 | 8 |
| 11       | Requirements Analysis and Documentation |10|  2/19/24 |  2/20/24 | 10 |
| 12     | Analyze Stakeholder Input | 5|  2/20/24 |  2/20/24 |11 |
| 13   | Analyze Interview Data | 5 | 2/20/24 | 2/21/24 | 12 |
| 14   | Document Functional Requirements |5 | 2/21/24| 2/22/24 | 13 |
| 15     | Database Design and Implementation | 60 | 2/22/24 | 3/6/24 | 14 |
| 16     | Define Database Schema |18 | 3/6/24 | 3/8/24 |15 |
|17   | Define Tables and Relationships | 12 | 3/6/24| 3/7/24| 15|
| 18   | Define Data Entry Rules | 8 | 3/6/24| 3/7/24 | 17 |
| 19     | Database Implementation | 20 | 3/8/24 | 3/13/24 | 17,18 |
| 20  | Create Database Tables | 12 | 3/13/24 | 3/14/24 | 19 |
| 21   | Implement Data Entry Rules | 14 | 3/13/24 | 3/14/24| 19|
| 22       | User Interface Design and Development |80 |3/15/24 |3/28/243 |21 |
| 23     | Design User Interface Mockups | 20 | 3/29/24 | 14/2/24 | 22 |
| 24   | Create Mockups for Main Pages | 12 | 4/2/24| 4/3/24 | 23 |
| 25   | Gather Feedback on Mockups | 8 | 4/2/24 | 4/3/24 | 23 |
| 26     | Develop User Interface | 40 | 4/3/24 | 4/3/24 | 25 |
|27  | Implement Main Page UI | 24 | 4/16/24  | 4/19/24  |26 |
| 28   | Implement Feedback-Driven Re visions | 12 | 4/19/24 | 4/22/24  | 27 |
| 29      | Backend Development | 90 | 4/22/24 |  5/14/24 |28 |
| 30     | Develop Core System Logic | 40 |  5/8/24 |  5/14/24 |29 |
| 31   | Implement User Authentication | 18 | 5/15/24  |  5/17/24 | 30 |
| 32   | Implement Data Handling Functions | 22 | 5/15/24 | 5/17/24  | 30 |
| 33    | Integrate Database Functionality | 30 | 5/17/24  | 5/23/24  | 30 |
| 34  | Integrate User Data Handling | 15 | 5/23/24  |5/27/24  | 33 |
|35  | Integrate Reporting Functionality | 12 | 5/27/24  | 5/28/24  | 34|
| 36     | Implement Security Measures | 20 | 5/28/24 | 5/31/24 | 35 |
| 37      | Integration and Testing | 50 |5/31/24  | 6/10/24  | 36 |
| 38    | Integrate UI, Backend, and Database | 30 | 6/10/24 | 6/14/24  |37 |
|39  | Integrate User Interface and Backend | 12 | 6/14/24  | 12/17/2023 |38 |
| 40  | Integrate Database Functionality | 12 | 16/17/24 | 6/19/24  |39 |
| 41     | Conduct System Testing | 8 | 6/19/24  | 6/20/24  | 40|
| 42   | Develop Testing Scenarios | 8 | 6/20/24  | 6/21/24  | 41 |
| 43   | Perform System Testing | 8| 6/21/24  | 6/24/24  |42|
| 44    | Bug Fixing and Final Testing | 8 | 6/24/24  | 6/27/24 | 43 |
|  45      | Security and Compliance Implementation | 20 | 6/25/24  |6/27/24  |44 |
| 46    | Compliance with Privacy Regulations | 8 | 6/27/24  | 6/28/24 |45 |
| 47     | Training Material Development | 8 | 6/28/24 | 6/28/24  | 46 |
| 48   | Create Training Modules | 8 |6/28/24 |7/1/24 | 47|
| 49   | Develop User Guides | 8 | 7/2/24 | 7/3/24 | 48 |
| 50     | User Training | 2| 7/3/24 | 7/3/24 | 49 |
| 51   | Develop Training Schedule | 1 |7/3/24| 7/3/24 | 50 |
| 52    | Conduct Training Sessions | 1| 7/3/27| 7/3/24| 51 |
| 53   | System Rollout | 10 | 7/3/24 |7/5/24| 52 |
| 54   | Pre-Rollout Checklist |5 | 7/5/24 | 7/5/24 | 53 |
|55  | Launch System to Users | 8 | 7/5/24 | 7/8/24 | 54 |
|56      | Project Closure and Evaluation |10 | 7/8/24 | 7/9/24 | 55|
| 57    | Evaluate Project Success | 10| 7/10/24 | 7/11/24 | 56 |
| 58   | Document Lessons Learned | 8 | 7/11/24 | 7/19/24 | 57 |
| 59      | Documentation and Knowledge Transfer | 8 |7/12/24 | 7/15/24| 58|
| 60   | Create User Manuals | 8 | 7/15/24|7/16/24 | 59 |
|61  | Develop Technical Documentation | 10 | 7/16/24 | 7/17/24 | 60 |
| 62      | Post-Implementation Review | 20 | 7/17/24 | 7/19/24 | 61 |
| 63    | Gather User Feedback | 12 | 7/22/24 | 7/23/24 | 62|
| 64      | Project Closure and Reporting | 12 | 7/23/24 | 7/24/24 | 63 |
| 65    | Finalize Project Documentation | 12| 7/25/24 | 7/26/24 | 64|
| 66    | Generate Project Report | 12 | 7/2624 | 7/29/24 | 65 |

## Gantt Chart & Network Diagram

[Downloadable Project Management File]([/documents/WIN%20Belize%20Project.mpp](https://github.com/cis-famu/design-project-mmw-n/blob/main/MMW%26N%20WBS.mpp))

## Requirements

### Functional Requirements:

1. **Data Entry and Storage:**
   - The system will recieve information on different data like location, users, instructors, textbooks, etc.
   - The system will organize and categorize the recieved data into databases.
   - The system will allow instructors to upload their lesson plans.

2. **Search and Retrieval:**
   - The system will provide a search function to enable users to search for information based on various filters such as         name, subject, year, date, category, location, keywords, etc.
   - The system will allow users to retrieve relevant data efficiently and in a user-friendly format.

3. **Reporting:**
   - The system generates a report for the management team on information related to accessibility, usage, etc.
   - The system will allow users to customize and export reports in various formats (e.g., PDF, Excel) for further use and sharing.

4. **User Authentication and Authorization:**
   - the system will allow users to pay and enroll to have access in TechConnect.
   - The system will have user authentication to protect their account.   
   - The system will allow administrators to manage user roles and permissions.

5. **User Interface:**
   - The system will allow users to choose what subject they want to enroll in.
   - The system will allow users to view instructors profile and ratings.
   - The system will match users with mentors based on skillset.
   - The system will have learning tools to assist users during their usage.
   - The system will have a progress tracker to allow users to keep track of their overall progress.
   - The system will formated for different devices and be accessibile to the app stores and the website for the users.

### Non-Functional Requirements:

1. **Performance:**
   - The system will respond to user actions swiftly, ensuring minimal latency even during peak usage times.
   - The system will support a large number of concurrent users without a significant decrease in performance.
     
2. **Security:**
   - The system will have data security and encryption to protect users’ payment information.
   - The system will have data security and encryption to protect users’ account information.
   - The system will implement user authentication and access controls to prevent unauthorized access and maintain confidentiality.

3. **Scalability:**
   - The system will be designed to scale seamlessly as the volume of data and user base grows, ensuring continued performance and reliability.
   - The system servers can be adjusted and optimized to adapt to the increase of users

4. **Reliability and Availability:**
   - The system will have a data backup and recovery in case repurchasing for or system crash.
   - If page fails to load, the page can be restarted.
   - The system will strive for high uptime, aiming for a minimum of 99% availability to ensure users can access the system      whenever needed.
   - The system can allow users to have the option to switch to different languages of their preference.

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
 [Use Case Diagram](https://github.com/cis-famu/design-project-mmw-n/blob/main/Screenshot%20(163).png)
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

