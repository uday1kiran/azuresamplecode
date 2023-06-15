## To login azure cli
az login
## to set default subscription
az account set --subscription "Visual Studio Professional Subscription"

## to deploy template

az deployment group create \
--resource-group dummy \
--template-file template.json \
--parameters storageAccounts_zuscutaastd1shared=studay1
