---
title: View Hosts, Processes & Workflow
---

Pygeoweaver provides various functions to list geospatial resources such as hosts, processes, workflows, and processes within a workflow. These functions allow you to retrieve information about the available resources for your geospatial data processing tasks. Here are the details of each function:

### List Hosts

#### `list_hosts()`

This function retrieves a list of available hosts in Geoweaver.

Usage:
```python
list_hosts()
```

By calling the `list_hosts()` function, you can obtain information about the hosts configured in Geoweaver. This information includes host names, addresses, and other relevant details.

### List Processes

#### `list_processes()`

This function retrieves a list of available processes in Geoweaver.

Usage:
```python
list_processes()
```

When you use the `list_processes()` function, you can retrieve information about the processes registered in Geoweaver. This information includes process names, descriptions, and other relevant details.

### List Processes in a Workflow

#### `list_processes_in_workflow(workflow_id)`

This function retrieves a list of processes within a specific workflow in Geoweaver.

Usage:
```python
list_processes_in_workflow(workflow_id)
```

- `workflow_id`: The ID of the target workflow.

By calling `list_processes_in_workflow(workflow_id)`, you can obtain a list of processes contained within the specified workflow. The information includes process titles and IDs.

### List Workflows

#### `list_workflows()`

This function retrieves a list of available workflows in Geoweaver.

Usage:
```python
list_workflows()
```

When you utilize the `list_workflows()` function, you can retrieve information about the workflows stored in Geoweaver. This information includes workflow names, descriptions, and other relevant details.

By leveraging these functions, you can easily explore and access the available hosts, processes, workflows, and processes within workflows in Geoweaver. This enables you to effectively manage and utilize the geospatial resources for your data processing needs.