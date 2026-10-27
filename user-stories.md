# User Stories and Tasks — Opportunity Connect

## 1. Introduction

User stories were used during the development of Opportunity Connect to describe the functionality of the system from the perspective of its intended users.

A user story focuses on **who** needs a feature, **what** they need and **why** they need it.

The general format used was:

> **As a [user], I want [functionality], so that [benefit].**

Each user story was then broken down into smaller development tasks. This made the requirements easier to understand, estimate, implement and test.

---

# 2. User Stories

## US01 — User Registration

**User Story:**

> As a student, I want to create an account so that I can access Opportunity Connect and use the platform.

**Priority:** High

### Tasks

- Design the registration interface.
- Create the required registration fields.
- Add input validation.
- Implement password and confirmation validation.
- Create the backend registration functionality.
- Connect the Angular frontend to the Python backend.
- Test successful registration.
- Test invalid registration data.
- Display appropriate success and error messages.

---

## US02 — User Login

**User Story:**

> As a registered student, I want to log into my account so that I can access the platform.

**Priority:** High

### Tasks

- Design the login interface.
- Add email and password fields.
- Implement frontend validation.
- Implement backend login functionality.
- Connect the login form to the backend.
- Handle successful authentication.
- Handle incorrect login details.
- Display appropriate error messages.
- Test the login functionality.

---

## US03 — View Available Opportunities

**User Story:**

> As a student, I want to view available bursaries and opportunities so that I can discover opportunities that may be relevant to me.

**Priority:** High

### Tasks

- Design the opportunity listing interface.
- Create the opportunity data structure.
- Add opportunity information.
- Retrieve opportunity information from the backend.
- Display opportunities in the frontend.
- Create opportunity cards or listings.
- Test that opportunity information is displayed correctly.

---

## US04 — Search for Opportunities

**User Story:**

> As a student, I want to search for opportunities so that I can quickly find opportunities that match my interests.

**Priority:** High

### Tasks

- Add a search field.
- Capture the user's search input.
- Implement search functionality.
- Filter opportunity results according to the search term.
- Display matching results.
- Handle searches with no matching results.
- Test different search terms.

---

## US05 — Filter Opportunities

**User Story:**

> As a student, I want to filter opportunities according to relevant criteria so that I can find opportunities that are more suitable for me.

**Priority:** Medium

### Tasks

- Identify useful filtering criteria.
- Design the filter interface.
- Implement the filtering logic.
- Connect filters to opportunity data.
- Display filtered results.
- Allow users to remove or change filters.
- Test different combinations of filters.

---

## US06 — View Opportunity Details

**User Story:**

> As a student, I want to view detailed information about an opportunity so that I can determine whether it is suitable for me.

**Priority:** High

### Tasks

- Create an opportunity details view.
- Display the opportunity name.
- Display the organisation providing the opportunity.
- Display eligibility information.
- Display application information.
- Display important dates where available.
- Add an application or external opportunity link where appropriate.
- Test the opportunity details page.

---

## US07 — Find Relevant Opportunities

**User Story:**

> As a student, I want to find opportunities that match my personal and academic information so that I can focus on opportunities for which I may be eligible.

**Priority:** High

### Tasks

- Identify information required for matching.
- Create the relevant user input fields.
- Define opportunity matching criteria.
- Implement matching logic.
- Compare user information against opportunity requirements.
- Display relevant opportunities.
- Test matching with different user information.

---

## US08 — Manage User Information

**User Story:**

> As a registered student, I want to manage my personal information so that my profile remains accurate.

**Priority:** Medium

### Tasks

- Create the user profile interface.
- Display existing user information.
- Add editable profile fields.
- Implement profile update functionality.
- Validate updated information.
- Save updated information.
- Test profile updates.

---

## US09 — Administer Opportunities

**User Story:**

> As an administrator, I want to manage opportunity information so that students have access to accurate and up-to-date opportunities.

**Priority:** High

### Tasks

- Create an administrator interface.
- Allow administrators to add opportunities.
- Allow administrators to edit opportunities.
- Allow administrators to remove opportunities.
- Validate opportunity information.
- Test opportunity management functionality.

---

## US10 — Responsive User Interface

**User Story:**

> As a student, I want the platform to work on different screen sizes so that I can access opportunities using different devices.

**Priority:** Medium

### Tasks

- Design responsive layouts.
- Test the interface on desktop screens.
- Test the interface on mobile screen sizes.
- Adjust navigation for smaller screens.
- Adjust opportunity cards for different screen sizes.
- Fix layout issues.
- Perform final responsive testing.

---

# 3. User Story Acceptance Criteria

Acceptance criteria were used to define what should be true for a user story to be considered successfully implemented.

For example:

### US01 — User Registration

A registration feature can be considered complete when:

- A student can access the registration form.
- Required information can be entered.
- Invalid information is identified.
- Password confirmation is validated.
- Valid registration information can be submitted.
- The backend processes the registration.
- The user receives appropriate feedback.

### US03 — View Available Opportunities

The feature can be considered complete when:

- Available opportunities can be retrieved.
- Opportunity information is displayed clearly.
- Users can select an opportunity to view more information.
- The displayed information is understandable.
- Errors are handled appropriately.

### US04 — Search for Opportunities

The feature can be considered complete when:

- A user can enter a search term.
- The system processes the search.
- Matching opportunities are displayed.
- Non-matching results are excluded.
- The system provides appropriate feedback when no results are found.

---

# 4. Task Breakdown

Breaking user stories into smaller tasks made it easier to manage development.

For example:

### User Story

**US01 — User Registration**

### Development Breakdown

```text
US01 User Registration
│
├── Design registration page
├── Create registration form
├── Add validation
├── Create backend registration endpoint
├── Connect frontend to backend
├── Process registration data
├── Handle errors
├── Test registration
└── Update task status
```

This approach allowed a large feature to be treated as a collection of smaller and more manageable development activities.

---

# 5. User Stories and Agile Development

The user stories provided a connection between the needs of Opportunity Connect's users and the technical work required to develop the system.

For example, the requirement for students to find relevant opportunities could be represented as a user story and then divided into tasks involving the frontend, backend, data and testing.

This helped ensure that development activities remained focused on providing functionality that had a clear purpose for the end user.

---

# Evidence

The following artefacts can be included as evidence for the User Stories and Tasks section.

### Evidence 1 — User Stories

The documented user stories demonstrate how the requirements of Opportunity Connect were described from the perspective of the intended users.

> **<img width="974" height="1280" alt="image" src="https://github.com/user-attachments/assets/96278a6a-fb29-4449-9258-41631f45c785" />
**

---

### Evidence 2 — Task Breakdown

Initial OppCo GitHub Repository Structure — Screenshot showing the initial repository structure of the OppCo project, including the organisation of the frontend, backend, and supporting project files.

> **<img width="2878" height="1800" alt="image" src="https://github.com/user-attachments/assets/72cd6d4c-e0a6-4037-98a3-13e77e5db3c5" />
**

---

### Evidence 3 — Implemented Features

Screenshot demonstrating the student profile functionality, where users can view and manage their personal information used to support personalised opportunity matching.

> **<<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/ca771779-51b7-4d0d-8e71-838b3786193c" />

**

---

# Reflection

Creating user stories and breaking them down into smaller tasks helped me understand how Agile development connects user requirements with technical implementation.

Before working with user stories, it was easy to think about a software project mainly in terms of the features that needed to be programmed. User stories changed this perspective by requiring me to consider the functionality from the point of view of the person who would actually use the system. For Opportunity Connect, this meant focusing on what students need when searching for bursaries and other opportunities.

One of the main benefits of using user stories was that they made large requirements easier to understand. For example, the requirement for students to register for the platform could be divided into several smaller tasks, including designing the form, implementing validation, creating backend functionality, connecting the frontend and backend, and testing the feature.

Breaking the stories into tasks also made it easier to monitor development progress. Instead of treating a feature as one large piece of work, I could identify the individual activities required to complete it. This made the development process more organised and helped identify which parts of a feature were still outstanding.

I also learned that user stories should focus on the value provided to the user rather than only describing technical implementation. For example, a student does not simply need a search function because it is a technical feature. The purpose of the search function is to help the student find relevant opportunities more efficiently.

Another important lesson was the value of acceptance criteria. Acceptance criteria provided a clearer understanding of what needed to happen before a user story could be considered complete. This made testing more focused because the implemented functionality could be compared against the expected behaviour.

Overall, creating user stories and tasks improved my ability to translate user requirements into manageable development activities. It also helped me understand how Agile development keeps software development focused on delivering value to the end user.
