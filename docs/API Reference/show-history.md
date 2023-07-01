---
title: show_history
---

#### `show_history(history_id)`

Function to display the history of a workflow or process.

**Parameters:**

- `history_id` (str): The ID of the history to retrieve.

**Notes:**

- This function downloads the GeoWeaver JAR file using the `download_geoweaver_jar` function.
- It executes the GeoWeaver JAR file with the `history` argument and the specified `history_id`.
- The function runs the command in the directory specified by the `get_root_dir` function.
- The function displays the history information in the console.