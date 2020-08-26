## Learning Objective

Applications will oftentimes need access to API keys, database passwords, TLS private keys, and other types of secrets.
Storing these secrets side by side with application code is not recommended for both security and sharing across components.
Using a centralized secret store with granular access controls, such as Azure Key Vault, is a better approach.

You can use the Azure PowerShell module to create Key Vaults, and store and retrieve individual secrets.

## Learning Points

* The `Az` PowerShell module is included in PowerShell projects