# azure-gallery-templates
Azure Gallery Templates downloaded with Get-AzureResourceGroupGalleryTemplate on the 30-08-2015

You can download them with 
```powershell
Get-AzureResourceGroupGalleryTemplate -Publisher "Microsoft" |% { Save-AzureResourceGroupGalleryTemplate $_.Identity}
```
 
