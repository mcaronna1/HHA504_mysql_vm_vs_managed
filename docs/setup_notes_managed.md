Azure
* All server -> databases -> Azure SQL Database -> Azure data for mysql flexible server
* Flex server: Quick Create
* Database Name: Testtesttest
* Region: West US 2
* Administrator log in: dba
* Password:
* Workload Details: Dev/Test
* Side bar- click- add firewall rule for IP address - be sure to use a public IP
* Review create

* In Shell, type in
``` bash
mysql -u dba -h testtesttest.mysql.database.azure.com -p
```
Enter in anyname you want to name your database:

```bash
create database caronna;
```
```bash
use caronna;
```
```bash
show database;
```
