# AzureForge sample application

A deliberately tiny public repository that plays the **customer** in AzureForge M2 onboarding
acceptance. It contains no secrets and no production code.

Its protected GitHub environments (`production-plan`, `production-apply`, `production-deploy`)
are trusted by three customer Azure identities, each limited to its own role in one customer
resource group. Workflows here prove those identities cannot act outside their approved scopes.
