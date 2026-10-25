# Design to implementation

A design is useful to a team when it tells people what the player should experience, what rules produce that result, which dependencies matter, and how to know whether the work is ready.

## Working method

1. **Start with the player outcome.** State what the player is trying to do and what changes when they succeed.
2. **Set authority.** Separate current design direction from open questions, implementation choices, and legacy behavior.
3. **Map the system.** Record resources, unlocks, owners, prerequisites, user feedback, persistence, and failure paths.
4. **Write for implementation.** Keep the feature brief clear enough for design, engineering, art, and QA to review together.
5. **Define evidence.** Name the checks or play observations that would support a claim that the feature works.
6. **Report status honestly.** Keep proposed, implemented, tested, and accepted work distinct.

## Example: making an unlock reachable

A feature brief can describe a new settlement capability and its player value. The implementation pass then checks that the prerequisite exists, required materials have a production route, UI can explain what is missing, and save data preserves the result. A structural check can establish reachability; a representative play session is still needed to assess pacing and player understanding.

## Why the operations background helps

Business systems work depends on permissions, data ownership, exception handling, recovery, and clear handoffs. Those habits transfer to game features that coordinate multiple systems and teams. I bring that implementation awareness while keeping the player experience as the reason for each rule.

## Evidence boundary

The public Civilian 66 showcase provides project direction and an Unreal code-set overview. The production repository contains additional source and records. This page describes my design process and does not claim that every planned mechanic has passed native runtime validation.

[Back to portfolio](../README.md) · [Public Civilian 66 showcase](https://github.com/RawPowered/Civilian66-Public)
