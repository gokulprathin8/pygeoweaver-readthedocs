---
title: sync
---

#### `sync(process_id: str, local_path: Union[str, PathLike], direction: str)`

Function to synchronize the code between the local file system and the GeoWeaver process.

**Parameters:**

- `process_id` (str): The ID of the process to synchronize.
- `local_path` (Union[str, PathLike]): The local path to sync the code.
- `direction` (str): The direction of synchronization. Valid options: "upload" or "download".

**Raises:**

- `Exception`: If the sync path is not found.
- `Exception`: If an unknown file format is encountered.


