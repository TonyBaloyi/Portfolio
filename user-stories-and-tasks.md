
---
layout: default
title: User Stories and Tasks
permalink: /user-stories-and-tasks.html
---

<div class="page-content" markdown="1">

<span class="eyebrow">Agile Portfolio · Requirements & Implementation</span>

# User Stories & Tasks

### Translating real user needs into functional software.

One of the most important lessons I learned during AquaLink was that software development does not begin with writing code.

It begins with understanding what users need to accomplish.

As Project Lead and a substantial frontend contributor, I participated in reviewing requirements, refining application workflows and translating user needs into screens and interactions.

The original Agile Logbook records this process from the requirements stage through frontend implementation and testing.

---

## 01. Understanding AquaLink's Users

AquaLink's documented application focused on two principal system roles: Administrator and Supplier.

Households were represented as subscribers and beneficiaries within the platform rather than as users of a separate consumer application.

<div class="card-grid">

<div class="feature-card">

<span class="card-icon">01</span>

### Administrator

Responsible for reviewing operational information, households, suppliers, plans and purchase-related records.

</div>

<div class="feature-card">

<span class="card-icon">02</span>

### Supplier

Responsible for reviewing tank information, refill history, monitoring data and operational alerts.

</div>

<div class="feature-card">

<span class="card-icon">03</span>

### Households

Community beneficiaries represented through household records, supplier assignments and subscription information.

</div>

</div>

This distinction influenced how we organised navigation and user-facing features.

The system needed to provide appropriate information for each role without confusing administrative responsibilities with supplier operations.

---

## 02. Evidence of Requirements Analysis

The original Agile Logbook contains dated entries documenting the early requirements process.

| Date | Recorded Activity | Development Significance |
|---|---|---|
| 27 July 2026 | Reviewed the AquaLink scope and agreed user stories | Established the Admin and Supplier requirements |
| 28 July 2026 | Reviewed supplier and household management stories | Considered relationships between records |
| 29 July 2026 | Organised requirements for plans, purchases, tanks, refills and alerts | Connected requirements to the product backlog |
| 30 July 2026 | Reviewed navigation between Admin and Supplier pages | Identified role-specific navigation needs |
| 31 July 2026 | Consolidated user-story scope and development priorities | Prepared requirements for implementation |

**Primary source:** AquaLink Agile Logbook, 27–31 July 2026.

[Download Original Agile Logbook](evidence/documents/AquaLink_Agile_Logbook.docx)

These entries demonstrate that the application requirements were reviewed before implementation and that dependencies between pages were considered during planning.

---

## 03. User Stories and Related Features

The following user stories express the functional requirements documented in the logbook using the standard Agile user-story format.

They are structured summaries of recorded requirements, rather than verbatim quotations from individual Trello cards.

| ID | User Story | Related Feature |
|---|---|---|
| US-01 | As an Administrator, I want to view an operational dashboard so that I can review important platform information. | Admin dashboard |
| US-02 | As an Administrator, I want to view household records so that I can understand household details and supplier assignments. | Household list and details |
| US-03 | As an Administrator, I want to review plans and purchases so that I can understand subscription-related activities. | Plans and purchase screens |
| US-04 | As a Supplier, I want to view tank information so that I can monitor infrastructure status. | Tanks overview and details |
| US-05 | As a Supplier, I want to review refill history so that I can understand previous refill activities. | Refill history |
| US-06 | As a Supplier, I want to view alerts so that I can identify operational situations requiring attention. | Supplier and sensor alerts |

The identifiers above are used for traceability within this portfolio.

---

## 04. From User Story to Development Task

A user story describes a user's objective.

Development tasks describe the work required to support that objective.

The following examples connect documented AquaLink requirements to frontend implementation activities.

<div class="story-panel">

<span class="eyebrow">US-02 · Administrator</span>

### Household Information

**User need:** Review household records and related supplier and plan information.

**Related screens:** Household list and household details.

**Frontend considerations:**

- Present household identification clearly.
- Display supplier assignment and plan information.
- Provide navigation between list and detail views.
- Handle missing or incomplete information.
- Keep information consistent across related screens.

**Logbook evidence:** 18–19 August and 8 September 2026.

</div>

<div class="story-panel">

<span class="eyebrow">US-04 · Supplier</span>

### Tank Monitoring

**User need:** Review tank information and monitoring status.

**Related screens:** Tanks overview and tank details.

**Frontend considerations:**

- Display tank identifiers and capacity.
- Present water level and status information.
- Show the latest reading and its timestamp.
- Support navigation from overview to detail.
- Distinguish unavailable readings from valid monitoring data.

**Logbook evidence:** 13 August and 24–25 August 2026.

</div>

<div class="story-panel">

<span class="eyebrow">US-06 · Supplier</span>

### Operational Alerts

**User need:** Identify monitoring conditions that may require attention.

**Related screens:** Supplier alerts and sensor alert pages.

**Frontend considerations:**

- Display alert categories and severity.
- Distinguish normal, low, critical and unavailable conditions.
- Present stale or unavailable sensor information clearly.
- Avoid treating unusual readings as confirmed infrastructure faults.

**Logbook evidence:** 27–28 August and 17 September 2026.

</div>

---

## 05. Acceptance Criteria

Acceptance criteria establish the conditions that a feature should satisfy.

The logbook records the review and refinement of acceptance criteria, including an entry on 14 September 2026 comparing implemented screens with the agreed user stories.

The criteria below are my retrospective, testable interpretation of the documented requirements.

| User Story | Proposed Acceptance Criteria |
|---|---|
| US-01 | Dashboard information is readable and links to the relevant management screens |
| US-02 | Household records can be viewed, related information is displayed consistently, and navigation between list and detail works |
| US-03 | Plan and purchase information uses consistent status labels and does not imply that a payment has been processed unless verified |
| US-04 | Tank overview and detail information are consistent, with clear status and reading information |
| US-05 | Refill records show relevant tank references, dates and event information |
| US-06 | Alerts distinguish severity and unavailable readings, and do not present simulated sensor information as live data |

These criteria provide a practical way to evaluate the interface.

They do not establish that every backend or external integration was completed.

---

## 06. My Frontend Contribution

My contribution to AquaLink was strongly connected to turning requirements into usable interfaces.

I worked extensively on the application's visual presentation, page structure, navigation and user-facing functionality.

The Agile Logbook records activities involving:

- Reviewing the Admin dashboard layout on 17 August.
- Reviewing household list and detail workflows on 18–19 August.
- Reviewing Supplier monitoring and alert screens during 24–28 August.
- Reviewing global and role-specific styling from 31 August to 2 September.
- Checking navigation between application screens on 3–4 September.
- Reviewing responsive layouts and usability during September.

These activities demonstrate the relationship between requirements, frontend development and quality review.

One of my priorities was ensuring that AquaLink remained visually consistent as the number of screens increased.

I learned that a feature is not simply an isolated page. It must fit into the wider application experience.

---

## 07. Evidence from Trello

### Requirements and Development Tasks

![Original AquaLink Trello evidence 12](evidence/trello/trello-12.jpg)

*Original Trello screenshot from the project planning evidence collection.*

![Original AquaLink Trello evidence 13](evidence/trello/trello-13.jpg)

*Additional original Trello screenshot documenting project work.*

### Supporting Records

- [Original AquaLink Trello Board](https://trello.com/invite/b/6a61c8f1356d8a59c782231c/ATTIf9d9fdf7ec47fcd3745825ca9a054a2898604B70/aqualink)
- [Original Agile Logbook](evidence/documents/AquaLink_Agile_Logbook.docx)
- [Evidence Gallery](evidence-gallery.html)
- [Product Backlog](product-backlog.html)

---

## 08. My Reflection: The Importance of Acceptance Criteria

The most important lesson I learned from working with user stories was the value of defining what successful implementation actually means.

At first, it can be tempting to think of a feature as complete once the relevant screen exists.

However, the development process taught me that a screen must also satisfy the user's purpose.

For example, displaying household information is not enough if the records are difficult to understand or navigation between screens is confusing.

Similarly, a tank monitoring page should not simply display numbers. It should communicate whether those readings are current, unavailable or simulated.

This changed how I approached frontend development.

I began thinking more carefully about the relationship between a user's objective, the information displayed and the behaviour expected from the interface.

The logbook also helped me understand why acceptance criteria should be considered before implementation.

Clear criteria reduce uncertainty and provide a stronger basis for testing.

---

## 09. What I Would Improve

In future projects, I would strengthen the user-story process by:

1. Giving every user story a unique identifier from the beginning.
2. Recording acceptance criteria before implementation.
3. Linking Trello tasks directly to their parent user stories.
4. Connecting completed stories to screenshots and test results.
5. Recording whether a feature has been implemented, tested and accepted.
6. Distinguishing frontend completion from full system integration.
7. Reviewing requirements with the relevant users or stakeholders where possible.

These improvements would make the relationship between requirements and delivered functionality easier to verify.

---

## 10. Connection to Agile Practice

The Scrum Guide explains that the Product Backlog is an ordered list of work needed to improve a product and that backlog refinement involves breaking work into smaller, more precise items (Schwaber and Sutherland, 2020).

This principle connects directly to my experience of translating AquaLink requirements into application screens and development activities.

I learned that smaller, clearer requirements are easier to implement, review and test.

### Reference

Schwaber, K. and Sutherland, J. (2020) *The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game*. Available at: https://scrumguides.org/scrum-guide.html (Accessed: 7 November 2026).

---

## 11. Final Reflection

AquaLink taught me that successful frontend development begins with understanding the user's objective.

User stories helped connect the purpose of the application to the work required to build it.

Acceptance criteria helped me appreciate the difference between creating a screen and delivering a feature that satisfies its intended purpose.

As a developer, I want to carry this understanding into future projects by building interfaces that are not only visually appealing, but also clear, functional and testable.

**A user story defines the purpose of a feature. Acceptance criteria help determine whether that purpose has been achieved.**

---

[← Agile Team Charter](agile-team-charter.html)

[Next: Product Backlog →](product-backlog.html)

</div>
