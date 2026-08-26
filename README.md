# Live Update / progress-centric notifications lab
Simula una entrega de 0 a 100. En Android 16+ usa `NotificationCompat.ProgressStyle` con segmentos, puntos y `setShortCriticalText`; en versiones anteriores degrada a una notificación normal. Solicita `POST_NOTIFICATIONS` en Android 13+ y actualiza con `setOnlyAlertOnce(true)`.
