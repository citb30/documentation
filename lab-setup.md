## Setup the Lab by following the steps.

### 1. Create a new server with centos 7 OS.

### 2. Login to server and run the following command.

```
$ curl -s https://raw.githubusercontent.com/linuxautomations/scripts/master/init.sh | sudo bash
```

### 3. Once after running the script, Server will get shutdown and reconnect back and then shutdown the server.

### 4. Next Goto Images in "Compute Engine" and Click on New Image.

name: mycentos7

source-disk : name-of-the-server

