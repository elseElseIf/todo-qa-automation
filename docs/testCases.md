# Test Cases

## TC-001 - Create a New Task

| Field | Value |
|-------|-------|
| ID | TC-001 |
| Title | Create a new task with a valid title |
| Priority | High |
| Preconditions | Application is launched |
| Steps | 1. Tap the Add button.<br>2. Enter a valid task title.<br>3. Tap Save. |
| Expected Result | A new task is successfully created and displayed in the task list. |
---

## TC-002 - Edit Existing Task

| Field | Value |
|-------|-------|
| ID | TC-002 |
| Title | Edit an existing task |
| Priority | High |
| Preconditions | At least one task exists |
| Steps | 1. Open an existing task.<br>2. Change the task title.<br>3. Tap Save. |
| Expected Result | The task is updated with the new title. |

---
## TC-003 - Delete Task

| Field | Value |
|-------|-------|
| ID | TC-003 |
| Title | Delete an existing task |
| Priority | High |
| Preconditions | At least one task exists |
| Steps | 1. Select a task.<br>2. Tap Delete.<br>3. Confirm deletion (if required). |
| Expected Result | The selected task is removed from the task list. |

---
## TC-004 - Create Task with Empty Title

| Field | Value                                                                     |
|-------|---------------------------------------------------------------------------|
| ID | TC-004                                                                    |
| Title | Attempt to create a task with an empty title                              |
| Priority | High                                                                      |
| Preconditions | Application is launched                                                   |
| Steps | 1. Tap the Add button.<br>2. Leave the title field empty.<br>3. Tap Save. |
| Expected Result | The application displays a validation message and prevents task creation. |

---

## TC-005 - Verify Data Persistence

| Field | Value |
|-------|-------|
| ID | TC-005 |
| Title | Verify tasks are saved after restarting the application |
| Priority | High |
| Preconditions | At least one task exists |
| Steps | 1. Close the application.<br>2. Launch the application again. |
| Expected Result | Previously created tasks are displayed after reopening the application. |