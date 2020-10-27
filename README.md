Virtual Machine Scheduled Scaling
=================================

            

Resizing a specific Resource Group Azure VM according to a schedule using Azure Automation. Autoscaling based on a schedule allows you to scale your solution according to predictable resource demand.


 


.EXAMPLE
-resourceGroupName myResourceGroup
-virtualMachineName myVirtualMachineName
-virtualMachineSize myVirtualMachineSize
-azureRunAsConnectionName AzureRunAsConnection 
-scalingSchedule [{WeekDays:[1, 2, 3, 4, 5]]
-scalingScheduleTimeZone Central Europe Standard Time
-requestUrl https://google.com


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
