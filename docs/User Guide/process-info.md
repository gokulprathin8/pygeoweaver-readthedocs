---
title: Retrieving Process Information
---

Pygeoweaver provides several functions to retrieve process information based on different criteria. These functions allow you to search for processes by name, ID, or programming language. Let's explore each function in detail:

### Get Process by Name

To retrieve processes by their names, you can use the `get_process_by_name` function. This function takes a process name as input and returns a DataFrame containing matching processes. Here's an example:

```python
get_process_by_name("my_process")
```

This will fetch all processes with the name "my_process" and display them in a tabular format.

### Get Process by ID

If you know the process ID and want to retrieve the corresponding process information, you can use the `get_process_by_id` function. Provide the process ID as input, and the function will return a DataFrame with the matching process details. Here's an example:

```python
get_process_by_id("process123")
```

This will retrieve the process with the ID "process123" and display its information in a tabular format.

### Get Process by Language

If you are interested in processes written in a specific programming language, you can use the `get_process_by_language` function. Specify the language as input, and the function will return a DataFrame with the matching processes. For example:

```python
get_process_by_language("Python")
```

This will retrieve all processes written in Python and display their information in a tabular format.

Note: The above functions rely on making requests to the Geoweaver API to retrieve process information. Ensure that the Geoweaver server is accessible and running for successful retrieval.

By utilizing these process retrieval functions, you can easily obtain relevant information about processes based on their names, IDs, or programming languages.