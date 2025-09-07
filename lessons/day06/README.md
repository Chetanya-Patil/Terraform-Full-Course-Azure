## Task for Day06

### Using the files from previous task(day05), divide the entire folder structure into seperate files such as
- backend.tf
- provider.tf
- resource-group.tf
- storage-account.tf
- local.tf
- variables.tf
- terraform.tfvars
- output.tf


#### Here, files are executed in alphabetical order but some file will be gives us error due to dependency. So to maintain that dependency we have Implicit dependency & Explicit dependency available.

Implicit dependency: In this process the property of previous task will be used in next task to maintain that depedency.

Explicit dependency: We have syntax to maintain this dependency.
depends_on = [ azure_resource_group.example ]
