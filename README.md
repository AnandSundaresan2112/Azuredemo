# Azuredemo
Azure Demo practice

Microsoft lab exercise link - https://microsoftlearning.github.io/Configure-secure-access-to-workloads-with-Azure-virtual-networking-services/

goto exercise 2 - 

Launch cloudshell from the Azure portal
enter the following commands
   $RGName = "RG1"
   
   New-AzResourceGroupDeployment -ResourceGroupName $RGName -TemplateUri https://raw.githubusercontent.com/AnandSundaresan2112/Azuredemo/main/create-vnet-subnets-template.json
