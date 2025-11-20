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
```bash
sudo apt install nano
```
```bash
sudo mysql
```
Type in terminal
```bash
show databases;
```
# Create new user (In terminal)

* Create user 'caronna' @ '%' identified by 'caronna2025';
* Enter
* Enter in
   ```bash
   select * from mysql.user;
   ```
  To format
  *press arrow up
  ``` bash
  select * from mysql.user;\G
  ```
  This will give a cleaner lay-out of your data

  Next: to give access to all in SSH:

  ```bash
  grant all privileges on *.* to 'caronna' @ '%" with grant option;
  ```
  ```bash
  select * from mysql.user where user like
  'caronna';
  after add \G to do a check
  
  

 
