---
'@backstage/plugin-scaffolder-backend-module-bitbucket-cloud': patch
---

Fix Bitbucket merge checks handling by updating types to accept null (as strings) and adjusting default values to prevent 400 errors from the API.
