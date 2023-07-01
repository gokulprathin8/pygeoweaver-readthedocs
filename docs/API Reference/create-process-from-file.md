---
title: create_process_from_file
---

#### `create_process_from_file(lang, description, name, file_path, owner="111111", confidential=False)`

Function to create a process with code from a file.

**Parameters:**

- `lang` (str): The programming language of the process.
- `description` (str): The description of the process.
- `name` (str): The name of the process.
- `file_path` (str): The path to the file containing the code.
- `owner` (str, optional): The owner of the process. Defaults to "111111".
- `confidential` (bool, optional): The confidentiality status of the process. Defaults to False.

**Returns:**

- `dict`: Returns the ID of the created process.