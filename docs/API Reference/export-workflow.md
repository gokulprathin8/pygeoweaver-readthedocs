---
title: export_workflow
---

#### `export_workflow(workflow_id, mode=4, target_file_path=None, unzip=False, unzip_directory_name=None)`

Function to export a workflow from GeoWeaver.

**Parameters:**

- `workflow_id` (str): The ID of the workflow to export.
- `mode` (int): The export mode options:
    - `1` - Export workflow only.
    - `2` - Export workflow with process code.
    - `3` - Export workflow with process code and only good history.
    - `4` - Export workflow with process code and all history. (default mode)
- `target_file_path` (str): The target file path to save the exported workflow ZIP file.
- `unzip` (bool): Flag to specify if the exported workflow should be unzipped. Default is `False`.
- `unzip_directory_name` (str): The name of the directory to extract the unzipped workflow. Required if `unzip` is `True`.

**Raises:**

- `RuntimeError`: If the workflow ID is missing.
- `Exception`: If `unzip` is `True` but `unzip_directory_name` is not provided.

**Notes:**

- This function internally calls the `download_geoweaver_jar()` function and executes a subprocess to export the specified workflow from GeoWeaver.
- The exported workflow is saved as a ZIP file at the specified `target_file_path`.
- If `unzip` is `True`, the exported workflow ZIP file is extracted to the specified `unzip_directory_name` within the same directory.
