# windows-notification
from plyer import notification

notification_name= 'windows'
notification_message = 'update your system'

notification.notify(
	title=notification_name,
	message=notification_message,
	timeout=10,
	toast=False
)
