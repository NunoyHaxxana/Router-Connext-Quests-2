![router setup](https://user-images.githubusercontent.com/83507970/170120644-be13ee8c-486c-43e5-a2ce-f88c4f2aaaa5.png)

# Discord handle: 
- Haxxana#5597

# Name of the challenge/quest you are applying for: 
- Quest 2 - Quick router setup.

# Briefly describe your project: 
- Developer shell script to help the user who needs to setup and upgrade a router to last version.  

>:black_square_button: Script Automate to install Connext Router by auto detected last version + Auto update last version.<br>

# Detailed project proposal:
- Automate to install Docker.
- Automate to install Docker-compose v2.5.1
- Automate to install nxtp-router.
- Automate to get & install Latest version.
- Automate to get & update Latest version.
- Automate to generate private key.
- Automate to backup private key.
- Automate to swith to amarok.
- Automate to create and config file .env, key.yaml, config.json
- Automate to delete nxtp-router file and docker-compose.


---


### Requirements

- OS Ubuntu 18.04 or 20.04 
>:black_square_button: 8GB RAM<br>
>:black_square_button: 30GB Storage<br>
- Need Super user or root for run this script.
- You can check the current Router version in the https://github.com/connext/nxtp/releases


## Clone and Install Scripts

```

wget -q -O router_setup.sh https://raw.githubusercontent.com/NunoyHaxxana/nxtp-router-docker-config/main/router_setup_v2.sh && chmod +x router_setup.sh && sudo /bin/bash router_setup.sh
```




![image](https://user-images.githubusercontent.com/83507970/170120882-96064529-8c8f-444d-880a-c9f4e188f6b1.png)

Choose you wanted option (for example option 1 Install with Auto PKey), press enter and wait for installation to complete.

 **1) Install with Auto PKey** `Automatically Install router and generate private key`


 **2) Install with Your PKey** `Automatically Install router with your private key`


 **3) Upgrade Version** `Upgrade router to new version`


 **4) Backup PKey** `Backup and show your private key`


 **5) Delete** `Delete Router and Data File`





---





### (Optional) Command
- Monitor router real time log.
```
docker logs --follow --tail 100 router
```


- Check the status.
```
docker-compose ps 
OR 
docker ps -a
```

- Restart Docker
```
docker-compose restart
```

- Stop and delete containers.

```
docker-compose down
```




