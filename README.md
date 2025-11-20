# HHA504_mysql_vm_vs_managed
mysql_vm_vs_managed
# VM Cloud
## * GCP
* Compute Engine
* Region: us-central1-c
* Machine type: E2 (e2-small)
* OS: Ubuntu (will set to 10GB)
### * Firewall 
* Create Firewall rule
* Name: mysql-connection
* Description: Allow mysql port
* Targets: All instances 
* IPv4 ranges: 0.0.0.0/0 (this allows ingress)

# Managed Serivce Cloud

*Azure
* All server -> databases -> Azure SQL Database -> Azure data for mysql flexible server
* Flex server: Quick Create
* Database Name: Testtesttest
* Region: West US 2
* Administrator log in: dba
* Password:
* Workload Details: Dev/Test
* Side bar- click- add firewall rule for IP address - be sure to use a public IP

  ALWAYS REMEMEBER TO DELETE RESOURCES AS YOU ARE GETTING CHARGED

  *scripts/vm_demo.py and scripts/managed_demo.py that (you can just copy and paste the provided files, and or modify them as you like):

* Read credentials from environment (.env)
* Connect to MySQL via SQLAlchemy
* Create a new database (e.g., dummydb) if not exists
* Create a table (e.g., visits) via pandas to_sql
* Insert 5–10 rows from a pandas DataFrame
* Read back with pd.read_sql and print row count

  
