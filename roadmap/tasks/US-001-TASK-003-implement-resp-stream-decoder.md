# Task: Implement RESP stream decoder

- **ID**: `US-001-TASK-003`
- **Story ID**: `US-001`
- **Status**: `PENDING`
- **Change Type**: `FEATURE`
- **Depends On**: `US-001-TASK-002`
- **Target Files**: `src/Thredis/Protocol/IRespDecoder.cs`, `src/Thredis/Protocol/RespDecoder.cs`, `tests/Thredis.Tests/ProtocolTests.cs`

## Description

Implement the RespDecoder to parse a ReadOnlySequence of bytes into RespFrame objects. Support chunked streams, inline commands, and pipelined commands. Write unit tests in ProtocolTests.cs to verify partial frame decoding and pipelining.
