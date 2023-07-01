---
title: Getting Help with Commands
---

Pygeoweaver offers a convenient function called `helpwith` that allows you to retrieve help information for specific commands. This function invokes the Geoweaver command-line interface (CLI) to provide detailed guidance on command usage. Let's explore how to use it:

### Syntax

The `helpwith` function takes a list of command arguments as input:

```python
helpwith(command_list)
```

- `command_list` (optional): A list of command arguments to retrieve help information for.

### Usage

To retrieve help information for a specific command, you can pass the command and its arguments as a list to the `helpwith` function. Here's an example:

```python
helpwith(["export", "workflow"])
```

This will display the help information for the `export workflow` command, explaining its usage, available options, and required parameters.

If you want to obtain help for a command with multiple arguments, provide each argument as a separate item in the command list. For example:

```python
helpwith(["add", "process"])
```

This will show the help information for the `add process` command.

If no specific command is provided, running `helpwith()` without any arguments will display general help information about the available commands in Pygeoweaver.

Note: The `helpwith` function relies on the Geoweaver CLI and requires the Geoweaver JAR file and Java binaries to be properly configured in your environment.

By utilizing the `helpwith` function, you can easily access comprehensive guidance on command usage within Pygeoweaver, assisting you in utilizing the available functionality effectively.