# Progression and settlement systems

## Design problem

A progression screen can promise an upgrade while leaving the player unsure what it enables, how to obtain it, or whether it has a useful result. In *Civilian 66*, progression must turn survival into a growing settlement and make each new capability change the player's choices.

## Design model

The design separates three kinds of progress:

- **Skill Points authorize capability.** They open an engineering path or raise what the player can build.
- **Credits pay for procurement and services.** They make trade a meaningful part of the settlement loop.
- **Materials pay for physical implementation.** The player still has to gather and process what the structure or upgrade needs.

An active unlock should lead to a reachable result. The player should be able to see the next settlement milestone and the prerequisites still missing.

## Player loop

1. Leave the relative safety of the settlement and explore, fight, mine, or recover supplies.
2. Return with resources and decide what to keep, process, sell, or use.
3. Invest in an authorized capability, procurement, or physical structure.
4. Establish a safer or more useful foothold.
5. Use that foothold to take on a larger expedition or campaign milestone.

The loop gives the player tradeoffs. Selling raw materials can create liquidity, while processed materials may be needed for fabrication. A reserve rule can protect progression-critical stock without removing the player's control over surplus.

## Design decisions to discuss

- Does each unlock have a clear physical or systemic payoff?
- Can the player tell which prerequisite is blocking the next milestone?
- Does a new merchant or structure add a distinct role to the settlement?
- Can the player reach a requested material through currently available production?
- Does selling create choice while preserving a viable path to later upgrades?
- Does a save restore the player's established foothold and ownership state?

## Evidence and status

The public *Civilian 66* showcase maps the project direction and Unreal code sets. It does not provide the complete production source or a public playable build. The progression case here is a selected design summary, not a claim that the entire described loop is complete or balance-validated.

## What this work demonstrates

This case shows how I connect player-facing intent to resource flow, progression gates, reachable outcomes, interface communication, save-state needs, and validation questions. It is the kind of feature work I would bring to a systems or progression design team.

[Back to portfolio](../README.md) · [Public Civilian 66 showcase](https://github.com/RawPowered/Civilian66-Public)
