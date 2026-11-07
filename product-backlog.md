
---
layout: default
title: Product Backlog
permalink: /product-backlog.html
---

<div class="page-content" markdown="1">

<span class="eyebrow">Agile Portfolio · Product Planning & Prioritisation</span>

# Product Backlog

### Deciding what matters, what comes first, and what remains.

AquaLink was an ambitious project with several interconnected features.

Our proposed solution included administration, household management, suppliers, water tanks, subscriptions, purchases, monitoring and alerts.

The challenge was not simply identifying these features.

It was understanding their dependencies, organising the work and making realistic decisions about what could be delivered.

As Project Lead and a substantial frontend contributor, I experienced the importance of these decisions throughout development.

---

## 01. The Purpose of Our Product Backlog

The Product Backlog provided an organised view of the work required to develop AquaLink.

Our project records show that backlog activities were reviewed during requirements analysis, frontend implementation, testing and final preparation.

The original Agile Logbook includes a taskboard that separates:

- Product Backlog / Remaining
- In Progress / Immediate Focus
- Completed

This distinction helped us understand the difference between work that had already been recorded as complete and work that still required attention.

<div class="story-panel">

<span class="eyebrow">A Key Development Lesson</span>

### An interface can be complete while an integration remains outstanding.

One of the most important distinctions in our backlog was separating completed application screens from live database, payment-provider and physical sensor integrations.

This prevented the scope of the working application from being confused with the full future vision of AquaLink.

</div>

---

## 02. Original Backlog Priorities

The original Agile Logbook contains a prioritised list of remaining work.

The following table reproduces its priority categories in a more accessible portfolio format.

| Priority | Backlog Item | Recorded Requirement |
|---|---|---|
| P1 | Real database integration | Connect the interface to persistent backend data and verify CRUD workflows |
| P1 | Payment integration | Implement and test a real payment-provider workflow where the required setup is available |
| P1 | IoT and hardware integration | Connect physical sensors or clearly label simulated readings |
| P1 | Final documentation and submission | Complete setup instructions, architecture, testing evidence and limitations |
| P1 | Demo presentation | Prepare and rehearse a reliable walkthrough |
| P1 | Live presentation | Present the business idea, architecture, application and future integrations |
| P2 | Mobile application development | Treat as a future enhancement unless specifically required |

**Source:** AquaLink Agile Logbook, Product Backlog / Remaining taskboard.

These priorities were organised around dependencies and the presentation milestone of 3 November 2026.

The distinction between P1 and P2 was especially important because the team had limited time to complete finalisation activities.

---

## 03. Completed Product Backlog Items

The logbook taskboard records the following work as completed during the documented project period.

### Requirements and Architecture

- User stories and acceptance criteria.
- Database schema design.

The schema design was recorded as complete, while live database integration remained a separate task.

### Shared Application Components

- Global stylesheet and shared logic.
- Admin stylesheet, shared logic and error page.
- Supplier stylesheet and shared logic.
- Integration and navigation bar.

### Administrator Features

- Admin dashboard.
- Household list.
- Household details.
- Plans management.
- Purchase page.

### Supplier Features

- Tanks overview.
- Tank details.
- Refill history.
- Supplier alerts.
- Sensor alerts.

### Quality and Testing

- Admin screen implementation and screen testing.
- Supplier screen implementation and screen testing.
- Application bug fixing and regression testing.
- Browser and responsive testing.

These completion statuses come from the original dated logbook and its taskboard.

---

## 04. How Dependencies Influenced Prioritisation

Not all backlog items could be completed independently.

Some features required other parts of the application to be available first.

<div class="card-grid">

<div class="feature-card">

<span class="card-icon">01</span>

### Frontend Dependencies

Shared navigation, styling and reusable logic supported multiple Admin and Supplier screens.

</div>

<div class="feature-card">

<span class="card-icon">02</span>

### Data Dependencies

Persistent household, supplier and subscription workflows depended on backend and database integration.

</div>

<div class="feature-card">

<span class="card-icon">03</span>

### External Dependencies

Payment processing and physical sensor monitoring required services or hardware beyond the interface itself.

</div>

</div>

These dependencies influenced how we interpreted progress.

For example, the presence of a purchase page did not automatically establish that a real payment provider was connected.

Similarly, a tank monitoring screen did not establish that physical sensors were transmitting live readings.

This distinction helped us evaluate the product more accurately.

---

## 05. Evidence of Backlog Refinement

The Agile Logbook provides dated examples of how the backlog was reviewed as the project developed.

| Date | Recorded Activity | Backlog Significance |
|---|---|---|
| 29 July 2026 | Organised requirements for plans, purchases, tank monitoring, refill history and alerts | Grouped features under the agreed backlog |
| 31 July 2026 | Consolidated user-story scope and prepared development priorities | Prepared the next implementation activities |
| 7 August 2026 | Consolidated UI feedback and mapped remaining screens to the backlog | Connected design review to outstanding tasks |
| 5 October 2026 | Reviewed the completed application against user stories | Confirmed implemented screens and identified integration boundaries |
| 22 October 2026 | Reviewed remaining work and task ownership | Supported final task tracking |
| 29 October 2026 | Reviewed the 11-sprint roadmap and reprioritised remaining work | Focused attention on documentation, rehearsal and presentation |

**Primary evidence:** AquaLink Agile Logbook, dated entries.

[Download the Original Agile Logbook](evidence/documents/AquaLink_Agile_Logbook.docx)

---

## 06. Prioritising the Final Delivery

As the presentation milestone approached, the logbook identified a practical order for the remaining work.

<div class="story-panel">

<span class="eyebrow">Final Delivery Priorities</span>

### Protect the working application.

**First:** Verify the completed Admin and Supplier screens and confirm the demonstration route.

**Second:** Complete documentation and ensure that the business model and architecture match the implemented solution.

**Third:** Test the presentation environment and explain which integrations are complete and which remain outstanding.

**Fourth:** Rehearse the demonstration and keep mobile application development as a future enhancement.

</div>

This sequence demonstrated an important prioritisation principle: introducing additional functionality late in development could create unnecessary risk.

The immediate priority became presenting a stable, accurately described application.

---

## 07. Original Trello Evidence

The following screenshots are from our original AquaLink Trello evidence collection.

### Product Backlog Screenshot 01

![AquaLink Trello Product Backlog evidence 01](evidence/trello/trello-01.jpg)

### Product Backlog Screenshot 02

![AquaLink Trello Product Backlog evidence 02](evidence/trello/trello-02.jpg)

### Product Backlog Screenshot 03

![AquaLink Trello Product Backlog evidence 03](evidence/trello/trello-03.jpg)

### Additional Evidence

- [Original Trello Board](https://trello.com/invite/b/6a61c8f1356d8a59c782231c/ATTIf9d9fdf7ec47fcd3745825ca9a054a2898604B70/aqualink)
- [Original Agile Logbook](evidence/documents/AquaLink_Agile_Logbook.docx)
- [Evidence Gallery](evidence-gallery.html)
- [Sprint Backlog](sprint-backlog.html)

---

## 08. My Contribution to Backlog Delivery

As a substantial frontend contributor, my work was closely connected to the implementation of AquaLink's user-facing features.

I focused on the appearance, structure and usability of the application.

This included reviewing layouts, navigation, shared styling and the consistency of Admin and Supplier screens.

The logbook records frontend activities across August and September, including:

- Reviewing the Admin dashboard and household workflows.
- Reviewing Supplier tank monitoring and alert interfaces.
- Consolidating shared styles and application navigation.
- Checking responsive behaviour and browser consistency.
- Reviewing implemented screens against the agreed requirements.

As Project Lead, I also had to consider how frontend progress related to other development dependencies.

A completed screen could still depend on data integration.

A working navigation flow could still require further testing.

These relationships helped me appreciate why backlog items need clear definitions of completion.

---

## 09. My Personal Reflection: Learning to Prioritise

The Product Backlog taught me that successful development requires making difficult choices.

At the beginning of AquaLink, I was excited by the number of features the platform could eventually provide.

I wanted the application to be visually professional, functional and capable of demonstrating the value of the solution.

However, the development process showed me that not every feature could receive equal attention at every stage.

Some tasks were essential to the demonstration.

Others depended on external services.

Some improvements could be deferred without preventing the team from presenting the core application.

The decision to keep mobile application development as a future enhancement was a useful example.

It showed that postponing a feature does not necessarily mean abandoning the idea.

Sometimes it means protecting the quality and stability of the work that matters most at the current stage.

### What I Learned About Completion

One of the most valuable lessons was the difference between completing an interface and completing an end-to-end workflow.

For example, a purchase page may look finished and allow the user to navigate through its intended interface.

However, without a verified payment-provider integration, it should not be described as a fully operational payment system.

The same principle applies to database persistence and physical sensor readings.

This distinction changed how I think about reporting software progress.

I learned that professional communication requires accurately describing what has been implemented, what has been tested and what remains dependent on other components.

---

## 10. What I Would Improve

In a future project, I would strengthen Product Backlog management by:

1. Assigning clear priority levels to every important backlog item.
2. Defining acceptance criteria and a clear completion standard.
3. Recording dependencies between frontend, backend and external integrations.
4. Linking backlog items to relevant user stories and test evidence.
5. Reviewing priorities when deadlines or resources change.
6. Separating future enhancements from current delivery commitments.
7. Recording why significant prioritisation decisions were made.

These improvements would make backlog decisions easier to understand, defend and evaluate.

---

## 11. Connection to Agile Practice

The Scrum Guide describes the Product Backlog as an ordered, evolving list of the work needed to improve a product (Schwaber and Sutherland, 2020).

This principle connects directly to AquaLink because our priorities changed as the project approached its presentation milestone.

The backlog was not simply a list of desired features.

It became a way of identifying the most important remaining work and recognising the limits of what could realistically be demonstrated.

### Reference

Schwaber, K. and Sutherland, J. (2020) *The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game*. Available at: https://scrumguides.org/scrum-guide.html (Accessed: 7 November 2026).

---

## 12. Final Reflection

AquaLink taught me that prioritisation is one of the most important responsibilities in software development.

The Product Backlog helped connect our larger vision to practical development decisions.

As a frontend contributor, it helped me understand how individual screens fitted into the broader application.

As Project Lead, it helped me recognise the importance of managing dependencies, controlling scope and communicating progress accurately.

**Good backlog management is not about building everything at once. It is about making informed decisions about what should be delivered next, and why.**

---

[← User Stories and Tasks](user-stories-and-tasks.html)

[Next: Sprint Backlog →](sprint-backlog.html)

</div>
