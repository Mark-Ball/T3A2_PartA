# MERN Project

- Purpose: The purpose of the application is to create an interface that manages and surfaces content from a library of learning content for internal use and select clients to build and teach. 
- Functionality / features:
    - categorised content: all learning content is sorted into appropriate categories based on their topic
    - progression in learning, (some topics have multiple lessons with increasing difficulty), therefore display prerequisites (assumed knowledge) of lesson
    - admin user approval to view content
    - admin ability to upload and remove learning content
    - learning pdf content embedded in window with option to download
    - flags for content more than a year old.
- Target audience: for internal parties of the company and selected clients in order to upskill.
- Tech stack
    - Draw io
    - 
jurra

## 1. Dataflow Diagram
![dataflow-diagram-mern](/docs/dataflow-diagram-mern.JPG)

<strong>Figure 1.</strong> Dataflow diagram

## 2. Application Architecture

![MERN-Application-Architecture](/docs/MERN-Application-Architecture.PNG)

<strong>Figure 2.</strong> Application architecture diagram

## 3. User stories

1. As a learner, I want to be able to access the learning material online, so I can explore what is available at my own pace

2. As the business owner, I want learning materials to be accessible online, so my staff do not have to spend time sending documents to clients

<strong>Implication:</strong> learning materials should be available on the web

3. As a learner, I want to be able to search for lessons, so I may find useful content more easily

<strong>Implication:</strong> the lessons should be searchable by keywords and return a list of results

4. As a learner, I want the lessons to be categorised, so I may find useful content more easily

<strong>Implication:</strong> the lessons should be categorised, functionality should exist to filter the lessons by category

5. As a learner, I want the lessons to be downloadable, so I may continue learning offline

<strong>Implication:</strong> the lessons should have an option to download, and what will be downloaded should be clear

6. As a learner, I want the content to be flagged with the level of proficiency required to understand the material, so I can select a lesson appropriate for my skills

<strong>Implication:</strong> the lessons should each have a visible proficiency score displayed alongside the search results

7. As a learner, I want the learning material to be flagged with the date it was created, so I can judge whether it is likely to be outdated

<strong>Implication:</strong> the lessons should be marked with the date it was created

8. As a learner, I want lessons to be suggested, so I can continue learning after I have finished my current lesson

<strong>Implication:</strong> lessons should be organised in a progression so that learners always know what they can work on next

9. As the business owner, I want users to have to log into the website to view the learning material, so I can lock out people who should not have access

<strong>Implication:</strong> there should be a username and password login functionality and all learning materials should be viewable only by logged-in users

10. As the business owner, I want to have control over which information users have access to, even after they have registered an account, so I may protect my business secrets

<strong>Implication:</strong> even after users have registered, there must be an additional level of security to ensure that only authorised users have access to the learning material

11. As the business owner, I want to be able to upload learning material, so I can continue to improve the e-learning options

<strong>Implication:</strong> there should be functionality within the application to add learning material

## 4. Wireframes
### Landing Page
Entry Point of Application.

![login-register-page](/docs/MERN-Wireframes/login-register-page-desktop.PNG)

##### Figure 3: Desktop Version of Login/Register Page
![login-register-page](/docs/MERN-Wireframes/login-register-page-ipad.PNG)

##### Figure 4: iPad Version of Login/Register Page
![login-register-page](/docs/MERN-Wireframes/login-register-page-mobile.PNG)

##### Figure 5: Mobile Version of Login/Register Page

### Home Page
Point of entry to the application once authorised. 

![home-page](/docs/MERN-Wireframes/home-page-desktop.PNG)

##### Figure 6: Desktop Version of Home Page 
![home-page](/docs/MERN-Wireframes/home-page-category-selector-desktop.PNG)

##### Figure 7: Desktop Version of Home Page 
![home-page](/docs/MERN-Wireframes/home-page-ipad.PNG)

##### Figure 8: iPad Version of Home Page
![home-page](/docs/MERN-Wireframes/home-page-mobile.PNG)

##### Figure 9: Mobile Version of Home Page

### Search Results Page
Returns results of a search query.

![search-results-page](/docs/MERN-Wireframes/search-results-page-desktop.PNG)

##### Figure 10: Desktop Version of Results Page 
![search-results-page](/docs/MERN-Wireframes/search-results-page-ipad.PNG)

##### Figure 11: iPad Version of Results Page
![search-results-page](/docs/MERN-Wireframes/search-results-page-mobile.PNG)

##### Figure 12: Mobile Version of Results Page

### Learning Content Page
Displays the selected content chosen from search query. 

![content-show-page](/docs/MERN-Wireframes/content-show-page-desktop.PNG)

##### Figure 13: Desktop Version of Content Page 
![content-show-page](/docs/MERN-Wireframes/content-show-page-ipad.PNG)

##### Figure 14: iPad Version of Content Page
![content-show-page](/docs/MERN-Wireframes/content-show-page-mobile.PNG)

##### Figure 15: Mobile Version of Content Page

### Admin Dashboard
Landing Page for the Admin Account

![admin-dash-page](/docs/MERN-Wireframes/admin-dash-page-desktop.PNG)

##### Figure 16: Desktop Version of Admin Dashboard  
![admin-dash-page](/docs/MERN-Wireframes/admin-dash-page-ipad.PNG)

##### Figure 17: iPad Version of Admin Dashboard 
![admin-dash-page](/docs/MERN-Wireframes/admin-dash-page-mobile.PNG)

##### Figure 18: Mobile Version of Admin Dashboard 

### Admin Approval Page 
Allows the administrator the ability to approve pending users' access to the site and additionally toggle existing user's access.

![admin-approval](/docs/MERN-Wireframes/admin-approval-desktop.PNG)

##### Figure 19: Desktop Version of Admin Approval Page 
![admin-approval](/docs/MERN-Wireframes/admin-approval-ipad.PNG)

##### Figure 20: iPad Version of Admin Approval Page
![admin-approval](/docs/MERN-Wireframes/admin-approval-mobile.PNG)

##### Figure 21: Mobile Version of Admin Approval Page

### Admin Content Upload & Removal Page
Allows the administrator to add new content or remove existing content.

![admin-file-content-page](/docs/MERN-Wireframes/admin-file-content-page-desktop.PNG)

##### Figure 22: Desktop Version of Admin Content Page 
![admin-file-content-page](/docs/MERN-Wireframes/admin-file-content-page-ipad.PNG)

##### Figure 23: iPad Version of Admin Content Page
![admin-file-content-page](/docs/MERN-Wireframes/admin-file-content-page-mobile.PNG)

##### Figure 24: Mobile Version of Admin Content Page


## 5. Kanban board

The project used a physical kanban board to visualise the progression of features in the project.

To plan which features should be completed first, 'scrum poker' was used to estimate the complexity and importance of each feature. Each feature was categorised into one of four boxes, representing the priority of the feature.

The highest priority features are the ones with high importance and low complexity, and the lowest priority features are the ones with low importance and high complexity. Features in the other two boxes, high importance-high complexity and low importance-low complexity are intermediate. This categorisation allows makes the decision of which features to work on easier.

![kanban_2](/docs/kanban_2.PNG)

<strong>Figure x.</strong> Kanban board for Part A, beginning day 4.

![kanban_3](/docs/kanban_3.PNG)

<strong>Figure x.</strong> Kanban board for Part A, end day 4.