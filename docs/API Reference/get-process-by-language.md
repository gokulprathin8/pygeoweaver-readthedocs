---
title: get_process_by_language
---

#### `get_process_by_language(language)`

Function to retrieve processes by programming language from GeoWeaver.

**Parameters:**

- `language` (str): The programming language of the processes to search for.

**Notes:**

- This function sends a POST request to the GeoWeaver API to retrieve the list of processes.
- It filters the processes by matching the `language` parameter.
- The function displays the matching processes in a pandas DataFrame with all columns visible.

