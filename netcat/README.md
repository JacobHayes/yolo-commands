# Tell nc to listen to a port # 3005 and execute /usr/bin/w command when client connects and send data back to the client
nc -l -p 3005 -e /usr/bin/w
