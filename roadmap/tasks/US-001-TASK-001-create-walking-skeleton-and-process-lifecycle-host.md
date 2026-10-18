# Task: Create walking skeleton and process lifecycle host

- **ID**: `US-001-TASK-001`
- **Story ID**: `US-001`
- **Status**: `PENDING`
- **Change Type**: `FEATURE`
- **Depends On**: `[]` 
- **Target Files**: `Thredis.sln`, `Makefile`, `src/Thredis/Thredis.csproj`, `src/Thredis/Program.cs`, `src/Thredis/Common/IClock.cs`, `src/Thredis/Common/SystemClock.cs`, `src/Thredis/Server/IServerHost.cs`, `src/Thredis/Server/ServerHost.cs`, `tests/Thredis.Tests/Thredis.Tests.csproj`, `tests/Thredis.Tests/IntegrationTests.cs`

## Description

Create the .NET 9 solution and project files. Write the Makefile with build, run, test, lint, and clean targets. Implement the thin Program.cs entrypoint. Implement ServerHost to manage the process lifecycle, read the PORT environment variable, and handle SIGINT and SIGTERM signals. Write a basic integration test to verify that the host starts and stops correctly.
