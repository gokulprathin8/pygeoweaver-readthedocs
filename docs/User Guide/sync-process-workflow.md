---
title: Synchronizing Processes and Workflows
---

Pygeoweaver provides functions to synchronize processes and workflows in Geoweaver. These functions allow you to download process code, upload modified code, and sync entire workflows. Here are the details of the functions:

### Synchronizing a Process

#### `sync()`

This function syncs the code of a specific process.

Usage:
```python
sync(process_id: str, local_path: str, direction: str)
```

- `process_id`: The ID of the process to sync.
- `local_path`: The local path where the code will be synced.
- `direction`: The direction of the sync. Choices are "upload" or "download".

The `sync()` function allows you to either download the code of a process to a local path or upload modified code to the process. If the direction is set to "download", the code of the process will be retrieved and saved to the specified local path. If the direction is set to "upload", the code from the specified local path will be uploaded to the process.

### Synchronizing a Workflow

#### `sync_workflow()`

This function syncs an entire workflow, including its code and history.

Usage:
```python
sync_workflow(workflow_id: str, sync_to_path: str)
```

- `workflow_id`: The ID of the workflow to sync.
- `sync_to_path`: The path to the workflow where the code and history will be synced.

The `sync_workflow()` function downloads the specified workflow, extracts it, and checks if the target workflow path matches the extracted workflow. If they match, the function replaces the files in the target workflow with the downloaded files, effectively syncing the code and history. Ensure that the `sync_to_path` matches the workflow you want to sync.

Make sure you have the necessary dependencies set up, including the Geoweaver JAR file and Java, before using these functions.

Use the `sync()` and `sync_workflow()` functions to synchronize processes and workflows in Geoweaver conveniently.