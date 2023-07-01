---
title: Import a existing workflow
---

With Pygeoweaver, you can import workflows from existing files using the `import_workflow` function. This allows you to easily bring in workflows saved as zip files. Here's how you can use this function:

### Importing a Workflow

#### `import_workflow(workflow_zip_file_path)`

This function imports a workflow from a zip file specified by the `workflow_zip_file_path`.

Usage:
```python
import_workflow(workflow_zip_file_path)
```

- `workflow_zip_file_path`: The file path to the Geoweaver workflow zip file.

Note: Before using this function, ensure that you have downloaded the Geoweaver JAR file and configured the Java binaries in your environment.

By utilizing the `import_workflow` function, you can seamlessly import workflows into Pygeoweaver, allowing you to work with existing workflows and leverage their functionality for your geospatial data processing tasks.
