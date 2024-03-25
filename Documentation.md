# Documentation Data
Last Updated Date: February 15th, 2024

# Summary
Below are the large number of Links that have been used in this deployment. Many are redundant, but it would take forever to clean that up.

They are broken up by the general topic in question with sub-categories.


# Azure

[Azure Naming Abbreviations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)

[Creating Custom Roles](https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles)

[Role breakdown for Start/Stop of VMs](https://stackoverflow.com/questions/23668154/allow-users-to-start-stop-particular-azure-vms/49925159)

[Azure Monitor Basics](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings?WT.mc_id=Portal-Microsoft_Azure_Monitoring)

[Azure VM Hibernation](https://learn.microsoft.com/en-us/azure/virtual-machines/hibernate-resume?tabs=osLimitsWindows%2CenablehiberPortal%2CcheckhiberPortal%2CenableWithPortal%2CcliLHE%2CUbuntu18HST%2CPortalDoHiber%2CPortalStatCheck%2CPortalStartHiber%2CPortalImageGallery)

### Powershell Usage

[Install / Update Azure Module for Powershell](https://learn.microsoft.com/en-us/powershell/azure/install-azps-windows?view=azps-11.3.0&tabs=powershell&pivots=windows-psgallery)

### Powershell Modules


# Azure Compute

[Creating an Azure Batch pool w/ Ephemeral Disks](https://learn.microsoft.com/en-us/azure/batch/create-pool-ephemeral-os-disk)

[Writeup on why Ephemeral Disks](https://insights.gocloudforce.com/en/optimize-azure-wvd-costs-with-ephemeral-os-disks)

### Powershell Modules
[Create VM w/ Accelerated Networking](https://learn.microsoft.com/en-us/azure/virtual-network/create-vm-accelerated-networking-powershell)

[Update-AzVM](https://learn.microsoft.com/en-us/powershell/module/az.compute/update-azvm?view=azps-11.2.0)

[New-AzNetworkInterface](https://learn.microsoft.com/en-us/powershell/module/az.network/new-aznetworkinterface?view=azps-11.2.0)

[New-AzDiskupdateConfig](https://learn.microsoft.com/en-us/powershell/module/az.compute/new-azdiskupdateconfig?view=azps-11.2.0)

[New-AzDiskConfig](https://learn.microsoft.com/en-us/powershell/module/az.compute/new-azdiskconfig?view=azps-11.2.0)

[Update-AzDisk](https://learn.microsoft.com/en-us/powershell/module/az.compute/update-azdisk?view=azps-11.2.0)


# Azure Resource Manager

[MSFT ARM Template for Session Host Creation](https://github.com/Azure/RDS-Templates/tree/master/ARM-wvd-templates/AddVirtualMachinesToHostPool)

[SAS Token for ARM Templates in Storage Container](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/secure-template-with-sas-token?tabs=azure-powershell)

[Use Keyvaults for Sensitive Data in Template]Key vaults and SAS in Datafactory](https://blog.nillsf.com/index.php/2020/09/03/using-key-vault-managed-storage-accounts-and-sas-tokens-in-azure-data-factory/)

[Create Template Spec Portal Forms](https://github.com/MicrosoftDocs/azure-docs/blob/main/articles/azure-resource-manager/templates/template-specs-create-portal-forms.md)

[About Template Specs](https://dev.to/omiossec/azure-template-specs-1h42)

[Add Tags to ARM Template Deployments](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources-templates)

[Store SAS token in Keyvault](https://woivre.com/blog/2020/01/generate-storage-accounts-sas-keys-using-keyvault)

### Powershell Usage

[Deploy Remote Templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-powershell#deploy-remote-template)

[Create linked templates w/ PowerShell](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs-deploy-linked-template?tabs=azure-powershell)

[Using Template Specs w/ Powershell](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs?tabs=azure-powershell)

[Quick Bit on Version Type Increments](https://stackoverflow.com/questions/30195025/increment-version-in-a-text-file)

### Powershell Modules

[Set-AzTemplateSpec](https://learn.microsoft.com/en-us/powershell/module/az.resources/set-aztemplatespec?view=azps-11.2.0)

[Get-AzTemplateSpec](https://learn.microsoft.com/en-us/powershell/module/az.resources/get-aztemplatespec?view=azps-11.2.0)

[New-AzTemplateSpec](https://learn.microsoft.com/en-us/powershell/module/az.resources/new-aztemplatespec?view=azps-11.2.0)




# Azure Imaging

### Setup and Capture
[Gold Image Setup for AvD](https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-golden-image)

[Issue w/ Accelerated Networking in Images](https://learn.microsoft.com/en-us/answers/questions/1394462/isacceleratednetworksupported-in-null-on-input-gal)

[Generalizing VM before Capture](https://learn.microsoft.com/en-us/azure/virtual-machines/generalize)

[Adjust MS Office Update Channel](https://learn.microsoft.com/en-us/deployoffice/office-deployment-tool-configuration-options#channel-attribute-part-of-updates-element)

[Manage the Windows Component Store](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/manage-the-component-store?view=windows-11)

[Cleaning upd WinSXS](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/clean-up-the-winsxs-folder?view=windows-11)

[Create an image definition and an image version]

### Optimization

[MS Official Virtual Desktop Optimization Tool](https://github.com/The-Virtual-Desktop-Team/Virtual-Desktop-Optimization-Tool)


[Writup on Optimization Tool](https://christiaanbrinkhoff.com/2020/07/31/optimize-your-windows-10-single-and-multi-session-images-with-the-new-windows-virtual-desktop-optimization-tool/)

[Optimize Windows AvD](https://aeccloud.com/blog/optimizing-performance-in-windows-virtual-desktop-best-practices)

[Disk Performance Tool - No Install](https://the-sz.com/products/parkdale/)

[Optimize Window10 2004 for AvD](https://learn.microsoft.com/en-us/windows-server/remote/remote-desktop-services/rds-vdi-recommendations-2004)

[Export Default App Associations](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/export-or-import-default-application-associations?view=windows-11)

### Powershell Modules

[New-AzImage](https://learn.microsoft.com/en-us/powershell/module/az.compute/new-azimage?view=azps-11.2.0)

[New-AzGalleryImageVersion](https://learn.microsoft.com/en-us/powershell/module/az.compute/new-azgalleryimageversion?view=azps-11.2.0)





# Azure Virtual Desktop

[CAP for Entra MFA](https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-mfa)

[Analyze AvD Connection Latency](https://learn.microsoft.com/en-us/azure/virtual-desktop/connection-latency#connection-graphics-data-preview)

### Security
[Zero Trust for Virtual Machines](https://learn.microsoft.com/en-us/security/zero-trust/azure-infrastructure-virtual-machines#logical-architecture-for-virtual-machines)

### AppAttach

[Publishing](https://learn.microsoft.com/en-us/azure/virtual-desktop/publish-applications-stream-remoteapp?tabs=portal)

[App Attach Setup](https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-setup?tabs=portal&pivots=app-attach)

[Overview](https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-overview?pivots=app-attach#permissions)

### Deployment

[Resource Org for AvD Deployment](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/wvd/eslz-resource-organization)

[Enterprise-scale support for Microsoft Azure Virtual Desktop](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/wvd/enterprise-scale-landing-zone)

[Network topology](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/wvd/eslz-network-topology-and-connectivity)

[Add session hosts to a pool](https://learn.microsoft.com/en-us/azure/virtual-desktop/add-session-hosts-host-pool?tabs=portal%2Cgui)

### Powershell Usage

[Using Powershell to get Hostpool Registration Keys](https://www.nielskok.tech/azure-virtual-desktop/wvd-hostpool-registration-key/)

### Powershell Modules

[Get-AzWVDUserSession](https://learn.microsoft.com/en-us/powershell/module/az.desktopvirtualization/get-azwvdusersession?view=azps-11.2.0)

[Get-AzWVDHostPool](https://learn.microsoft.com/en-us/powershell/module/az.desktopvirtualization/get-azwvdhostpool?view=azps-11.2.0)

[Get-AzWVDSessionHost](https://learn.microsoft.com/en-us/powershell/module/az.desktopvirtualization/get-azwvdsessionhost?view=azps-11.2.0)

[Get-AzWvdRegistrationInfo](https://learn.microsoft.com/en-us/powershell/module/az.desktopvirtualization/get-azwvdregistrationinfo?view=azps-11.2.0)





# Azure Automate

[Managed Identity for Azure Automation Account](https://learn.microsoft.com/en-us/azure/automation/enable-managed-identity-for-automation)

[Configure Parameters to make Runbooks Modular](https://learn.microsoft.com/en-us/azure/automation/runbook-input-parameters)

[PSWorkflow vs PSCode](https://learn.microsoft.com/en-us/azure/automation/automation-powershell-workflow)

[Source Control Integration w/ GitHub](https://learn.microsoft.com/en-us/azure/automation/source-control-integration#prerequisites)

[Troubleshooting: 403 inside Runbook accessing Storage Blob](https://learn.microsoft.com/en-us/answers/questions/1294600/azure-blob-storage-unauthorized-403-while-access-f)

[Create modular runbooks](https://learn.microsoft.com/en-us/azure/automation/automation-child-runbooks)

[Runbook Execution Process](https://learn.microsoft.com/en-us/azure/automation/automation-runbook-execution)

[Troublshooting Hybrid Worker](https://learn.microsoft.com/en-us/azure/automation/troubleshoot/extension-based-hybrid-runbook-worker)

[Run in Hybrid Worker](https://learn.microsoft.com/en-us/azure/automation/automation-hrw-run-runbooks?tabs=win-extn-hrw%2CLin-extn-hrw%2Csa-mi)

[Deallocate at logoff](https://avdpunks.com/avd/2023/01/12/AVDxDeallocateSessionHosts.html)

### Powershell Usage

[Configure Hybrid Benefits](https://jimmyk.azurewebsites.net/2020/03/21/enable-hybrid-benefit-on-all-already-deployed-windows-vms-in-your-subscription/)

[Temp Storage inside Automation Runbook](https://learn.microsoft.com/en-us/answers/questions/1007777/temp-location-to-download-blob-and-update-the-blob)

### Powershell Modules

[New-AzAutomationSourceControl](https://learn.microsoft.com/en-us/powershell/module/az.automation/new-azautomationsourcecontrol?view=azps-11.3.0)

[Set-AzAutomationSCNode](https://learn.microsoft.com/en-us/powershell/module/az.automation/set-azautomationdscnode?view=azps-11.3.0)

[Set-AzAutomationRunbook](https://learn.microsoft.com/en-us/powershell/module/az.automation/set-azautomationrunbook?view=azps-11.3.0)





# Azure Storage

### Powershell Usage

[Creating Storage SAS Permissions](https://learn.microsoft.com/en-us/rest/api/storageservices/create-service-sas#permissions-for-a-directory-container-or-blob)

[Storage Account Security](https://learn.microsoft.com/en-us/azure/storage/common/storage-network-security?tabs=azure-powershell#exceptions)

### Powershell Modules

[Get-AzStorageStorageContainer](https://learn.microsoft.com/en-us/powershell/module/az.storage/get-azstoragecontainer?view=azps-11.3.0)

[Get-AzStorageStorageBlob](https://learn.microsoft.com/en-us/powershell/module/az.storage/get-azstorageblob?view=azps-11.2.0)

[Get-AzStorageStorageContext](https://learn.microsoft.com/en-us/powershell/module/az.storage/new-azstoragecontext?view=azps-11.3.0)

[Get-AzStorageBlobContent](https://learn.microsoft.com/en-us/powershell/module/az.storage/get-azstorageblobcontent?view=azps-11.2.0)

[Get-AzStorageBlobSASToken](https://learn.microsoft.com/en-us/powershell/module/az.storage/new-azstorageblobsastoken?view=azps-11.2.0)





# Azure NetApp Files

[SMB Performance w/ SMB3](https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-smb-performance#smb-encryption)

[Configuring Kerberos](https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-kerberos-encryption)

[Service Level Breakdown](https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-service-levels)

[Networking for Netapp Fiels](https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies)

[Perf/Cost Sizer for Netapp Files](https://bluexp.netapp.com/azure-netapp-files/sizer)

[Dynamic Volume Service Levels](https://docs.netapp.com/us-en/netapp-solutions/ai/aks-anf_azure_netapp_files_performance_tiers.html#dynamically-change-the-service-level-of-a-volume)

[Check Netapp Files Metrics](https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-metrics#volumes)


# UberAgent

### Installation

### License Updates
    Update/Replace the uberagent.lic file here:
    C:\Program Files\vast limits\uberAgent