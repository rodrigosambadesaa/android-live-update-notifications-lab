# Live Update / progress-centric notifications lab
Simula un trayecto activo de reparto de 0 a 100. En Android 16+ usa `Notification.ProgressStyle` con segmentos y puntos; solicita tratamiento promoted-ongoing mediante extras compatibles. En versiones anteriores degrada a una notificación de progreso normal. Solicita `POST_NOTIFICATIONS` en Android 13+ y declara `POST_PROMOTED_NOTIFICATIONS`.
