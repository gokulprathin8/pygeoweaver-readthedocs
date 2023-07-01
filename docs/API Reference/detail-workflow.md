---
title: detail_workflow
---

#### `detail_workflow(workflow_id)`

Function to retrieve detailed information about a workflow.

**Parameters:**

- `workflow_id` (str): The ID of the workflow.

**Raises:**

- `RuntimeError`: If the workflow ID is missing.

**Notes:**

- This function internally calls the `download_geoweaver_jar()` function and executes a subprocess to retrieve the detailed information about the specified workflow using the GeoWeaver application.

