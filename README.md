# filepublisher 
## get publisher
git clone https://github.com/CSDCFund/filepublisher.git

## create an account and config file
publisher -i -n

## add account to server
this should be done by administor manually

## run bin version
check file publisher config.json replace.txt

check host attribute in config.json

create keystore and import to config publisher -n -i

use pm2 to daemon process pm2 start ./publisher --name filepublisher sleep 3s pm2 save

memo Do remember to add account to the manager
