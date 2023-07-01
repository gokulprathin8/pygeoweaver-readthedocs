---
title: Creating Processes and Workflows
---

The Pygeoweaver library provides functionalities to create processes and workflows for geospatial data processing and analysis. This section explains how to use the `create_process`, `create_process_from_file`, and `create_workflow` functions to create processes and workflows in Pygeoweaver.

### Creating a Process

#### Function Signature

```python
def create_process(lang, description, name, code, owner="111111", confidential=False):
    ...
```

#### Parameters

- `lang` (str): The programming language of the process. Currently, *python* & *shell* are supported.
- `description` (str): The description of the process.
- `name` (str): The name of the process.
- `code` (str): The code of the process.
- `owner` (str, optional): The owner of the process. Defaults to "111111".
- `confidential` (bool, optional): The confidentiality status of the process. Defaults to False.

#### Return Value

- Returns the ID of the created process as a dictionary.

#### Description

The `create_process` function creates a process in Pygeoweaver with the provided data. It takes the programming language, description, name, code, owner, and confidentiality status as input. The function sends a POST request to the GeoWeaver API to create the process.

### Creating a Process from a File

#### Function Signature

```python
def create_process_from_file(lang, description, name, file_path, owner="111111", confidential=False):
    ...
```

#### Parameters

- `lang` (str): The programming language of the process.
- `description` (str): The description of the process.
- `name` (str): The name of the process.
- `file_path` (str): The path to the file containing the code.
- `owner` (str, optional): The owner of the process. Defaults to "111111".
- `confidential` (bool, optional): The confidentiality status of the process. Defaults to False.

#### Return Value

- Returns the ID of the created process as a dictionary.

#### Description

The `create_process_from_file` function creates a process in Pygeoweaver using the code from a file. It takes the programming language, description, name, file path, owner, and confidentiality status as input. The function reads the code from the specified file and calls the `create_process` function with the obtained code.

### Creating a Workflow

#### Function Signature

```python
def create_workflow(description, edges, name, nodes, owner="111111", confidential=False):
    ...
```

#### Parameters

- `description` (str): The description of the workflow.
- `edges` (str): The edges of the workflow.
- `name` (str): The name of the workflow.
- `nodes` (str): The nodes of the workflow.
- `owner` (str, optional): The owner of the workflow. Defaults to "111111".
- `confidential` (bool, optional): The confidentiality status of the workflow. Defaults to False.

#### Return Value

- Returns the ID of the created workflow as a dictionary.

#### Description

The `create_workflow` function creates a workflow in Pygeoweaver with the provided data. It takes the description, edges, name, nodes, owner, and confidentiality status as input. The function sends a POST request to the GeoWeaver API to create the workflow.

---

With these functions, you can easily create processes and workflows in Pygeoweaver for geospatial data processing. You can provide the necessary information, such as the programming language, description, code or file path, and structure of the workflow.