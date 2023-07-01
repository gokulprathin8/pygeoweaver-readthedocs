---
title: PyGeoWeaver Internals
---

PyGeoWeaver is built using Python and leverages various libraries and frameworks to provide its functionality. This section provides an overview of the internal components and architecture of PyGeoWeaver.

## Core Components

### 1. Geoweaver JAR

PyGeoWeaver relies on the Geoweaver JAR file, which is a Java-based tool that provides the underlying functionality for managing workflows and processes. The Geoweaver JAR file is responsible for executing commands and interacting with the Geoweaver server.

### 2. REST API

PyGeoWeaver communicates with the Geoweaver server through a RESTful API. This API allows PyGeoWeaver to perform operations such as listing workflows and processes, executing workflows and processes, retrieving details, and managing workflow history.

### 3. HTTP Requests

To interact with the Geoweaver server, PyGeoWeaver utilizes the `requests` library, which provides a convenient way to send HTTP requests and handle responses. PyGeoWeaver uses the `requests` library to send requests to the Geoweaver server's REST API endpoints.

### 4. Command-Line Interface (CLI)

PyGeoWeaver includes a command-line interface that allows users to interact with the library from the terminal. The CLI provides a set of commands for performing operations such as listing workflows, executing processes, exporting workflows, and retrieving workflow history.

### 5. Function Library

The core functionality of PyGeoWeaver is implemented through a set of Python functions. These functions wrap the Geoweaver API endpoints and provide a higher-level interface for users to interact with Geoweaver. The function library handles tasks such as sending requests to the server, parsing responses, and providing convenient abstractions for common operations.

## Extensibility and Customization

PyGeoWeaver can be extended and customized to fit specific use cases. Users can build upon the library's existing functionality by creating wrappers or additional functions that cater to their specific requirements. Additionally, PyGeoWeaver supports configuration customization to adapt to different Geoweaver server setups and environments.

Understanding the internals of PyGeoWeaver provides insights into how the library interacts with the Geoweaver server and how it implements its functionality. This knowledge can be helpful for extending the library, troubleshooting issues, and exploring advanced use cases.