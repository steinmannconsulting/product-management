# Guidelines for Product ROI Assessment

## Artifacts

### What Are Artifacts?
Artifacts (or **Work Artifacts**) represent the key deliverables and work items managed in the product lifecycle. Artifacts are used to organize, track, and prioritize efforts, ensuring alignment with product goals and measurable outcomes.

- **Source Definition** *(SAFe - Scaled Agile Framework)*:  
  *An artifact is a work item, output, or deliverable that provides value or supports decision-making during the product development process.*  
  [Source: SAFe Framework - Artifacts](https://scaledagileframework.com/)

### Types of Artifacts
The following work artifacts help categorize and manage efforts throughout the product lifecycle:

1. **Features**
   - **What Are They?**: Individual updates or enhancements to the product that group together multiple user stories under a common purpose.
   - **Example**: Adding a reporting dashboard with customizable analytics.

2. **Modules**
   - **What Are They?**: Logical groupings of functionalities, often representing a specific area of the application.
   - **Example**: Authentication, Billing, Analytics.

3. **Roles**
   - **What Are They?**: Archetypes that represent groups of users with shared needs and goals, helping guide the creation of user stories.
   - **Example**: Administrator, End User, Power User.

4. **User Stories**
   - **What Are They?**: Short, focused descriptions of functionality written from the user's perspective to articulate a specific outcome.
   - **Format**: 
     *"As a [Role], I want to [Action], so that I can [Outcome]."*

   - **Purpose**: User stories ensure that features and functionality are designed to meet user needs and achieve a specific goal.

   - **Composition of a User Story**:
     - **Role**: The user or archetype performing the action (e.g., End User, Administrator).
     - **Action**: The action the user needs to perform (e.g., enable 2FA, view a dashboard).
     - **Outcome**: The desired result or benefit (e.g., secure an account, analyze performance metrics).
   
   - **Examples of User Stories**:
     1. *"As an Administrator, I want to enable 2FA, so that I can secure user accounts from unauthorized access."*
     2. *"As a Power User, I want to export data from the analytics dashboard to Excel, so that I can analyze it offline."*
     3. *"As an End User, I want to receive SMS notifications for critical updates, so that I don’t miss important alerts."*

   - **Why User Stories Matter**:
     User stories ensure clarity, focus on user outcomes, and provide a foundation for collaboration between product managers, developers, and stakeholders. They align product work with user needs and business value.

5. **Bugs**
   - **What Are They?**: Defects or errors in the product that impact functionality, performance, or user experience.
   - **Example**: 2FA code fails intermittently.

6. **Enhancement Requests**
   - **What Are They?**: Suggestions or proposals for improving existing functionalities.
   - **Example**: Improve loading speed of analytics dashboards.

7. **Support Cases**
   - **What Are They?**: Issues or inquiries reported by users that require resolution or follow-up.
   - **Example**: User unable to reset their password.

---

## Definitions

### Features
- **What Are Features?**  
  Features are individual updates or enhancements to the product that group together multiple user stories under a common purpose. Each feature represents a cohesive unit of marketable value delivered to the user or business.

- **Source Definition** *(Pragmatic Institute)*:  
  *A feature is a function of a product that delivers a specific benefit or solves a particular problem for a target customer.*  
  [Source: Pragmatic Institute - Features and Benefits](https://www.pragmaticinstitute.com/resources/framework/features-benefits)

- **Feature Composition:**  
  When defining a feature, include the following elements:
  - **Description**: A clear explanation of what the feature is.
  - **Purpose**: Why the feature is being created and what problem it solves.

- **Examples of Features:**
  - **Feature**: Reporting Dashboard  
    - **Description**: A new dashboard with customizable reports for analytics.
    - **Purpose**: To give users visibility into key performance metrics in real-time.
  
  - **Feature**: Two-Factor Authentication (2FA)  
    - **Description**: Adding a second authentication layer for logins.
    - **Purpose**: To improve account security and reduce unauthorized access.

- **Why Features Matter:**
  Features provide a way to deliver incremental value to users while maintaining a clear roadmap. They are larger than user stories but smaller than modules, allowing for effective prioritization and tracking.

---

### Modules
- **What Are Modules?**  
  Modules are specific areas or "Feature Areas" of the application that represent logical groupings of functionalities. Modules serve as structural components of the product and can include features, user stories, bugs, enhancement requests, and support cases.

- **Source Definition** *(SAFe - Scaled Agile Framework)*:  
  *A module (or capability) is a higher-level grouping of features and functionalities that together deliver business value. Modules often align with systems or services within a solution.*  
  [Source: SAFe Framework - Capabilities and Modules](https://scaledagileframework.com/capabilities/)

- **Examples of Modules:**
  - **Authentication**: Login, registration, password recovery.
  - **Analytics**: Dashboards, visualizations, data exports.
  - **Billing**: Subscriptions, payments, invoices.
  - **Notifications**: Email, SMS, and in-app messaging.
  - **User Management**: Roles, permissions, and profiles.

---

### Roles
- **What Are Roles?**  
  Roles, also known as archetypes, are derived by grouping similar user personas who share common needs, behaviors, and goals.

- **Source Definition** *(Nielsen Norman Group - User Archetypes)*:  
  *A role, or archetype, is a generalized representation of user types that describes shared characteristics and goals across multiple personas.*  
  [Source: Nielsen Norman Group - Archetypes and Personas](https://www.nngroup.com/articles/archetypes-personas/)

- **Examples of Roles and Grouped Personas:**
  - **Administrator**: IT Admins, Account Managers, Team Leaders.
  - **End User**: Individual Contributors, Content Creators.
  - **Power User**: Data Analysts, Workflow Coordinators.

---

## Tracking Features and Modules

To effectively manage product development and prioritize ROI, ensure that **Artifacts** (Features, Modules, Roles, User Stories, Bugs, Enhancements, and Support Cases) are consistently tracked across the following areas:

1. **User Stories**
   - Clearly link user stories to features, modules, and roles.
   - Write stories in the format: *"As a [Role], I want to [Action], so that I can [Outcome]."*

2. **Bugs**
   - Bugs must reference the module they belong to, along with severity and priority.

3. **Enhancement Requests**
   - Ensure that improvements reference their associated module and feature.

4. **Support Cases**
   - Tag support cases with relevant modules for reporting and analysis.

---
