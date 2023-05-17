### EXPOSE
EXPOSE instruction is usefull to tell the users of the image about the ports and protocols images/containers is opening. It will not have any functionality it is used only to tell the information

EXPOSE <port number>/<protocol>

Here's an example:
```
EXPOSE 8080/tcp
```