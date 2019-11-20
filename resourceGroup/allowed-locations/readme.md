CLI Commands
 
1. Create Policy 

az policy definition create --name "Policy Name" --rules "azurepolicy.parameters.json" --params "allowedLocations"

2. Create Policy Assignment 

Valid Scopes - mgmt group, subscription, resource manager, resource

az policy assignment create --scope "scope" --policy "policyname" -p "paramefile"