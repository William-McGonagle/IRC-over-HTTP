## Auth

GET     /auth/2FA/

GET     /auth/2FA/:auth_scheme

GET     /auth/2FA/:auth_scheme/callback

POST    /auth/login

POST    /auth/signup

DELETE  /auth/logout


## Messaging

GET     /server/

POST    /server/create

GET     /server/:server/

POST    /server/:server/edit

POST    /server/:server/member/add

GET     /server/:server/member/

GET     /server/:server/member/:memberId/

GET     /server/:server/channels

GET     /server/:server/:channel/

GET     /server/:server/:channel/messages

GET     /server/:server/:channel/:messageId/

POST    /server/:server/:channel/send   
	(for plaintext)

PUT     /server/:server/:channel/send   
	(for files)
