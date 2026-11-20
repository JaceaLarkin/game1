# Little Dungeon

A small turn-based roguelike that runs in your browser.

## Play

Open the [live game](https://jacealarkin.github.io/game1/) or run `index.html` from VS Code (Live Server works well). Move with WASD or the arrow keys. Fight monsters, collect treasure and potions, and step on `>` to descend. Every move gives enemies a turn.

## Enemies

- `g` Goblin: standard melee enemy.
- `b` Cave Bat: low health, but moves twice per turn.
- `s` Skeleton: shoots down clear corridors from up to three tiles away.
- `o` Orc: high health and strong melee attacks.
- `m` Dark Mage: powerful ranged attacks from up to five tiles away.

New enemy types appear as you descend. Defeating them grants XP and gold based on the monster and dungeon depth.

## Progression

- Defeating goblins gives XP and gold. Leveling up raises maximum health, restores some health, and grants a skill point.
- Open **Skills** to choose from 15 upgrades across the Warrior, Survivor, and Scavenger branches. Spend one point per node; each branch has level gates and connected prerequisites.
- Warrior improves attacks and critical hits; Survivor adds health, armor, and healing; Scavenger improves XP, loot, monster rewards, and shop prices.
- Open **Shop** to buy healing potions, attack upgrades, and armor upgrades with gold.
- When health reaches zero, choose **New run** to start over.
