CST8918-W25-A11.
Prof. Robert McKenney
Student: Catherine Daigle - 41175118

# Lab A11: Remote state storage with Azure Blob Storage



az storage account create \
--name 41175118tfstorage \
--resource-group daig0104-cst8918-tf-backend \
--location westus3 --sku Standard_LRS


az storage container create --name tfstate --account-name 41175118tfstorage

