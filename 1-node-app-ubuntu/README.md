    1  apt-get update
    2  apt-get install curl -y
    4  curl -sL https://deb.nodesource.com/setup_10.x | bash
    5  apt-get install nodejs -y
    6  cd opt/
    7  mkdir node-app
    8  cd node-app/
    9  echo 'console.log("nodejsapp from ubuntu...");' > index.js
   10  ls
   11  cat index.js 
   12  history