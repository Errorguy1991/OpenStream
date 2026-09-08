# OpenStream Protocol

The protocol separates:

1. Control
2. Video
3. Audio
4. Input
5. Telemetry

Video and audio are optimized for low latency.

Old media packets must not block newer media.

Input is prioritized because interactive response is more
important than retransmitting obsolete video.

Telemetry includes:

- RTT
- jitter
- packet loss
- bandwidth
- encoder latency
- decoder latency
- render latency
- FPS

The host dynamically adjusts streaming parameters according
to measured conditions.
