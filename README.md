# 📘 Requirement Analysis in Software Development

## 📖 Introduction

This repository contains detailed information about **Requirement Analysis** in the Software Development Life Cycle (SDLC). It serves as a reference and educational guide for understanding the purpose, importance, and core activities involved in analyzing software requirements.

---

## 💡 What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a new or modified software product. It ensures that developers, designers, and project managers understand what the end-users need before the development begins.

This phase is critical in the SDLC because it lays the foundation for all subsequent phases. A well-executed requirement analysis process helps prevent scope creep, reduce cost overruns, and ensure that the final product meets user expectations.

---

## ❓ Why is Requirement Analysis Important?

1. **Prevents Miscommunication**
   - Clearly defines what is expected from the software, minimizing misunderstandings between stakeholders and developers.

2. **Saves Time and Cost**
   - Early detection of unclear or conflicting requirements avoids costly changes later in the development process.

3. **Guides Design and Development**
   - Acts as a blueprint for system design and ensures all features are aligned with business goals.

---

## 🔍 Key Activities in Requirement Analysis

- **Requirement Gathering**
  - Collecting needs from stakeholders via interviews, questionnaires, or observations.

- **Requirement Elicitation**
  - Digging deeper into user needs through workshops, brainstorming, and scenario analysis.

- **Requirement Documentation**
  - Writing clear and detailed requirement specifications (SRS).

- **Requirement Analysis and Modeling**
  - Analyzing feasibility, prioritization, and modeling using diagrams like UML.

- **Requirement Validation**
  - Ensuring documented requirements match stakeholder expectations through reviews and feedback.

---

## 🧾 Types of Requirements

### ✅ Functional Requirements

These specify **what the system should do**.

**Examples for Booking System**:
- The user can search for available properties.
- The system allows a user to make a reservation.
- Admins can add or remove listings.

### ⚙️ Non-functional Requirements

These define **how the system performs**.

**Examples for Booking System**:
- The system should respond to search queries within 2 seconds.
- The platform must be accessible on mobile and desktop.
- All data must be encrypted in transit and at rest.

---

## 🧩 Use Case Diagrams

**Use Case Diagrams** provide a visual representation of the system's functionalities and how users (actors) interact with them. They help stakeholders understand what the system will do without diving into technical details.

![Use Case Diagram](./diagrams/alx-booking-uc.png)


> 📌 Diagram includes:
> - **Actors**: Guest, Host, Admin
> - **Use Cases**: Search Listings, View Details, Book Property, Add Listing, Approve Booking, etc.

---

## ✅ Acceptance Criteria

**Acceptance Criteria** define the conditions a software product must meet to be accepted by a user, customer, or other stakeholders. They are essential for aligning expectations and guiding development and testing.

### Example: *Checkout Feature*

**Acceptance Criteria**:
- The user can input credit card and billing information.
- Payment is processed securely through the payment gateway.
- A confirmation email is sent after successful booking.
- The booking appears in the user’s booking history.
- Error messages are shown for failed transactions.

---

## 📂 Repository Structure (Optional)

```bash
requirement-analysis/
├── README.md
└── alx-booking-uc.png

---

## ✅ **Step 3: Create the Use Case Diagram**

1. Go to [https://draw.io](https://draw.io) (or [https://app.diagrams.net](https://app.diagrams.net))
2. Create a simple **Use Case Diagram** with:
   - **Actors**: Guest, Host, Admin
   - **Use Cases**: Search Listings, View Listing, Book, Cancel Booking, Manage Listings, etc.
3. Export the diagram as `alx-booking-uc.png`
4. Upload it to your GitHub repo:
   - You can use the GitHub web interface (drag/drop into the repo)
   - Or use Git:

```bash
cp path/to/alx-booking-uc.png .
git add alx-booking-uc.png
git commit -m "Add use case diagram for booking system"
git push origin main
