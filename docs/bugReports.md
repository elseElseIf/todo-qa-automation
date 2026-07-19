# BUG-1

## Title
Application allows creating a task with an empty title.

## Severity
Medium

## Priority
Medium

## Environment
Android Emulator
Android 14

## Preconditions
Application is running.

## Steps to Reproduce
1. Tap the Add button.
2. Enter a space in the Task Title field.
3. Tap Save.

## Expected Result
The application should display a validation message and prevent task creation.

## Actual Result
The task is created with an empty title.

### Attachments
Screenshot: src/empty_title_bug.png

## Status
Open

