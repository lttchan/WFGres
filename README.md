# WFGres

Interactive presentation layer for the WoW Forever leveling BiS research.

Live graph: once GitHub Pages is enabled, this repo serves the interactive graph from `index.html`.

## Current graph

The public graph now keeps three visibly separate datasets:

- **BASELINE** — the original consistent 144-point single-pass model snapshot used as the clean apples-to-apples comparison baseline.
- **AUDITED AH OFF** — the current source/binding audit layer. It is a working audit view, not silently promoted to final truth.
- **AH ON/OFF — ON = you have a fat wallet LOL** — market-sensitivity view based on the current audit layer.

This separation is intentional. The audit work changed some source classifications and checkpoint values substantially, especially for casters. The original baseline remains available so those changes can be compared rather than mistaken for a finished replacement.

The frozen pre-audit source archive remains in the private WFG repository and is not overwritten.

Source data used to build the graph is retained in the WFG research repository.
