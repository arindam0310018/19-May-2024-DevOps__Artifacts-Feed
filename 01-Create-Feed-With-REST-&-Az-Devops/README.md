# BLOG COMING SOON!

| __Automation Scope__ | 
| --------- |

| __#__ | __Scope__ |
| --------- |:---------:| 
| 1. | Validate RG and Keyvault. | 
| 2. | Choice in the pipeline to create feed on Org level or Project Level. | 
| 3. | Based on either choice, the pipleine stores feed ID in Key Vault. | 


| __IMPORTANT TO NOTE:-__ | 
| --------- |
| __Create Feed on Org:__ POST https://feeds.dev.azure.com/{organization}/_apis/packaging/feeds?api-version=7.1-preview.1 |
| __Create Feed on Project:__ POST https://feeds.dev.azure.com/{organization}/{project}/_apis/packaging/feeds?api-version=7.1-preview.1 |

