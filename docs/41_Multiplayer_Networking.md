# 41 - Multiplayer Networking

## Goals
Provide responsive and fair online gameplay while minimizing latency and preventing desynchronization.

## Networking Model
- Dedicated servers only.
- Server-authoritative simulation.
- Client-side prediction for movement.
- Lag compensation for hit validation.
- Interest management to reduce bandwidth.

## Replication Priorities
1. Player movement
2. Combat events
3. AI state
4. Loot interactions
5. Environmental events

## Performance Targets
- Stable 30 Hz simulation minimum.
- Low bandwidth per player.
- Fast reconnect support.
- Graceful handling of packet loss.

## Design Philosophy
Players should trust that deaths, hits and extractions are determined fairly by the server rather than by client state.