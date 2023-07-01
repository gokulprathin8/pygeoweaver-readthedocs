---
title: Retrieving Detailed Information
---

The Pygeoweaver package provides convenient functions to retrieve detailed information about workflows, processes, and hosts. These functions allow you to obtain specific details and configurations related to these components. Let's explore how to use them effectively:

### Detail Workflow

To retrieve detailed information about a workflow, use the `detail_workflow` function. Simply provide the workflow ID as a parameter. Here's an example:

```python
detail_workflow("workflow123")
```

This function will display comprehensive information about the specified workflow.

### Detail Process

If you need to gather detailed information about a process, the `detail_process` function is what you need. Pass the process ID as a parameter to retrieve the details. Take a look at this example:

```python
detail_process("process123")
```

The function will retrieve and display extensive information about the specified process.

### Detail Host

To obtain detailed information about a host, you can utilize the `detail_host` function. Provide the host ID as a parameter to retrieve the information. Here's an example:

```python
detail_host("host123")
```

The function will retrieve and display detailed information about the specified host.

### Get Process Code

If you want to retrieve the code of a specific process, you can use the `get_process_code` function. Provide the process ID as a parameter, and the function will return the code of the process. Here's an example:

```python
code = get_process_code("process123")
print(code)
```

This function will retrieve the code of the specified process and print it for you.

These functions make it easy to retrieve detailed information about workflows, processes, and hosts in Pygeoweaver. Use them to enhance your understanding and management of geospatial processing tasks within Pygeoweaver.