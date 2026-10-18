# Task: Implement RESP frame models and encoder

- **ID**: `US-001-TASK-002`
- **Story ID**: `US-001`
- **Status**: `PENDING`
- **Change Type**: `FEATURE`
- **Depends On**: `US-001-TASK-001`
- **Target Files**: `src/Thredis/Protocol/RespType.cs`, `src/Thredis/Protocol/RespFrame.cs`, `src/Thredis/Protocol/IRespEncoder.cs`, `src/Thredis/Protocol/RespEncoder.cs`, `tests/Thredis.Tests/ProtocolTests.cs`

## Description

Define the RespType enumeration and the RespFrame model. Implement the RespEncoder to serialize RESP frames into an IBufferWriter. Write unit tests in ProtocolTests.cs to verify the byte-level wire formatting for all RESP types.
