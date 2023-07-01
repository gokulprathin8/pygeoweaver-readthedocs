---
title: get_process_by_name
---

#### `get_process_by_name(process_name)`

Function to retrieve processes by name from GeoWeaver.

**Parameters:**

- `process_name` (str): The name of the process to search for.

**Notes:**

- This function sends a POST request to the GeoWeaver API to retrieve the list of processes.
- It filters the processes by matching the `process_name` parameter.
- The function displays the matching processes in a pandas DataFrame with all columns visible.

