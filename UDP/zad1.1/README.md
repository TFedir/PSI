## Task 1.1
The client sends and the server receives datagrams of a fixed, small size (on the order of tens of bytes). Datagrams can contain a fixed or generated text - e.g. "abcde....", "bcdef...", etc. Several datagrams should be sent, after which the client should terminate. The server once started runs until the process is killed. The server outputs to stdout the address of the client sending the datagram.