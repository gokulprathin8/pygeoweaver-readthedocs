---
title: get_process_history
---

#### `get_process_history(process_id)`

Function to retrieve the list of history entries for a process using the process ID.

**Parameters:**

- `process_id` (str): The ID of the process to retrieve the history for.

**Returns:**

- `DataFrame`: A pandas DataFrame containing the process history information.

**Notes:**

- This function downloads the GeoWeaver JAR file using the `download_geoweaver_jar` function.
- It sends a POST request to the GeoWeaver API endpoint to retrieve the process history.
- The response is converted to a pandas DataFrame for easier data manipulation and analysis.
- The DataFrame includes columns for the history begin time and end time, converted to datetime format.
