# v1.0.0 (07/31/2023)

Initial release

# v1.0.1 (10/09/2023)

## Bug Fixes
* Runs in Terraform Cloud that produce multiple State Versions (due to a bug or outdated version of Terraform Enterprise) will no longer cause provisioning to fail. The Engine now fetches and inspects each State Version to find the most recent version, and uses that version to parse the `output` values.
