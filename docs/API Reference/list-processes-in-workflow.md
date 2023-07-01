---
title: list_processes_in_workflow
---
#### `list_processes_in_workflow(workflow_id)`

Function to list all processes in a specified workflow.

**Args:**

- `workflow_id` (str): The ID of the workflow.

**Returns:**

- If executed in an IPython environment:
  - `result` (pandas.DataFrame): A DataFrame containing the process titles and IDs in the workflow.
- If executed in a non-IPython environment:
  - `result` (list): A list of dictionaries containing the process titles and IDs in the workflow.

**Raises:**

- `Exception`: If the GeoWeaver JAR file is not found or if the workflow details cannot be retrieved.

