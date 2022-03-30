primitives
8
u8
16
u16
32
u32
64
u64
boolean: u8 0 false 1 true

array8: u8 byte length plus data of u8 length
array16:
array32:

array8string: u8 byte length utf8 string
array16string
array32string




Request/Response

Request sha256(location) -> Response (array32)



Streams

ReadStream

Request (u32 size) -> Response (data[uint size])

WriteStream

Request (u32 size, data[uint size]) -> Response (none? error handling?)

ReadWriteStream

mode: 
u8 mode
0: read
u32 size
1: write
u32 size
data

todo write rust lib and client/server example
