---
title: create_workflow
---

#### `create_workflow(description, edges, name, nodes, owner="111111", confidential=False)`

Function to create a workflow with the given data if valid.

**Parameters:**

- `description` (str): The description of the workflow.
- `edges` (str): The edges of the workflow.
- `name` (str): The name of the workflow.
- `nodes` (str): The nodes of the workflow.
- `owner` (str, optional): The owner of the workflow. Defaults to "111111".
- `confidential` (bool, optional): The confidentiality status of the workflow. Defaults to False.

**Returns:**

- `dict`: Returns the ID of the created workflow.

Note: All the functions mentioned above internally call the `download_geoweaver_jar()` function and make API requests to the GeoWeaver application for creating processes and workflows. They return the ID of the created process or workflow if successful. If the code is executed in an IPython environment, the functions also return a pandas DataFrame containing the key-value pairs of the data sent to the API.
