# Solution Architecture

## High-Level Architecture

Employee
↓
Power Apps Canvas Application
↓
SharePoint Requests List
↓
Power Automate Approval Flow
↓
Approver / Deputy
↓
Approved / Rejected
↓
SharePoint Status Update
↓
Email Notification

## Components

### Power Apps

Provides the user interface for absence request submission and status tracking.

### SharePoint

Stores absence requests, approval history, and absence type configuration.

### Power Automate

Handles approval routing, notifications, and status updates.

### Office 365 Services

Provides user lookup and email communication capabilities.

## Design Considerations

* Low-code architecture
* Easy deployment
* SharePoint-native storage
* Scalable approval model
* Power BI integration ready

## Future Architecture Enhancements

* Dataverse migration
* Teams integration
* Power BI analytics layer
* Role-based security enhancements
