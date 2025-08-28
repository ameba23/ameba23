
My interests:

## Peer-to-peer

Why I love peer-to-peer: 
 - Put ourselves in control
 - Reduce dependence on commercial infrastructure
 - Reduce energy use

In my spare time i maintain [harddrive-party](https://github.com/ameba23/harddrive-party)

I am particularly interested in peer discovery and NAT traversal.

## Confidential computing 

If you must use servers, make it possible for people to audit what is running on the server - through client attestation and reproducible builds. 

I think people are getting tired of using services with opaque server-side code with data extraction and other funny business. Trusted execution environments pave the way for new kinds of 'transparent services' where clients get genuine guarantees about how their data is used.

Confidential computing crates i authored:
 - [`tdx-quote`](https://docs.rs/tdx-quote) - Parse and verify TDX quotes
 - [`configfs-tsm`](https://docs.rs/configfs-tsm) - Generate quotes for remote attestation on confidential computing platforms using Linux's configfs-tsm filesystem interface

##  Social backup / recovery 

Rely on a small group of people you trust to secure your identity online.

For several years i worked on [darkcrystal.pw](https://darkcrystal.pw/) - a protocol framework for social recovery with implementations in Rust, Java, and Javascript. I worked on a social recovery feature for the privacy-focussed messaging app, [Briar](https://briarproject.org).

## Cryptography for groups / group management / group moderation

Client-side signing and encryption is very empowering for individual users. But its even more empowering for groups. Im interested group threshold signing and group encryption schemes, particularly how to manage group members joining and leaving dynamically.

At [entropy](https://entropy.xyz) i have been working on a threshold signing platform using [synedrion](https://docs.rs/synedrion).

I also worked on [Cobox](https://cobox.cloud) - a distributed filesystem which allows organizations to mutually provide encrypted backups for each other.

