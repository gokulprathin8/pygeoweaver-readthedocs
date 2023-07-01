---
title: detail_process
---

#### `detail_process(process_id)`

Function to retrieve detailed information about a process.

**Parameters:**

- `process_id` (str): The ID of the process.

**Raises:**

- `RuntimeError`: If the process ID is missing.

**Notes:**

- This function internally calls the `download_geoweaver_jar()` function and executes a subprocess to retrieve the detailed information about the specified process using the GeoWeaver application.

---