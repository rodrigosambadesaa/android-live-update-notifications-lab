# Android Live Update Notifications Lab

Original demo of Android's promoted ongoing **Live Update** notification model using AndroidX Core `NotificationCompat.ProgressStyle`.

- User starts a simulated, time-sensitive delivery journey.
- A progress-centric ongoing notification advances from 0 to 100%.
- Requests promoted-ongoing treatment with `setRequestPromotedOngoing(true)`.
- Declares `POST_PROMOTED_NOTIFICATIONS` and requests `POST_NOTIFICATIONS` where required.
- Uses segments and a milestone point; Android versions below the progress-style platform support fall back to a standard notification.
- The demo ends cleanly with a normal completion notification or can be cancelled by the user.

Promotion is ultimately controlled by Android, the user's settings and OEM criteria. Live Updates should only represent ongoing, user-initiated, time-sensitive activity—not ads or generic shortcuts.
