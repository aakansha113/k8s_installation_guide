---
## step to install 
## Add current user to docker group (To use docker without root)
```
sudo usermod -aG docker $USER && newgrp docker
```

Now, logout (use exit command) and connect again.

### create one folder as kind_cluster
 ```
 vim installation.sh
 ```

### first change the permission of installation.sh as
 ```
 sudo chmod 777 installation
 ```

### Run 
```
./installation.sh 

 ```


