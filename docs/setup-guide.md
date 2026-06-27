# Setup Guide

## Prerequisites

* Microsoft 365
* Power Apps
* Power Automate
* SharePoint Online

## Import Solution

Navigate to:

Power Apps → Solutions → Import Solution

Import:

AbsenceManager_managed.zip

## Configure Connections

Configure:

* SharePoint
* Office 365 Users
* Office 365 Outlook

## Configure SharePoint Lists

Create:

1. Requests
2. Absence Types

Refer to sharepoint-schema.md for the required structure.

## Validation

Verify:

* Requests can be submitted
* Approval workflow triggers correctly
* Status updates are written to SharePoint
* Notifications are delivered successfully
