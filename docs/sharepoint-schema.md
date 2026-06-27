# SharePoint Data Model

## Requests List

Stores employee absence requests and approval information.

| Column                 | Purpose                   |
| ---------------------- | ------------------------- |
| Person                 | Request submitter         |
| Approver               | Assigned approver         |
| Deputy                 | Assigned deputy           |
| From                   | Start date                |
| To                     | End date                  |
| Request Comments       | Employee comments         |
| Approver Comments      | Approval comments         |
| Status                 | Request status            |
| Approval/Rejected Date | Decision timestamp        |
| Approved/Rejected By   | Decision maker            |
| AbsenceType            | Selected absence category |

### Status Values

* In-Progress
* Approved
* Rejected

---

## Absence Types List

Stores absence category configuration.

| Absence Type     | Needs Approval | Needs Deputy |
| ---------------- | -------------- | ------------ |
| Sick Leave       | No             | No           |
| Vacation         | Yes            | Yes          |
| Military Service | Yes            | No           |
| Maternity Leave  | No             | Yes          |

### Purpose

Allows administrators to control approval behavior without modifying application logic.

This design makes the solution flexible and scalable for future absence categories.
