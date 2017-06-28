# HumbleNet

## What exactly is HumbleNet?
   
HumbleNet is a simple C API that wraps WebRTC and WebSockets and hides away all
the platform differences between browser and non-browser platforms. The current
version of the library exposes a simple peer-to-peer API that allows for basic
peer discovery and the ability to easily send data (via WebRTC) to other peers.
In this manner, you can build a game that runs on Linux, macOS, and Windows,
while using any web browser — and they can all communicate in real-time via WebRTC.
This means no central server (except for peer discovery) is needed to handle network
traffic for the game. The peers can talk directly to each other.

## Building from scratch

Instructions coming soon for all platforms. 

## Contributing

Please look at our [TODO](https://github.com/HumbleNet/humblenet/blob/master/TODO.md) list as well as the [CONTRIBUTING](https://github.com/HumbleNet/humblenet/blob/master/CONTRIBUTING.md) guide.

## Downloads

Prebuilt binary releases will be available soon at the [github releases](https://github.com/HumbleNet/humblenet/releases) page.
