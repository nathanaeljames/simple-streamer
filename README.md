# simple-streamer
A bare-bones JavaScript frontend for streaming audio from web browser to server using websockets.

Many of the existing audio streaming demos out there in 2021 are either outdated and/ or have a ton of "extra" features which raise the barrier to getting started with websockets and audio streaming. I created this "bare bones" script which reduces the audio streaming down to only four key functions:

1. Open websocket
2. Start Streaming
3. Resample audio
4. Stop streaming

Thanks to [vin-ni's Google-Cloud-Speech-Node-Socket-Playground](https://github.com/vin-ni/Google-Cloud-Speech-Node-Socket-Playground) for most of this code. Hopefully this KISS (Keep It Simple, Stupid) demo can help somebody else get started with streaming audio a little faster than it took me. You can test this using most of the Autobahn python echo servers which you can find on [Crossbario's GitHub](https://github.com/crossbario/autobahn-python/tree/master/examples/twisted/websocket/echo). The `startRecording()` and `stopRecording()` functions could also be called from variables in Storyline or H5P, if one wanted to use this for speech recognition in ed tech (like me).
