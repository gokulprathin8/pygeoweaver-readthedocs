---
title: Running Processes and Workflows
---

Pygeoweaver provides functions to run processes and workflows in Geoweaver. These functions allow you to execute specific processes or entire workflows on designated hosts. Here are the details of the functions:

### Running a Process

#### `run_process()`

This function runs a specific process on a designated host.

Usage:
```python
run_process(
    process_id: str,
    host_id: str,
    password: str = None,
    environment: str = None,
    sync_path: os.PathLike = None
)
```

- `process_id`: The ID of the process to run (required).
- `host_id`: The ID of the host on which to run the process (required).
- `password`: The password for the host (optional). If not provided, you will be prompted to enter the password securely.
- `environment`: The environment in which to run the process (optional).
- `sync_path`: The path to a file to update the code for the workflow (optional).

The `run_process()` function downloads the Geoweaver JAR file and executes the specified process on the designated host. If a `sync_path` is provided, the code for the workflow will be updated with the contents of the specified file.

### Running a Workflow

#### `run_workflow()`

This function runs an entire workflow or a specific workflow folder on designated hosts.

Usage:
```python
run_workflow(
    workflow_id: str,
    workflow_folder_path: str = None,
    workflow_zip_file_path: str = None,
    environment_list: str = None,
    host_list: str = None,
    password_list: str = None,
    sync_path: os.PathLike = None
)
```

- `workflow_id`: The ID of the workflow to run.
- `workflow_folder_path`: The path to the workflow folder (optional).
- `workflow_zip_file_path`: The path to the workflow zip file (optional).
- `environment_list`: A comma-separated list of environment IDs on which to run the workflow (optional).
- `host_list`: A comma-separated list of host IDs on which to run the workflow (optional).
- `password_list`: A comma-separated list of passwords for the target hosts (optional). If not provided, you will be prompted to enter the passwords securely.
- `sync_path`: The path to a file to sync with the workflow (optional).

The `run_workflow()` function downloads the Geoweaver JAR file and executes the specified workflow on the designated hosts. You can provide the workflow ID, the workflow folder path, or the workflow zip file path. If a `sync_path` is provided, the workflow will be synchronized with the contents of the specified file.

Ensure that you have the necessary dependencies set up, including the Geoweaver JAR file and Java, before using these functions.

Use the `run_process()` and `run_workflow()` functions to execute processes and workflows in Geoweaver with ease.