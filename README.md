# 1. Install nvm For this run below command in your terminal
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash

# 2. Install specific node version using nvm
Replace 12.14.1 with your node version
nvm install 12.14.1

Note: If you are getting error of NVM not recognised then run below command and then run above again
source ~/.nvm/nvm.sh

# 3. Make the installed version default
Note: Replace 12.14.1 with your installed version.
nvm alias default 12.14.1

and 

nvm use 12.14.1

# 4. Check node version

node -v
