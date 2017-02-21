notifications.updateFavPromo

$description
Updates notification created by {% replace_method notifications.sendFavPromo %} call.

$params#id
Notification id

$params#text
Notification text

$params#image
Custom notification image or game icon by default

$params#mark
custom_args value

$params#expires
Expiration time 
Format: yyyy.MM.dd HH:mm

**Note**: Max value is 14 days since now (Time zone is MSK(UTC+03:00))

$params#status
* PUBLIC or P
* ADMINS_ONLY or A

$additional
