---
title: import_workflow
---

#### `import_workflow(workflow_zip_file_path)`

Function to import a workflow from a zip file.

**Parameters:**

- `workflow_zip_file_path` (str): The file path to the Geoweaver workflow zip file.

**Notes:**

- This function downloads the GeoWeaver JAR file using the `download_geoweaver_jar` function.
- It executes the GeoWeaver JAR file with the `import` argument, `workflow` sub-command, and the specified `workflow_zip_file_path`.
- The function runs the command in the directory specified by the `get_root_dir` function.