# USE CASE: 6 View an employee's details so that a promotion request can be supported.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to view an employee's details so that the employee's promotion request can be supported.

### Scope

Company.

### Level

Primary task.

### Preconditions

The Employee's details are in the database.

### Success End Condition

The employee's details can be viewed.

### Failed End Condition

The details cannot be viewed.

### Primary Actor

HR Advisor.

### Trigger

A request for promotion is recieved from an employee.

## MAIN SUCCESS SCENARIO

1. A request for promotion is recieved.
2. HR can view an employees details.


## EXTENSIONS

3. **The employee's details are not present**:
    1. HR advisor add's the employees details, see use case 5.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0