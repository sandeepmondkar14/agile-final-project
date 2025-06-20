# Agile Product Catalog Backend: A Kanban-Managed E-commerce Solution

## 🚀 Project Overview

This project focuses on the backend development for a core **Product Catalog** service, designed to support an e-commerce website. The primary goal is to provide robust capabilities for managing product data, including creation, retrieval, updates, deletions, and interaction features like product 'liking' and 'disliking'. A key aspect of this project is its deployment to a cloud environment with automated continuous delivery, demonstrating a complete software development lifecycle.

This final project serves as a practical application of Agile methodologies, specifically utilizing a Kanban board on GitHub Projects for managing the product backlog, sprint planning, and simulating sprint execution.

## ✨ Key Features (Stakeholder Requirements)

The following core functionalities are being developed for the product catalog:

* **Product Management (CRUD):**
    * Ability to **Create** a new product in the catalog.
    * Ability to **Retrieve** a specific product from the catalog.
    * Ability to **Update** existing product details.
    * Ability to **Delete** a product from the catalog.
* **Customer Interaction:**
    * Ability to **Like** a product.
    * Ability to **Dislike** a product.
* **Product Discovery:**
    * Ability to **List all** products in the catalog.
    * Ability to **Query a subset** of products based on criteria.
* **Infrastructure & Operations (Technical Debt Focus):**
    * Must be **hosted in the cloud** for scalability and availability.
    * Must have **automation** to deploy new changes to the cloud efficiently.

## 📋 Agile Workflow & Project Management

This project is managed using Agile principles with a Kanban board hosted on GitHub Projects. This approach allows for:

* **Visualizing Workflow:** Clearly seeing the status of each task.
* **Limiting Work in Progress (WIP):** Focusing on completing tasks before starting new ones.
* **Continuous Flow:** Delivering value incrementally.

### Kanban Board Structure

Our Kanban board, named "Final Project," is structured with the following columns:

* **Icebox:** Ideas and requirements that are not yet prioritized for development.
* **Product Backlog:** Prioritized list of features and tasks ready for future sprints.
* **Sprint Backlog:** Stories committed to and planned for the current sprint.
* **In Progress:** Work actively being developed by a team member.
* **Review/QA:** Completed work awaiting testing and quality assurance.
* **Done:** Features that are fully completed, tested, and potentially deployed.

---

**Current Kanban Board Status:**

![Kanban Board Left Side](images/Kanban%20board%28left%20side%29.png)
![Kanban Board Right Side](images/Kanban%20board%20%28right%20side%29.png)
*(Note: These images show the full progression of stories across our Kanban board during the simulated sprint.)*

---

### User Stories

All features are captured as user stories following the `As a... I need... So that...` format, complete with `Details and Assumptions` and `Acceptance Criteria` in Gherkin syntax.

Example User Story Structure:
```markdown
**As a** [role]
**I need** [function]
**So that** [benefit]

### Details and Assumptions
* [document what you know]

### Acceptance Criteria

```gherkin
Given [some context]
When [certain action is taken]
Then [the outcome of action is observed]
```

### Labels

Issues are categorized using labels to provide additional context:

* `enhancement`: For new features or improvements to existing functionality.
* `technical debt`: For addressing non-functional requirements, architectural improvements, or areas where past decisions need remediation (e.g., cloud hosting and deployment automation in this project).

## 📊 Sprint 1 Status (Simulated)

This section reflects the outcome of our simulated 2-week sprint ("Sprint" Milestone, ending June 23, 2025).

**Sprint Goal:** Deliver foundational CRUD operations for the product catalog.

**Initial Sprint Commitment:** 16 Story Points

**Burndown Chart Summary:**
The burndown chart visually tracks our progress, showing the remaining work against time.

* Initial Scope: 16 Story Points
* Completed during sprint: 8 Story Points
    * `Create Product in Catalog` (5 pts)
    * `Retrieve Product from Catalog` (3 pts)
* Remaining at Sprint End: 8 Story Points
    * `Update Product in Catalog` (5 pts - In Progress)
    * `Delete Product from Catalog` (3 pts - In Sprint Backlog)

---

**Sprint 1 Burndown Chart:**

![Sprint 1 Burndown Chart](images/BurnDown%20chart.png)

---

## 🔗 Project Links

* **GitHub Repository:** `https://github.com/sandeepmondkar14/agile-final-project`
* **Kanban Board (GitHub Project):** `https://github.com/users/sandeepmondkar14/projects/2`
* **Burndown Chart (GitHub Insights):** `https://github.com/users/sandeepmondkar14/projects/2/insights/1`

---

## 👥 Team

This project is a solo effort for learning purposes.

* **Product Owner / Scrum Master / Developer:** Sandeep Mondkar

## 📝 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
