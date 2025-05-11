# 📌 Requirement Analysis in Software Development

## ❓ What is Requirement Analysis?

Requirement Analysis is the process of identifying, analyzing, and documenting the needs and expectations of stakeholders for a new or modified software system. It acts as a bridge between business problems and technology solutions. The goal is to ensure that developers build what the users actually need — not just what they say they want.

This process includes understanding **what** the system should do (**functional requirements**) and **how** it should perform (**non-functional requirements**). It also involves constant communication with stakeholders to avoid ambiguities and misinterpretations.

---

## 🧠 Why is Requirement Analysis Important?

Requirement Analysis plays a critical role in the success of any software project. Here’s why it matters:

- ✅ **Defines Clear Project Scope**: It helps establish what should be built and what shouldn’t, preventing scope creep.
- 🛠️ **Improves Design and Development**: Developers can build the right features with fewer misunderstandings.
- 📉 **Reduces Costs**: Finding and fixing errors early in the requirements phase is cheaper than fixing them during or after development.
- 🕒 **Saves Time**: Accurate requirements lead to better planning, scheduling, and faster delivery.
- 📡 **Enhances Communication**: Acts as a shared understanding between stakeholders, developers, testers, and project managers.

---

## 📂 Types of Requirements

In software development, requirements are generally classified into two main types:

### 🔹 Functional Requirements

These specify **what the system should do**. They describe the specific behavior or functions of the system.

**Examples:**
- User authentication
- Booking a ticket
- Generating a report

### 🔸 Non-functional Requirements

These specify **how the system should perform**. They define the system’s quality attributes.

**Examples:**
- Performance (e.g., response time under 2 seconds)
- Security (e.g., data must be encrypted)
- Scalability
- Usability

🔄 **Key Difference**:  
- Functional = *Features and actions*
- Non-functional = *Performance and quality of those features*

---

## 🧾 Use Case Diagrams

Use Case Diagrams are a type of UML (Unified Modeling Language) diagram used during Requirement Analysis to visually represent **how users (actors)** interact with the system.

### 🎯 Purpose:

- Identify system functionalities from a user’s perspective
- Clarify different user roles and their goals
- Serve as a communication tool between stakeholders and developers

### 🧑‍🤝‍🧑 Example:
Imagine a **property booking system**. A use case diagram might include:
- **Actors**: Guest, Admin
- **Use Cases**: Register, Search Property, Book Property, Cancel Booking, Manage Listings

This visual structure helps ensure that all necessary interactions are accounted for before development begins.

---

## ✅ Acceptance Criteria

Acceptance Criteria are the **conditions that a feature or system must meet to be accepted** by stakeholders or users.

### ✍️ How to Establish & Use Acceptance Criteria:

1. **Collaborate Early**: Define criteria with stakeholders during requirement discussions.
2. **Make It Testable**: Each criterion should be measurable and verifiable.
3. **Use Simple Language**: Avoid technical jargon. Keep it user-focused.
4. **Follow Gherkin Format (optional)**:
   ```gherkin
   Given [initial context]
   When [event occurs]
   Then [expected outcome]
