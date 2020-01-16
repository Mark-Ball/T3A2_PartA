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

## 5. Kanban board

The project used a physical kanban board to visualise the progression of features in the project.

To plan which features should be completed first, 'scrum poker' was used to estimate the complexity and importance of each feature. Each feature was categorised into one of four boxes, representing the priority of the feature.

The highest priority features are the ones with high importance and low complexity, and the lowest priority features are the ones with low importance and high complexity. Features in the other two boxes, high importance-high complexity and low importance-low complexity are intermediate. This categorisation allows makes the decision of which features to work on easier.

![kanban_2](/docs/kanban_2.PNG)

<strong>Figure x.</strong> Kanban board for Part A, beginning day 4.

![kanban_3](/docs/kanban_3.PNG)

<strong>Figure x.</strong> Kanban board for Part A, end day 4.