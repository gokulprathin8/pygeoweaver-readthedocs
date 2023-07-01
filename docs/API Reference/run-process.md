---
title: run_process
---
#### `run_process(*, process_id: str, host_id: str, password: str = None, environment: str = None, sync_path: PathLike = None)`

Function to run a GeoWeaver process.

**Parameters:**

- `process_id` (str): The ID of the process to run.
- `host_id` (str): The ID of the host on which to run the process.
- `password` (str, optional): The password for the host. If not provided, a prompt will ask for it.
- `environment` (str, optional): The environment to run the process in.
- `sync_path` (PathLike, optional): The path to the file to sync with the workflow code.

**Raises:**

- `Exception`: If the specified sync path does not exist.
- `Exception`: If the workflow ID mismatch occurs.

