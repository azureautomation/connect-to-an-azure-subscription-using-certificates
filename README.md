Connect to an Azure Subscription using Certificates
===================================================

            

**Description**


This PowerShell Workflow runbook sets up a connection to an Azure subscription by placing the Azure management certificate into the local machine store and setting the connection to the subscription.


WARNING: This runbook is deprecated, although it will continue to work going forward. Please use OrgID credential auth to connect to Azure, instead of certificate auth using this runbook.  You can learn more about
 using credential auth with Azure here:http://aka.ms/Sspv1l


**Requirements**


Before running this runbook, make sure the following components are available:


  *  Automation Certificate Asset containing the management certificate loaded to Azure

  *  Automation Connection Asset containing the subscription id and the name of the certificate setting in Automation Assets


**Runbook Contents**


The runbook's contents are displayed below:


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
