# People Quest Protocol

[![hackmd-github-sync-badge](https://hackmd.io/Nn3mwkKLQ5m04nowsKhMug/badge)](https://hackmd.io/Nn3mwkKLQ5m04nowsKhMug)

Authors:
- Hlib Kanunnikov(@Wondertan)

## Overview
This document describes the People Quest Protocol. The protocol aims to reimagine the way people find new valuable connections. In a simple list, it tells the whole protocol flow:
- How any person/user lists all his interest tags.
- How devices passively scan for other peers through Bluetooth(BLE).
- Defines secure networking(handshakes, connection establishment/keep-alive, messaging).
- Defines private message exchange format.
- Specs out the way devices understand whenever the peers are interested in connecting to each other(matching).

## Motivation
// TODO: Consider moving this as overall Nobis thesis.
- Social networking needs to be revisited to match Web3 principles. Almost every person in developed and developing countries nowadays has a device in everyday 
usage to informationally stay connected to the whole world and their tribes through the Internet or specifically Web2.0. The Web2.0 has been serving us well, but
through time, known drawbacks, which can be ignored at the beginning of the development, have to be fixed, or they will become a source of performance losses, 
security breaches, etc., as with any technology out there. Luckily, recent days show lots of effort from enthusiasts worldwide, aiming to improve the current state
of the Web, known as Web3.0. Most of the ongoing work in this sphere focuses on innovations(Blockchains) and core infrastructure(IPFS) for the new Web. At the same
time, there are plenty of existing Web2.0 applications that need to be migrated or reimagined to support Web3.0 core principles efficiently, like social
networking. Here we can observe lower interest, even though the field is essential for humanity. Fortunately, some projects are pushing the goal forward, like
Berty. Still, it is reasonable to support the effort furthermore, and this document describes one of the core pieces and foundation for Web3.0 social networking.
//TODO: Add references to projects and to Web2.0 drawbacks.

- New "cool", appealing and non-tech but Web3 based features has to be introduced, otherwise masses won't migrate to Web3 stack applications. Creating Web3 mirrors
of exisisting applications with same feature set won't bring interest for people of different spectrum, as they mostly don't care about inner mechanics of how 
any app works and how it uses their data. Web2, in contrast with Web1.0, brought to us new dynamic kind of applications with new features never known before what 
subsequently provided enourmous interest to the Internet. Web3 on the other hand treats each user with more respect to owned data, bandwidth usage, information 
integrity and overall user rights, while preserving dinamicity. Still, besides providing secure and trustless asset management through Blockchain, those Web3 
qualities haven't brought deserved popularization and new breakthrough user friendly Web3 applications have to arise to accelerate adoption. Nobis here aims for 
maximum decentralization of social networking to provide solution for which regular centralized application technically won't scale. Similarly how Web2.0 provided us with more usecases comparing to Web1.0. PQP, as Nobis core prorocol, allows people to met each other and understand whenever they are interested in
communication on the fly. Use of regular Web2 tech would require coordination of GPS, multiple ISP up to central server over the ocean and finally costy data
processing on that server. Unfortunately, overall latancy of such a tech would never allow two humans to match when passing by each other, while in p2p environment this would work flawlessly.

- 


## Goals
- Offline first(Does not rely on WAN in the first place)
- Scaleable(Works in crowded places with ~100 peers around)
- Instant(Matching operation succeds for two peers running in opposite directions)
- Simple UX

## The Protocol

