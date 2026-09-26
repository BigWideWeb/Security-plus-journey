# Module: Network Fundamentals — TryHackMe Pre Security

Covered the basics of how networking works. From LANs up through the OSI model and how data actually gets encapsulated and moved.

## What I learned

- **What is networking:** at its core, it's just computers exchanging data. The "how" is what the rest of this module builds out (protocols, addressing, physical connections).
- **Intro to LAN:** a Local Area Network is a group of devices connected within a small area (home, office) that can communicate directly with each other, usually through a switch or router.
- **OSI model:** the 7-layer conceptual model for how network communication happens, from physical cabling (Layer 1) up to the actual application (Layer 7). Each layer only talks to the ones directly above/below it. And what this actually means is, troubleshooting network issues usually means figuring out *which layer* the problem is actually at.
- **Packets and frames:** data gets broken into **packets** at the network layer (Layer 3) and wrapped into **frames** at the data link layer (Layer 2) before it physically travels. Each layer adds its own header info (encapsulation) — like nesting envelopes inside envelopes.
- **Extending your network:** devices like switches, routers, access points, and repeaters each extends or manages a network differently (switches connect devices within a LAN, routers connect networks to each other, repeaters just boost signal range).

## What confused me

Packets vs. frames was the trickiest part for me. They sound interchangeable but aren't. What helped: packets are the Layer 3 (network layer) unit, frames are the Layer 2 (data link) unit — a packet gets wrapped inside a frame for its actual journey across the physical network, then unwrapped again on arrival.

## Mystery Gift

My gift was a streak freeze.


