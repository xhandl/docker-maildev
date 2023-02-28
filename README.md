# MailDev
### Run and go Docker setup for MailDev.

<br />

To start MailDev on background via Docker just type:
```
docker compose up -d
```

Main parameters can be modified via `.env` file.


Default configuration:
```
IMAGE: maildev/maildev:2.0.5
CONTAINER NAME: maildev
WEB_PORT: 1080
SMTP_PORT: 1025
```
