https://www.w3schools.com/whatis/

### upgrade node js to latest version:

https://stackoverflow.com/questions/10075990/upgrading-node-js-to-latest-version

The module n makes version-management easy:

``` bash
sudo npm install n -g

For the latest stable version:

sudo n stable

For the latest version:

sudo n latest
```



### install yarn:

``` bash
sudo npm install -g yarn
```

change package.json since node version here is 14.17.5 : 

 "engines": {
    "node": "14.17.5",


### install mongodb  

https://stackoverflow.com/questions/63980239/mongodb-in-ubuntu-20-04-problems

https://stackoverflow.com/questions/48092353/failed-to-start-mongod-service-unit-mongod-service-not-found/48871898#48871898

https://docs.mongodb.com/manual/reference/installation-ubuntu-community-troubleshooting/

first remove old ones:

``` bash
sudo apt remove mongodb-org mongodb-org-tools
sudo apt remove mongo-tools

sudo apt remove mongodb
sudo apt purge mongodb
sudo apt autoremove
```

then follow:  
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/


### ensure mongodb is running 

``` bash
sudo systemctl restart mongod
mongo
```

### run project

``` bash
#then in project folder:
cd project_folder
yarn
yarn development
```


### deploy

https://www.freecodecamp.org/news/deploying-a-mern-application-using-mongodb-atlas-to-heroku/














