# HF_custom

# Install 
1. nvm install v8 
2. npm install -g composer-cli@0.19  
3. npm install -g composer-rest-server@0.19
4. npm install -g generator-hyperledger-composer@0.19

# Start Fabric network
1. cd hyperledger/hyperledger-fabric
2. ./2_startFabric.sh

# Start Composer
1. cd hyperledger/hyperledger-composer
2. ./run.sh

# Start Webserver 
1. cd app/bin
2. ./db.sh
3. ./www
