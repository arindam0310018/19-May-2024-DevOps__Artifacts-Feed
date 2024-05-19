# BLOG COMING SOON!

| __Automation Scope__ | 
| --------- |

| __#__ | __Scope__ |
| --------- |:---------:| 
| 1. | Validate RG and Keyvault. | 
| 2. | Choice in the pipeline to Temporary or Permanently delete feed on Org level. | 
| 3. | Based on either choice, the pipleine stores feed ID in Key Vault. | 
| 4. | If feed is deleted temporarily from Org Level, it exists in Recycle Bin marked for Permanent deletion. Feed ID still exists in Key Vault. |
| 5. | If feed is deleted Permanently from Org Level, it is deleted from Recycle Bin as well. Also, Feed ID is no more in Key Vault. |
| 6. If feed is deleted temporarily from Project Level, it exists in Recycle Bin marked for Permanent deletion. Feed ID still exists in Key Vault. |
| 7. If feed is deleted Permanently from Project Level, it is deleted from Recycle Bin as well. Also, Feed ID is no more in Key Vault. |

| __IMPORTANT TO NOTE:-__ | 
| --------- |
| __Delete from Org:__ DELETE https://feeds.dev.azure.com/{organization}/_apis/packaging/feeds/{feedId}?api-version=7.1-preview.1 |
| __Delete from Org Recycle Bin:__ DELETE https://feeds.dev.azure.com/{organization}/_apis/packaging/feeds/{feedId}?api-version=7.1-preview.1 |
| __Delete from Project:__ DELETE https://feeds.dev.azure.com/{organization}/{project}/_apis/packaging/feedrecyclebin/{feedId}?api-version=7.1-preview.1 |
| __Delete from Project Recycle Bin:__ DELETE https://feeds.dev.azure.com/{organization}/{project}/_apis/packaging/feeds/{feedId}?api-version=7.1-preview.1 |
