# SMTP_Server_Mass_checker
Easy script on python for mass checking authorization on SMTP servers

1. Create combo txt list with SMTP credentials like: login|password|smtp_server|port
2. Put file permissions: chmod +x script.py
3. Run script: python script.py credentials

Script authomatic checking authorization connection with SMTP servers on ports 465/587. 

For example output:

$ python script.py credentials
FAILED: xxxxx@xxxxx:xxxxxxx - SMTP Server: smtp.xxxx.xx - Port: 587
SUCCESS: daudi@pearesgroup.com:Daudi.123 - SMTP Server: pearesgroup.com - Port: 465
