# Azuredemo
Azure Demo practice

Microsoft lab exercise link - https://microsoftlearning.github.io/Configure-secure-access-to-workloads-with-Azure-virtual-networking-services/

goto exercise 2 - 

   $RGName = "RG1"
   
   New-AzResourceGroupDeployment -ResourceGroupName $RGName -TemplateUri https://raw.githubusercontent.com/MicrosoftLearning/Configure-secure-access-to-workloads-with-Azure-virtual-networking-services/main/Instructions/Labs/azuredeploy.json
