---
title: detail_host
---

#### `detail_host(host_id)`

Function to retrieve detailed information about a host.

**Parameters:**

- `host_id` (str): The ID of the host.

**Raises:**

- `RuntimeError`: If the host ID is missing.

**Notes:**

- This function internally calls the `download_geoweaver_jar()` function and executes a subprocess to retrieve the detailed information about the specified host using the GeoWeaver application.
