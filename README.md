Arcanum: ReForged is a modernization and balance project built on Arcanum Community Edition (CE).

The project keeps CE responsible for the underlying game systems—including game rules, saves, inventory transactions, travel, and interaction—while adding an optional modern presentation layer and selected gameplay and balance changes.

Players still need their own original Arcanum game data.

Modernization

Display and Rendering

- Widescreen and fullscreen resolutions.
- Presentation filters.
- Optional GPU-accelerated presentation.
- Native UI composition.
- Smoother follow-camera behavior.
- HD cursor and artwork hooks.
- Rendering diagnostics.
- Classic rendering remains available as a fallback.

Modern Interface

The project provides a responsive graphical interface for:

- HUD.
- Dialogue.
- Five-page graphical character sheet.
- Graphical inventory and equipment management.
  - Drag-and-drop.
  - Item swapping.
  - Item arrangement.
  - Hotkey assignment.
- Barter and loot.
- Journal.
- Settings.
- Save/load.
- Schematics.
- Main menu.

These interfaces preserve the underlying CE actions and retain classic-view fallbacks where appropriate.

Maps

Responsive map interfaces are provided for:

- World map.
- Continent map.
- Town maps.

Map features include:

- Notes.
- Waypoints.
- Travel controls.
- Zoom.
- Overview.
- Corrected panning and clipping.

An optional, locally generated 64-tile HD World/Continent atlas can replace the original map presentation. If the generated atlas is incomplete or invalid, the game automatically falls back to the original map.

Gameplay Changes

Several gameplay improvements are included independently of the optional balance profile:

- Improved dialogue readability.
- Improved map travel controls.
- Optional safe automatic exit from combat.

Optional Balance Profile

The balance changes are controlled by:

BalanceFixes=1

When enabled, the profile applies the documented gameplay adjustments described below.

Set:

BalanceFixes=0

to retain the normal Arcanum CE balance.

Action Points and Speed

- Attacks cost a minimum of 2 AP.
- Speed is capped at 25.
- Hasten provides +50% speed.
- Tempus provides +5 / -5 speed.
- Potion of Haste provides +8 speed.

Spells and Fatigue

Harm

- Damage is 6–24, depending on aptitude.
- Costs 8 fatigue.

Stone Throw

- Receives revised damage, cost, and saving-throw values.

Jolt

- Receives revised damage, cost, and saving-throw values.

Fireflash

- Receives revised damage, cost, and saving-throw values.

Lightning

- Receives revised damage, cost, and saving-throw values.

Quench Life

- Receives revised damage, cost, and saving-throw values.

Disintegrate

- Costs 50 fatigue.
- Deals 60–100 damage to targets above 30% health.
- Against targets below 30% health, it can execute an ordinary creature when the target fails its saving throw.
- Protected targets can still take damage.

Healing

Healing effects are adjusted as follows:

- Minor Healing: 8 fatigue, restores 8–16 HP.
- Major Healing: 22 fatigue, restores 30–45 HP.
- Salve: restores 12–18 HP.
- Accelerate: restores 20–28 HP outside combat.
- Cure All: restores 30–45 HP.

Firearms and Ammunition

Firearms receive more distinct roles and less punishing failure behavior.

- Firearm critical failures can no longer break the gun.
- Pistols, rifles, repeaters, and specialist guns receive distinct statistics.
- Other guns and stronger bows receive approximately 20% more damage.
- Stronger guns pierce 25% of physical resistance.

Ammunition consumption is adjusted:

- Ordinary guns use 1 bullet per attack.
- Repeaters use 2 bullets.
- Automatic weapons use 3 bullets.

Ammunition weight is reduced:

- Bullets weigh 75% less.
- Batteries and fuel weigh 50% less.

Bullet base value is reduced from 3 to 2.

Weapons and Special Items

- The Pyrotechnic Axe deals 10–20 fire damage.
- Two Charged Rings together provide a maximum of +2 DX.
- Azram's Star provides +15% critical chance.

Resistances and Backstab

- Ordinary resistances are capped at 90%.
- The backstab bonus against aware targets is halved.

Crowd Control

Hard control effects are made more difficult to repeatedly apply while a target is already under the same type of control.

Item Durability and Repair

Repairing an item can no longer destroy it through accumulated wear:

- Repair wear cannot reduce an item's current HP below 1.
- Failed repairs may still reduce durability.
- An item therefore cannot be destroyed solely because a repair attempt failed.

Utility Spells

Unlocking / Locks

- Hard locks require an appropriate caster level.
- Hard locks can resist Unlocking.

Charm

- Its reaction bonus cannot be stacked repeatedly.

Invisibility

- Has an upkeep cost.
- Attacking makes the caster detectable.
- Detection is particularly likely when the caster does not have master-level Prowling.

---

Design Approach

Arcanum: ReForged is intended to modernize the presentation and usability of Arcanum without replacing the underlying CE game systems.

The project therefore separates three areas:

1. CE foundation — core game rules, saves, inventory transactions, travel, and interaction.
2. Modern presentation — updated rendering, interfaces, maps, and usability improvements.
3. Optional balance profile — targeted rule changes that can be enabled or disabled independently.

This allows players to use the modernization features while retaining standard CE balance, or enable the optional balance profile for the ReForged gameplay experience.
