---
title: helpwith
---

#### `helpwith(command_list: list = [])`

Function to display help information for a specific command or subcommand in GeoWeaver.

**Parameters:**

- `command_list` (list): A list of strings representing the command and subcommands to retrieve help information for. Defaults to an empty list.

**Notes:**

- This function constructs a command to execute using the `get_java_bin_path` and `get_geoweaver_jar_path` functions.
- If the `command_list` is provided, it appends the command and subcommands to the target command.
- The constructed command runs the GeoWeaver JAR file with the `help` argument and the specified command and subcommands.
- The function displays the help information in the console.

