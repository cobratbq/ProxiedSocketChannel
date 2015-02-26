# ProxiedSocketChannel
A Java SocketChannel implementation that uses a provided Proxy instance to set up a network connection via provided proxy. The SocketChannel is implemented with a Socket instance under the surface.

## Limitations
This implementation currently supports only blocking mode. Note that this is the default behaviour for SocketChannel instances, so unless a project explicitly switches to non-blocking mode, this implementation may already be sufficient for your purpose.
