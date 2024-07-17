# function-bicep
```
az group create --name rg-temptemptemp --location japaneast

az deployment group create \
    --resource-group rg-temptemptemp \
    --template-file main.bicep \
    --parameters functionAppName=func-temptemptemp storageAccountName=sttemptemptemp
```