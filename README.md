# Student Project Portfolio & Showcase App

## Problem Statement 4 — Student Project Portfolio & Showcase App

This repository contains the submissions for the Student Project Portfolio & Showcase App, including Lab 1 — Requirements Engineering & UML Use-Case Modelling and Lab 2 — Agile Backlog Creation & Sprint Simulation in Jira.

---

# Lab 1 — Requirements Engineering & UML Use-Case Modelling

## Problem Statement 4 — Student Project Portfolio & Showcase App

This repository contains the individual submission for Lab 1 of Requirements Engineering & UML Use-Case Modelling.

### Student Details

- **Name:** Kirthana S
- **SRN:** PES1UG24AM136
- **Section:** C
- **Semester:** 5
- **Problem Statement:** 4 — Student Project Portfolio & Showcase App
- **Individual Use Case:** UC-01 — Create Showcase Profile
- **Primary Actor:** Student Team

### Lab Deliverables

The submission includes:

- Functional Requirements
- Non-Functional Requirements
- UML Use-Case Diagram
- Use-Case Flow Specification
- Main Success Scenario
- Alternate Flow

### Individual Focus

**UC-01 — Create Showcase Profile**

The use case allows a Student Team to create a showcase profile for the annual project exhibition. The process includes entering project and team information, providing an abstract summary, adding a demo video link and GitHub repository URL, validating the submitted repository, storing the profile, and making it eligible for publication in the showcase catalog.




---

# Lab 2 — Agile Backlog Creation & Sprint Simulation in Jira

Lab 2 converts the functional requirements identified in Lab 1 into Agile backlog items using Jira. The work includes creating an Epic and User Stories, assigning priorities and story points, planning and executing a sprint, and analysing progress using the Burndown Chart.

### Individual Epic

**SCRUM-5 — Showcase Profile Management**

The Epic covers the creation of student showcase profiles and validation of the submitted GitHub repository URL before publication.

### User Stories

| Jira Key | User Story | Priority | Story Points | Sprint |
|---|---|---|---:|---|
| SCRUM-6 | Create Showcase Profile | High | 5 | Sprint 1 |
| SCRUM-19 | Validate GitHub Repository URL | High | 3 | Sprint 1 |
| SCRUM-20 | Correct/Resubmit Invalid Repository URL | High | 2 | Sprint 1 |

**Total individual contribution: 10 story points**

### Sprint 1

The three User Stories under the Showcase Profile Management Epic were assigned to Sprint 1 and completed through the Jira workflow.

Completed stories:

- SCRUM-6 — Create Showcase Profile
- SCRUM-19 — Validate GitHub Repository URL
- SCRUM-20 — Correct/Resubmit Invalid Repository URL

The Sprint 1 Burndown Chart shows the overall team sprint workload decreasing from **17 story points to 0 remaining story points**.

### Lab 2 Deliverables

The submission includes:

- Jira Epic
- Agile User Stories
- Acceptance Criteria
- Priority Assignment
- Story Point Estimation
- Sprint 1 Planning and Execution
- Completed Sprint Work
- Burndown Chart
- Sprint Reflection

---

# Lab 3 – Component Modelling & Architectural Pattern Selection

Lab 3 focuses on designing a UML component diagram and selecting a suitable architectural style for the Student Project Portfolio & Showcase App. The work continues from the functional requirements identified in Lab 1 and the Showcase Profile Management Epic developed in Lab 2.

### Architectural Style

**Layered Architecture**

The architecture separates the user interface, profile management logic, authentication and validation, and data persistence into distinct components.

### Component Diagram

The UML component diagram models the Showcase Profile Management workflow, focusing on:

- **FR-001 – Create Showcase Profile**
- **FR-002 – Validate GitHub Repository URL**
- **UC-01 – Create Showcase Profile**

The diagram contains the following components:

1. Showcase UI
2. Showcase Profile Manager
3. Authentication & Access Control
4. GitHub URL Validator
5. Profile Repository
6. Showcase Catalog

The interfaces represent profile submission, authorization, repository validation, profile data storage, and publication eligibility. Provided and required interfaces illustrate the interactions between components.

### Written Justification

Layered Architecture was selected to separate component responsibilities and improve maintainability and testability. The GitHub URL Validator ensures that repository URLs are validated before profiles become eligible for publication. Authentication and access control support secure profile operations, while separating validation and persistence helps isolate and test individual operations.

### Deliverables

- `Lab3_Component_Diagram_Kirthana.png` – UML component diagram in PNG format.
- `Lab3_Component_Diagram_Kirthana.pdf` – UML component diagram in PDF format.
- `Lab3_Written_Justification_Kirthana.docx` – Written architectural justification.
- `Lab3_Written_Justification_Kirthana.pdf` – Written architectural justification in PDF format.

### Conclusion

Lab 3 models the interactions between the components responsible for creating, validating, storing, and publishing student project profiles. The selected architecture maintains continuity with the functional requirements and use case established in Lab 1 and the Showcase Profile Management work continued in Lab 2.
