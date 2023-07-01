---
title: get_process_by_id
---

#### `get_process_by_id(process_id)`

Function to retrieve a process by its ID from GeoWeaver.

**Parameters:**

- `process_id` (str): The ID of the process to retrieve.

**Notes:**

- This function sends a POST request to the GeoWeaver API to retrieve the list of processes.
- It filters the processes by matching the `process_id` parameter.
- The function displays the matching process in a pandas DataFrame with all columns visible.
