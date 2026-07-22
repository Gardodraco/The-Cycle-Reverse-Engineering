# 01 - Core Design Pillars

## Mission
Create an extraction shooter where every expedition creates a unique story, every decision has weight, and the world keeps moving even when the player is not looking.

## Design Intent
The game must avoid three common failures of the genre:
- empty raids with no meaningful systemic interaction
- hard meta builds that dominate every situation
- progression that only rewards repetition instead of mastery

The pillars below exist to prevent those failures from creeping into future features.

## Pillar 1 - A Living World
The world continues to evolve without the player. Wildlife competes for territory, weather changes routes, resources regenerate differently, and events reshape priorities.

### Implications
- POIs should not exist as static loot containers.
- Creature populations must react to player pressure and environmental conditions.
- Weather and events must influence route planning, combat timing and extraction strategy.
- Faction activity should change the danger level of regions over time.

### Design Rule
A location is not complete until it changes the way players move, fight, gather information or extract.

## Pillar 2 - Meaningful Decisions
Every item carried into a raid, every fight accepted or avoided, and every extraction attempt should have long-term consequences.

### Decision Surfaces
- What to bring into the raid
- Which route to follow
- Whether to engage or disengage
- How long to stay in the zone
- What to keep, sell or craft after extraction
- Which faction or vendor to favor

### Design Rule
A decision is only meaningful if there is a visible trade-off. No choice should be pure upside.

## Pillar 3 - Emergent Gameplay
Systems interact with each other instead of relying on scripted moments. AI, weather, economy and players should constantly create unexpected situations.

### Emergent Sources
- AI reacting to sound and threat levels
- Weather changing visibility and sound propagation
- Factions and patrols altering route safety
- Dynamic objectives drawing groups of players into conflict
- Economy changes shifting the value of specific resources

### Design Rule
If a feature cannot interact with at least two other systems, it should be redesigned or removed.

## Pillar 4 - Multiple Playstyles
Combat, exploration, trading, crafting, reconnaissance and support should all be viable paths to progression.

### Supported Roles
- Aggressive raiders
- Stealth and reconnaissance players
- Traders and crafters
- Resource specialists
- Group support players
- High-risk high-reward hunters

### Design Rule
No single playstyle should own the best progression, best rewards and best safety at the same time.

## Pillar 5 - Sustainable Progression
Progression rewards knowledge, mastery and planning more than repetitive grinding.

### Progression Layers
- Account progression
- Faction reputation
- Crafting knowledge
- Hideout growth
- Seasonal progression
- Player skill and map knowledge

### Design Rule
Grinding can accelerate progress, but it must never replace understanding the game.

## Feature Evaluation Checklist
Whenever a feature is proposed, ask:
1. Does it strengthen one of the five pillars?
2. Does it create new decisions or just add noise?
3. Does it interact with existing systems?
4. Does it support more than one playstyle?
5. Does it improve long-term replayability?

If the answer to any of these is clearly no, the feature needs revision.

## Anti-Goals
The project should avoid:
- static raids with no systemic pressure
- loot that exists only to fill space
- linear progression that ignores player skill
- weapon upgrades with no drawback
- mechanics that create mandatory meta behavior
- content that becomes irrelevant immediately after release

## Final Principle
The game should always feel like a place where events happen, not a menu of isolated systems. Every feature must preserve that feeling.