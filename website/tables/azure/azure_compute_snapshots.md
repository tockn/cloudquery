# Table: azure_compute_snapshots

This table shows data for Azure Compute Snapshots.

https://learn.microsoft.com/en-us/rest/api/compute/snapshots/list?tabs=HTTP#snapshot

The primary key for this table is **id**.

## Columns

| Name          | Type          |
| ------------- | ------------- |
|_cq_source_name|String|
|_cq_sync_time|Timestamp|
|_cq_id|UUID|
|_cq_parent_id|UUID|
|subscription_id|String|
|location|String|
|extended_location|JSON|
|properties|JSON|
|sku|JSON|
|tags|JSON|
|id (PK)|String|
|managed_by|String|
|name|String|
|type|String|