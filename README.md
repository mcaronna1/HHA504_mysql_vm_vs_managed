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

# Start to finish elapsed time: 3 hours 

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

  # Start to Finish Elapsed Time Measured in Azure 1 hour

  # Issues:

When working out of Visual Studio Code and wanting to run my URL patterns iut came up with an error. I created screenshots of my connection string patterns to show how they did not fully go through.

  # Loom video links:
  
  https://www.loom.com/share/82e642957e354399aa3d155acfe65a95

  https://www.loom.com/share/d7b7f394e3154c94b7bdfce872509972



  

  

 




  
