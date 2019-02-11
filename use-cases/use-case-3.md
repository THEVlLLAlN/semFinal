# USE CASE: 3 Produce a Report on the Salary of all Employees in my Department.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.
### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current employee salary data.

### Success End Condition

A report is available for the department manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager

### Trigger

A request for finance information is sent to the Department Manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for all employees in your department.
2. Department Manager extracts current salary information of all employees in their department.
3. Department Manager provides report to finance.

## EXTENSIONS

2. **There is no salary information**:
    1. Department Manager informs finance no salary information exists.
   

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0