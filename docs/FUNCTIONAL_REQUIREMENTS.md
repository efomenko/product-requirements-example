# Functional Requirements

## Purpose 

Describes the specific behaviors and capabilities the product must provide. These requirements translate user needs into clear system behavior that can be implemented and tested by engineering.

## FR-01 Workflow Creation

The system shall allow users to create a workflow.

Required fields:

- Name
- Description
- Trigger

---

## FR-02 Trigger Configuration

The system shall provide a catalog of available triggers.

Each trigger shall expose:

- Name
- Description
- Event type
- Available properties

---

## FR-03 Conditions

Users shall be able to add one or more conditions.

Supported operators:

- Equals
- Not equals
- Contains
- Greater than
- Less than
- Is empty
- Is not empty

---

## FR-04 Actions

Users shall be able to configure one or more actions.

Each action shall expose its required parameters.

---

## FR-05 Workflow State

A workflow shall support:

- Draft
- Enabled
- Disabled
- Error

---

## FR-06 Execution History

The system shall provide:

- Execution timestamp
- Trigger
- Status
- Duration
- Error information
