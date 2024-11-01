# Personal Project Portfolio

This repository serves as a log of ongoing and planned projects, each focused on deepening knowledge in system-level programming, distributed systems, and application development.

## Projects Overview

### Ongoing Project: Go Blockchain
- **Description**: Implementing a blockchain from scratch using Go. This project involves creating a distributed ledger with cryptographic hashing, block validation, and an optional consensus mechanism.
- **Progress**:
  - Created block structure and linked list.
  - Added block validation and hashing mechanism.
  - **Next Steps**: Implement Proof-of-Work and simple P2P networking for block synchronization.

### Planned Projects

1. **Binary Utility (Binutil)**
   - **Description**: Developing a custom `binutil` tool for low-level file operations. This will explore binary manipulation, file parsing, and potentially disassembly.
   - **Goals**:
     - Build a hex dump utility to display binary file content.
     - Implement patching capabilities to modify specific bytes.
     - Experiment with file format parsing, such as ELF or PE headers.

2. **File Upload Service**
   - **Description**: Creating a scalable file upload service with functionality for handling large files, multipart uploads, and basic authentication.
   - **Goals**:
     - Build secure file upload endpoints.
     - Implement chunking and resume capabilities.
     - Design the service for scalability and storage optimization.

3. **Distributed Task Queue System**
   - **Description**: Implementing a distributed task queue in Go to handle background tasks asynchronously. This will involve concurrency, message queuing, and task distribution.
   - **Goals**:
     - Set up a message broker (e.g., Redis, RabbitMQ) for task management.
     - Implement a producer/consumer model with task prioritization.
     - Add monitoring, retry handling, and metrics for task tracking.

---

## Next Steps

- Finalize blockchain Proof-of-Work and peer-to-peer networking.
- Begin binary utility (binutil) development, starting with a hex dump and progressing to binary patching.
- Prioritize file upload service and distributed task queue as next concurrent projects.

This README will be updated as projects progress and new goals are defined.
