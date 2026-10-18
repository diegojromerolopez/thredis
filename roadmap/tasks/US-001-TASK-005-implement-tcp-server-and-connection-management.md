# Task: Implement TCP server and connection management

- **ID**: `US-001-TASK-005`
- **Story ID**: `US-001`
- **Status**: `PENDING`
- **Change Type**: `FEATURE`
- **Depends On**: `US-001-TASK-003`, `US-001-TASK-004`
- **Target Files**: `src/Thredis/Server/TcpServer.cs`, `src/Thredis/Server/ClientConnection.cs`, `src/Thredis/Server/ServerHost.cs`, `tests/Thredis.Tests/IntegrationTests.cs`

## Description

Implement the TcpServer to accept TCP connections on the configured port. Implement ClientConnection to manage the asynchronous PipeReader and PipeWriter loop. Connect the decoder, dispatcher, and encoder. Update ServerHost to start the TcpServer. Write socket integration tests in IntegrationTests.cs to verify live TCP communication.
