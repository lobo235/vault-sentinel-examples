# vault-sentinel-examples
# Examples of some Sentinel policies for HashiCorp Vault
## custom_metadata_validation
This Sentinel Policy shows an example of doing some validation of values in the custom_metadata field of KV2 metadata. It has a regex matching example as well as a value-in-list example.
## metadata_expire_date
This Sentinel Policy shows an example of limiting access to create/update/delete only 1 custom_metadata field called "expire_date". Any create/update/delete operations requested for any other custom_metadata fields will be denied.