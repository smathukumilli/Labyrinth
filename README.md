# Labyrinth

one way of deploying resources is to 

New-AzResourceGroupDeployment -Name MyARMDeployment -ResourceGroupName ADFResourceGroup -TemplateFile C:\ADF\ADFARM.json -TemplateParameterFile C:\ADF\ADFparameters.json

OR Automated Build or CI with Azure Devops

POST https://{instance}/{collection}/{project}/_apis/build/builds?api-version=5.0


