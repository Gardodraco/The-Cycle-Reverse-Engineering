# 42 - Save & Persistence

## Vision
Player progression must be reliable, secure and recoverable. Every successful extraction permanently updates the player's profile while minimizing risks of data loss or duplication.

## Persistent Data
- Character progression
- Inventory
- Stash
- Hideout upgrades
- Faction reputation
- Quest progression
- Statistics
- Seasonal progression

## Saving Rules
- No permanent save during an active raid.
- Final validation occurs on successful extraction.
- Atomic transactions prevent partial saves.
- Versioned save format supports future updates.

## Failure Recovery
- Automatic backups.
- Transaction logs.
- Rollback for corrupted saves.
- Duplicate item detection.

## Design Principles
Persistence must always prioritize integrity over speed. Losing a few seconds is preferable to corrupting long-term player progression.