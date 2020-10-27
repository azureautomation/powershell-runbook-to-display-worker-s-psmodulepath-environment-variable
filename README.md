PowerShell Runbook to Display Worker's PSModulePath Environment Variable
========================================================================

            
Description

This simple Azure Automation PowerShell runbook displays all the folders listed in the PSModulePath enviornment variable on the worker that executed the runbook. This can be helpful when using Azure Automation hybrid workers and require manually deploy custom
 PowerShell modules or Integration Modules to hybrid workers. This runbook can help to identify a suitable destination for the manually deployed modules.

Requirements

This runbook does not use any external systems, Automation Assets, or any other runbooks.

Runbook Content

The content is listed below:


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
