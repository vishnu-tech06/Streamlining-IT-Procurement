# Streamlining IT Procurement

## Project Overview

**Streamlining IT Procurement** is a ServiceNow-based workflow automation project designed to simplify and automate the processing of Standard Laptop requests.

The solution automates task creation after the configured approval condition is met and ensures that approved laptop requests are automatically routed to the appropriate **Hardware assignment group**.

## Objectives

- Automate Catalog Task creation for approved laptop requests
- Reduce manual intervention in the IT procurement process
- Improve request processing efficiency
- Ensure consistent task routing to the Hardware team
- Provide better visibility into the request fulfillment process

## Workflow

The automated process follows these steps:

```text
Standard Laptop Request
        ↓
Approval Validation
        ↓
Approval Condition Met
        ↓
Automatic Catalog Task Creation
        ↓
Assignment to Hardware Group
        ↓
Laptop Configuration & Fulfillment


Key Features
Automated Task Creation

Once the configured approval condition is satisfied, the workflow automatically creates a Catalog Task under the related Requested Item.

Automatic Assignment

The generated Catalog Task is automatically assigned to the Hardware assignment group for further processing.

Request Traceability

The Catalog Task remains associated with the original Requested Item, allowing the Hardware team to track and process the request efficiently.

Technology
Platform: ServiceNow
Automation: Flow Designer / Workflow Studio
Request Type: Standard Laptop
Task Type: Catalog Task
Assignment Group: Hardware
Expected Outcome

The automation minimizes manual task creation, improves processing efficiency, and ensures that approved Standard Laptop requests are consistently routed to the appropriate Hardware team.

Project Demonstration

The demonstration covers the complete workflow:

Submit a Standard Laptop request
Verify the Requested Item
Complete the configured approval process
Trigger the automation
Verify automatic Catalog Task creation
Verify assignment to the Hardware group
Project Evidence

Screenshots and supporting documentation are included in this repository to demonstrate the implemented workflow and its execution in ServiceNow.

Conclusion

This project demonstrates how ServiceNow workflow automation can streamline IT procurement operations by automating task creation and assignment for approved Standard Laptop requests.
