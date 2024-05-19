# BLOG COMING SOON!

#########################################################################################
Automation Scope:-
#####################
1. Validate RG and Keyvault.
2. Choice in the pipeline to create feed on Org level or Project Level.
3. Based on either choice, the pipleine stores feed ID in Key Vault.

Create Feed on Org: POST https://feeds.dev.azure.com/{organization}/_apis/packaging/feeds?api-version=7.1-preview.1
Create Feed on Project: POST https://feeds.dev.azure.com/{organization}/{project}/_apis/packaging/feeds?api-version=7.1-preview.1

#########################################################################################
