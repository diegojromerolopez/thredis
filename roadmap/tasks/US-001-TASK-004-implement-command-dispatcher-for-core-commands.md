# Task: Implement command dispatcher for core commands

- **ID**: `US-001-TASK-004`
- **Story ID**: `US-001`
- **Status**: `PENDING`
- **Change Type**: `FEATURE`
- **Depends On**: `US-001-TASK-002`
- **Target Files**: `src/Thredis/Commands/ICommandDispatcher.cs`, `src/Thredis/Commands/CommandDispatcher.cs`, `tests/Thredis.Tests/CommandTests.cs`

## Description

Implement the CommandDispatcher to route RESP frames to command handlers. Implement handlers for PING, ECHO, and QUIT commands. Validate command arity and handle unknown commands. Write unit tests in CommandTests.cs to verify command execution and error messages.
