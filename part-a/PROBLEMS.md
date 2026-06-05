## Problem 1: Tatkal Booking Crashes at 10:00 AM [Given]

### What is broken

Users attempting Tatkal booking at 10 AM frequently experience
timeouts, page freezes, session expirations, and payment failures.

### Affected users

Daily Tatkal passengers
Urgent business travelers
Students
Medical emergency travelers

### Frequency

Daily
Occurs around 10:00 AM when Tatkal quota opens.

### Current flow

1. User logs in at 9:50 AM.
2. Searches train.
3. Opens Tatkal quota.
4. Waits for 10 AM.
5. Clicks Book Now.
6. System begins processing.
7. Page freezes.
8. User refreshes.
9. Session expires.
10. Tatkal quota disappears.

### Where exactly it breaks

Step 6-7.

Booking request spikes dramatically and the user receives no queue
position, progress indicator, or meaningful feedback.