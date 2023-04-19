# when error 'port already use' to run server

Kill command

sudo lsof -t -i tcp:8000 | xargs kill -9
