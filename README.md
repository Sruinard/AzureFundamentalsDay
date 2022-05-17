# AzureFundamentalsDay

This repository contains some basic demo's for showcasing the capabilities of Azure.

# Azure VM with Application Gateway + VNET

Archicture:

Create Ubuntu 20.04 vm in the portal (create Application Gateway during that process as well)
navigate to

```
chmod 400 </insert/path/to/key/>
ssh -i path/to/pemfile.pem azureuser@ipadress

sudo apt-get update
sudo apt-get install apache2

curl http://localhost:80

cd /var/www/html
sudo vim index.html --> change "It works" --> "Default page modified by team X"

sudo apt remove apache2


```

### Show budgets, alerting, cost analysis

### Azure Functions deploy from portal and deploy using VSCode extensions

### Generate traffic and showcase application insights' live metrics

```
ssh -i path/to/pemfile.pem azureuser@ipadress
sudo apt-get install apache2-utils

ab -n 1000 -c 100 <insert function endpoint>

ab -n 10000 -c 100 <insert function endpoint>
```
