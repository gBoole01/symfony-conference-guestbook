# Docker Container (PgSql && Mailer)

`cd ~/Code/guestbook && docker-compose up`

# Server Symfony

`cd ~/Code/guestbook && symfony server:start`

# Mailcatcher Symfony

`symfony open:local:webmail`

# Server Symfony Logs

`cd ~/Code/guestbook && symfony server:log`

# Launch Message Worker in Dev Mode (Watch for Changes)

`symfony run -d --watch=config,src,templates,vendor symfony console messenger:consume async -vv`

# Watch Server Activity (Retrieve Workers PID)

`symfony server:status`

# Stop Worker

`kill {workerPID}`
