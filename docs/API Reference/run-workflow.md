---
title: run_workflow
---

#### `run_workflow(*, workflow_id: str, workflow_folder_path: str = None, workflow_zip_file_path: str = None, environment_list: str = None, host_list: str = None, password_list: str = None, sync_path: PathLike = None)`

Function to run a GeoWeaver workflow.

**Parameters:**

- `workflow_id` (str): The ID of the workflow to run.
- `workflow_folder_path` (str, optional): The folder path of the workflow.
- `workflow_zip_file_path` (str, optional): The path to the workflow zip file.
- `environment_list` (str, optional): The list of environments to run on, separated by commas.
- `host_list` (str, optional): The list of hosts to run on, separated by commas.
- `password_list` (str, optional): The list of passwords for the target hosts, separated by commas.
- `sync_path` (PathLike, optional): The path to the file to sync with the workflow code.

**Raises:**

- `RuntimeError`: If the password list length doesn't match the host list.
- `RuntimeError`: If at least one of the three options (workflow ID, folder path, or zip path) is not provided.
