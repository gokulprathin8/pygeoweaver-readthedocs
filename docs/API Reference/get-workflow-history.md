---
title: get_workflow_history
---

#### `get_workflow_history(workflow_id)`

Function to retrieve the list of history entries for a workflow using the workflow ID.

**Parameters:**

- `workflow_id` (str): The ID of the workflow to retrieve the history for.

**Returns:**

- `DataFrame`: A pandas DataFrame containing the workflow history information.

**Notes:**

- This function sends a POST request to the GeoWeaver API endpoint to retrieve the workflow history.
- The response is converted to a pandas DataFrame for easier data manipulation and analysis.
- The DataFrame includes columns for the history begin time and end time, converted to datetime format.