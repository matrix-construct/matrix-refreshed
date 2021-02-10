# MSC3004: m.room.animation

The event `type` `m.room.animation` with `state_key` `""` is specified to have the following `content` properties:
- `enable`: JSON literal. Defaults to `true` if not present or erroneous.

#### Client Behavior

Clients may not "show chat effects" when `enable` is `false`.
