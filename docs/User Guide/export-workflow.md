---
title: Exporting Workflows
---

Pygeoweaver offers a convenient function, `export_workflow`, to export workflows in various modes. This allows you to save workflows and their associated components for sharing or archiving purposes. Let's explore how to use this function effectively:

### Export Workflow

To export a workflow, use the `export_workflow` function. Specify the workflow ID and provide a target file path where the exported workflow will be saved. Here's an example:

```python
export_workflow("workflow123", target_file_path="path/to/exported/workflow.zip")
```

By default, the function exports the workflow with all its history and process code. However, you can customize the export mode using the `mode` parameter. The available options are:

- Mode 1: Export workflow only
- Mode 2: Export workflow with process code
- Mode 3: Export workflow with process code and only good history
- Mode 4 (default): Export workflow with process code and all history

For example, to export only the workflow without process code or history, you can use:

```python
export_workflow("workflow123", mode=1, target_file_path="path/to/exported/workflow.zip")
```

### Unzip Exported Workflow

If you want to unzip the exported workflow, you can set the `unzip` parameter to `True`. Additionally, provide a unique name for the directory where the contents will be extracted using the `unzip_directory_name` parameter. Here's an example:

```python
export_workflow(
    "workflow123",
    target_file_path="path/to/exported/workflow.zip",
    unzip=True,
    unzip_directory_name="unzipped_workflow"
)
```

This will extract the exported workflow into the specified directory, allowing you to access its contents.

Note: Please ensure you have the necessary permissions and appropriate directory paths before executing the export and unzip operations.

The `export_workflow` function in Pygeoweaver simplifies the process of exporting workflows, enabling you to share, archive, or backup your geospatial processing workflows effortlessly.