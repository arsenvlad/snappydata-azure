# SnappyData on Azure
Automated SnappyData deployment on Microsoft Azure Cloud

# Deploy via the Azure portal UI
<a href="https%3A%2F%2Fraw.githubusercontent.com%2Farsenvlad%2Fsnappydata-azure%2Fmaster%2FmainTemplate.json">
<img src="https://camo.githubusercontent.com/9285dd3998997a0835869065bb15e5d500475034/687474703a2f2f617a7572656465706c6f792e6e65742f6465706c6f79627574746f6e2e706e67" data-canonical-src="http://azuredeploy.net/deploybutton.png" style="max-width:100%;">
</a>

# Deploy using Azure CLI
```
azure account login
```
```
azure account set "My Subscription"
```
```
azure group list
```
```
azure group create --name avsnappydata1 --location westus
```
```
azure group deployment create --resource-group avsnappydata1 --name mainTemplate --template-file mainTemplate.json
```