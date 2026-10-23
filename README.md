# Azuredemo
Azure Demo practice

Microsoft lab exercise link - https://microsoftlearning.github.io/Configure-secure-access-to-workloads-with-Azure-virtual-networking-services/

goto exercise 2 - 

Launch cloudshell from the Azure portal

**Step1 - **
enter the following commands
   $RGName = "RG1"

**Step 2 ******
# to create VNET and Subnet (Hub and Spoke)
   New-AzResourceGroupDeployment -ResourceGroupName $RGName -TemplateUri https://raw.githubusercontent.com/AnandSundaresan2112/Azuredemo/main/create-vnet-subnets-template.json

# to create the VMs
   New-AzResourceGroupDeployment -ResourceGroupName $RGName -TemplateUri https://raw.githubusercontent.com/AnandSundaresan2112/Azuredemo/Lab2.json
