# Personal Project Portfolio

This repository serves as a log of ongoing and planned projects, each focused on deepening knowledge in system-level programming, distributed systems, and application development.

## Projects Overview

### Completed Projects

1. **[Widyanaya API](https://github.com/dosedaf/widyanaya-api)**
   - **Description**: A RESTful API designed to manage and serve data efficiently, with structured endpoints for various resources.
   - **Features**:
     - Implements standard CRUD operations.
     - Secure authentication and authorization.
     - Data validation and structured error handling.
   - **Technologies**: Go, PostgreSQL, Docker.

2. **[PERPUSTAKON](https://github.com/dosedaf/PERPUSTAKON)**
   - **Description**: A library management system API for handling book inventory, member records, and borrowing transactions.
   - **Features**:
     - Handles book information, member records, and loan tracking.
     - Efficient searching and filtering options.
     - Built with clean code architecture.
   - **Technologies**: Go, PostgreSQL, Docker, Redis.

### Ongoing Projects

1. **[Sireng](https://github.com/dosedaf/sireng)**
   - **Description**: A comprehensive API for tracking study sessions, adding friends, and supporting chat functionality.
   - **Progress**:
     - Implemented JWT-based session management and authentication.
     - Built initial Redis caching and schema validation.
     - **Next Steps**: Integrate AWS S3 for profile photos, complete chat feature.
   - **Technologies**: Go, PostgreSQL, Redis, GoFiber.

2. **[Go Blockchain](https://github..com/dosedaf/goblock)**
   - **Description**: Implementing a blockchain from scratch using Go. This project involves creating a distributed ledger with cryptographic hashing, block validation, and an optional consensus mechanism.
   - **Progress**:
     - Created block structure and linked list.
     - Added block validation and hashing mechanism.
     - **Next Steps**: Implement Proof-of-Work and simple P2P networking for block synchronization.
   - **Technologies**: Go, Networking.

### Planned Projects

1. **Binary Utility (Binutil)**
   - **Description**: Developing a custom `binutil` tool for low-level file operations. This will explore binary manipulation, file parsing, and potentially disassembly.
   - **Goals**:
     - Build a hex dump utility to display binary file content.
     - Implement patching capabilities to modify specific bytes.
     - Experiment with file format parsing, such as ELF or PE headers.
   - **Technologies**: Go, Binary File Parsing.

2. **File Upload Service**
   - **Description**: Creating a scalable file upload service with functionality for handling large files, multipart uploads, and basic authentication.
   - **Goals**:
     - Build secure file upload endpoints.
     - Implement chunking and resume capabilities.
     - Design the service for scalability and storage optimization.
   - **Technologies**: Go, S3-Compatible Storage.

3. **Distributed Task Queue System**
   - **Description**: Implementing a distributed task queue in Go to handle background tasks asynchronously. This will involve concurrency, message queuing, and task distribution.
   - **Goals**:
     - Set up a message broker (e.g., Redis, RabbitMQ) for task management.
     - Implement a producer/consumer model with task prioritization.
     - Add monitoring, retry handling, and metrics for task tracking.
   - **Technologies**: Go, Redis/RabbitMQ.

---

## Next Steps

- Finalize blockchain Proof-of-Work and peer-to-peer networking.
- Begin binary utility (binutil) development, starting with a hex dump and progressing to binary patching.
- Prioritize file upload service and distributed task queue as next concurrent projects.

This README will be updated as projects progress and new goals are defined.
