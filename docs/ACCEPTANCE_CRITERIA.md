# Acceptance Criteria

## Purpose

Defines the conditions that must be satisfied for each major capability to be considered complete. Acceptance criteria use clear, testable scenarios to align Product, Engineering, and QA on expected behavior.

## Create Workflow

**Given** the user is on the workflow creation page

**When** the user provides a valid workflow name and trigger

**Then** the workflow can be saved.

## Enable Workflow

**Given** a workflow is configured

**When** the user enables the workflow

**Then** new matching events should trigger the workflow.

## Condition

**Given** a workflow contains a condition

**When** an incoming event does not satisfy the condition

**Then** the workflow should not execute the configured action.

## Action

**Given** a workflow is enabled

**When** a matching event is received

**Then** the configured action should be executed.
