# Chapter 8: Scrum Artifacts

---

# 8. Scrum Artifacts

## 8.1 Introduction

Scrum Artifacts are essential components of the Scrum framework that provide transparency about the work being performed and the value being delivered. They represent important information that enables the Scrum Team and stakeholders to inspect progress, make informed decisions, and adapt to changing requirements.

According to the Scrum Guide (2020), Scrum defines **three official artifacts**:

- Product Backlog
- Sprint Backlog
- Increment

Each artifact supports one or more Scrum Events and contributes to achieving the Product Goal and Sprint Goal.

---

# 8.2 Purpose of Scrum Artifacts

Artifacts exist to make work visible.

By providing a shared understanding of project status, artifacts help teams:

- Improve transparency
- Facilitate inspection
- Support adaptation
- Prioritize work effectively
- Measure progress
- Deliver customer value

Without these artifacts, teams would struggle to coordinate work and maintain alignment with project objectives.

---

# 8.3 Overview of Scrum Artifacts

| Artifact | Owner | Purpose |
|-----------|-------|----------|
| Product Backlog | Product Owner | Defines all desired product work |
| Sprint Backlog | Developers | Defines work for the current Sprint |
| Increment | Scrum Team | Represents completed, usable functionality |

Together, these artifacts provide a complete picture of the project's current state.

---

# 8.4 Product Backlog

## 8.4.1 Definition

The **Product Backlog** is an ordered list of everything that may be needed in the product.

It serves as the single source of work for the Scrum Team and evolves continuously throughout the project.

Unlike traditional requirement documents, the Product Backlog is dynamic rather than fixed.

---

## 8.4.2 Characteristics

A Product Backlog should be:

- Ordered by priority
- Continuously refined
- Visible to stakeholders
- Flexible
- Value-driven
- Continuously updated

As customer requirements change, backlog items are added, modified, removed, or reprioritized.

---

## 8.4.3 Product Backlog Items

Each Product Backlog Item (PBI) typically contains:

- Title
- Description
- Business value
- Priority
- Acceptance criteria
- Estimated effort

Example:

| ID | Feature | Priority |
|----|----------|----------|
| PB-01 | User Login | High |
| PB-02 | Online Payment | High |
| PB-03 | Notifications | Medium |
| PB-04 | Dark Mode | Low |

---

## 8.4.4 Product Backlog Refinement

Backlog refinement is an ongoing activity in which the Product Owner and Developers collaborate to improve Product Backlog Items.

Typical refinement activities include:

- Clarifying requirements
- Splitting large features
- Estimating effort
- Removing obsolete items
- Reordering priorities

A well-maintained backlog enables more effective Sprint Planning.

---

# 8.5 Sprint Backlog

## 8.5.1 Definition

The **Sprint Backlog** contains the Product Backlog Items selected for the current Sprint, along with a plan for delivering them.

It belongs to the Developers, who are responsible for updating it throughout the Sprint.

The Sprint Backlog answers three important questions:

- What work will be completed?
- How will the work be completed?
- How does the work support the Sprint Goal?

---

## 8.5.2 Characteristics

The Sprint Backlog is:

- Created during Sprint Planning
- Updated daily
- Visible to the entire team
- Flexible during the Sprint
- Focused on achieving the Sprint Goal

Unlike the Product Backlog, it only contains work for the current Sprint.

---

## 8.5.3 Example Sprint Backlog

| Task | Status |
|------|--------|
| Design Login Screen | Completed |
| Implement Authentication | In Progress |
| Database Integration | Not Started |
| Unit Testing | Not Started |

This artifact helps Developers monitor daily progress.

---

# 8.6 Increment

## 8.6.1 Definition

The **Increment** is the sum of all completed Product Backlog Items at the end of a Sprint.

Each Increment must be:

- Complete
- Tested
- Integrated
- Potentially releasable

An Increment represents actual customer value rather than unfinished work.

---

## 8.6.2 Characteristics

A Scrum Increment should be:

- Functional
- High quality
- Fully integrated
- Usable
- Tested
- Valuable

If work does not meet the Definition of Done, it cannot be considered part of the Increment.

---

## 8.6.3 Definition of Done

The **Definition of Done (DoD)** specifies the quality standards required before work can be considered complete.

Typical Definition of Done criteria include:

- Code completed
- Code reviewed
- Unit tests passed
- Integration tests passed
- Documentation updated
- No critical defects
- Approved by the Product Owner

The Definition of Done promotes consistency and quality across all Sprints.

---

# 8.7 Relationship Between Scrum Artifacts

The three artifacts are closely connected.

```
Product Backlog
        │
        ▼
Sprint Planning
        │
        ▼
Sprint Backlog
        │
        ▼
Development Work
        │
        ▼
Increment
        │
        ▼
Sprint Review
        │
        ▼
Updated Product Backlog
```

This continuous flow ensures transparency and supports iterative product development.

---

# 8.8 Artifact Commitments

The Scrum Guide associates each artifact with a specific commitment that provides focus and purpose.

| Artifact | Commitment |
|-----------|------------|
| Product Backlog | Product Goal |
| Sprint Backlog | Sprint Goal |
| Increment | Definition of Done |

These commitments help ensure that every Sprint contributes toward long-term product success.

---

# 8.9 Benefits of Scrum Artifacts

Effective use of Scrum Artifacts provides numerous advantages:

- Greater project transparency
- Better prioritization
- Improved collaboration
- Continuous progress tracking
- Higher software quality
- Easier stakeholder communication
- Faster decision-making
- Better alignment with business goals

Artifacts provide the information necessary for evidence-based decision-making throughout the project.

---

# 8.10 Practical Example

Consider a team developing an online food delivery application.

The **Product Backlog** contains features such as:

- User registration
- Restaurant search
- Online payment
- Order tracking

During Sprint Planning, the Developers select:

- User registration
- Login functionality

These items become the **Sprint Backlog**.

After completing, testing, and integrating both features, they become part of the **Product Increment**, ready for demonstration during the Sprint Review.

---

# 8.11 Chapter Summary

This chapter introduced the three Scrum Artifacts: the Product Backlog, Sprint Backlog, and Increment. It explained their purpose, ownership, characteristics, and relationship within the Scrum framework. The chapter also discussed Product Backlog refinement, the Definition of Done, and artifact commitments introduced in the Scrum Guide. Together, these artifacts provide transparency, support continuous inspection and adaptation, and ensure that every Sprint delivers measurable customer value.

The next chapter examines the **Scrum Workflow**, illustrating how Roles, Events, and Artifacts interact throughout the iterative development cycle.
