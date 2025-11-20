# VM STEPS

* Compute Engine
* Region: us-central1-c
* Machine type: E2 (e2-small)
* OS: Ubuntu (will set to 10GB)
### * Firewall 
* Create Firewall rule
* Name: mysql-connection
* Description: Allow mysql port
* Targets: All instances 
* IPv4 ranges: 0.0.0.0/0 (this allows ingress

* SSH: Terminal->Install
```bash
 sudo apt-get update
```
```bash
sudo apt install mysql.server mysql-client -y
```
 
