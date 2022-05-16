# Implementation of Stream that work with WebSockets

## wsio

- `wsio.FromWebSocket(r fio.ReadWriter, side ws.State, chunkSize int) stream.Stream[[]byte]`
- `wsio.WriteByteChunks(writer fio.ReadWriter, side ws.State, chunkSize int) stream.Sink[[]byte`
