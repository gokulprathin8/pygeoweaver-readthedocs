---
title: Viewing History
---

Pygeoweaver provides functions to view the history of workflows and processes, allowing you to track their execution and monitor previous runs. The following functions enable you to access and display the history information:

### Viewing Workflow and Process History

#### `show_history(history_id)`

This function displays the history of a workflow or process based on the provided `history_id`.

Usage:
```python
show_history(history_id)
```

- `history_id`: The ID of the workflow or process history you want to view.

#### `get_process_history(process_id)`

This function retrieves the history of a specific process using the `process_id` parameter. It returns a pandas DataFrame containing detailed information about each historical run.

Usage:
```python
get_process_history(process_id)
```

- `process_id`: The ID of the process for which you want to retrieve the history.

#### `get_workflow_history(workflow_id)`

This function retrieves the history of a workflow identified by the `workflow_id`. It returns a pandas DataFrame containing the history details of each run.

Usage:
```python
get_workflow_history(workflow_id)
```

- `workflow_id`: The ID of the workflow for which you want to retrieve the history.

Note: The history functions require the Geoweaver JAR file and Java binaries to be properly configured in your environment.

By utilizing these functions, you can easily access and analyze the historical execution data of workflows and processes within Pygeoweaver. This allows you to review past runs, track performance, and identify any issues or improvements.