---
title: Custom Transports
permalink: /wiki/custom-transports/
---

The MLAPI supports custom transports. It uses UNET by default. You can also write custom transports. A transport is the library that is responsible for sending the raw bytes and handle connections.

Usually, transports doesn't support support all channel types and event types. Sometimes they have more, in that case you manually have to do translation between them. See the ENET transport for examples.

To get started writing transport interfaces, the current implementations for Unet and ENET are great starting points for learning their flow. If you do write a transport for a well known transport, feel free to open a PR to add it to the default supported.
