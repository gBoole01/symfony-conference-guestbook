# Docker Container (PgSql && Mailer)

`cd ~/Code/guestbook && docker-compose up`

# Server Symfony

`cd ~/Code/guestbook && symfony server:start`

# Mailcatcher Symfony

`cd ~/Code/guestbook && symfony open:local:webmail`

# Webpack Compilator

`cd ~/Code/guestbook && symfony run yarn dev --watch`

# Server Symfony Logs

`cd ~/Code/guestbook && symfony server:log`

# Launch Message Worker in Dev Mode (Watch for Changes)

`cd ~/Code/guestbook && symfony run -d --watch=config,src,templates,vendor symfony console messenger:consume async -vv`

# Watch Server Activity (Retrieve Workers PID)

`cd ~/Code/guestbook && symfony server:status`

# Stop Worker

`kill {workerPID}`
