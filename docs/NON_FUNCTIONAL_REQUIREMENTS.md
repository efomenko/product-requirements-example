# Non-Functional Requirements

## Reliability

Workflow execution should be resilient to temporary integration failures.

## Observability

Failed executions must be identifiable by users and operators.

## Security

Actions must execute using the permissions associated with the configured
integration.

## Performance

Normal workflow execution should complete within an acceptable operational
timeframe.

## Scalability

The architecture should support increasing numbers of workflows and executions
without requiring customers to redesign their workflows.

## Auditability

Important workflow configuration changes and executions should be traceable.
