---
title: sync_workflow
---


#### `sync_workflow(workflow_id: str, sync_to_path: Union[str, PathLike])`

Function to synchronize the workflow and its code between the local file system and the GeoWeaver workflow.

**Parameters:**

- `workflow_id` (str): The ID of the workflow to synchronize.
- `sync_to_path` (Union[str, PathLike]): The local path where the workflow should be synchronized.

**Raises:**

- `Exception`: If the workflow ID mismatch occurs.

