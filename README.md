# Apple Reminder + Calendar Sync
An iOS shortcut to create calendar events for reminders with date and time assigned. This is based off of [Reminders2Calendar](https://github.com/cinaq/reminders2calendar/) from [Xiwen Cheng](https://www.cinaq.com) with my own updates and additions.

### What it Does
When a reminder has a date, or date and time set, it will add a calendar event for the reminder including any notes. The event will reflect updates made to the date or time. If the reminder is completed, or if the date AND time are removed, the calendar event will be removed. There are two mechanisms used to maintain the relation between the remidner and event, a `#cal` tag is added to a reminder when there is an associated calendar event, and the calendar event will have a unique ID in the event notes.

### How to Install
TBD

### How to Use
TBD

### Testing
| Test Case                                              | Status             |
| ------------------------------------------------------ | ------------------ |
| New reminder with date creates all-day event           | :white_check_mark: |
| New reminder with date and time creates standard event | :white_check_mark: |
| Re-add event when date re-added to reminder            | :white_check_mark: |
| Add notes to new reminder                              | :white_check_mark: |
| Updating date moves the all-day event                  | :white_check_mark: |
| Updating date/time moves the standard event            | :white_check_mark: |
| Update notes on updated reminder                       | :white_check_mark: |
| Remove reminder time converts to all-day event         | :white_check_mark: |
| Remove date/time deletes the event                     | :white_check_mark: |
| Completing the reminder deletes the event              | :white_check_mark: |
| Add #cal tag to reminder when creating an event        | :white_check_mark: |
| Keep #cal tag to reminder when updating an event       | :white_check_mark: |
| Remove #cal tag from reminder when deleting an event   | :white_check_mark: |
