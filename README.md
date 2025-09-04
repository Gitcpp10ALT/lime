# lime
Lime is a simple reverse shell, that uses the Python Library pywinpty. It has full interactive shell.
# Installation
Just download the zip, extract it and you are done!
# Usage
In command prompt.
**For listener**
```cmd
lime listen -ip [ip address, if not specified listens on localhost] -p [port number]
```
**For connecting to a listener**
```
lime connect -ip [ip of listener] -p [port number]
```
**For connecting to a listener forever**
```
lime forever -ip [ip of listener] -p [port number]
```
