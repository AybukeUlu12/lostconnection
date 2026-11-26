# Lost Connection
NMED 3203 — Temporality × Reciprocity.
Two robots must cooperate to escape a factory. Energy drains over time. Blue powers the relay and uses charging pads; Amber opens the final gate. Either robot can transfer energy to the other when nearby.

## Run
Upload all files to the root of a GitHub repository, enable Pages from main / root. For local use, run a local HTTP server (e.g. `python -m http.server 8000`) and open localhost:8000. ES modules may not work by double-clicking index.html.

WASD/arrows: move; Tab: switch; E: interact; Q: transfer; R: restart. Touch buttons are available. Cyan relay opens gate A; amber switch opens gate B; green pads recharge Blue. Bring both robots to the green exit.

## Live edits
Change DESIGN at the top of script.js: drainPerSecond, moveSpeed, transferAmount, rechargeAmount, rechargeSeconds, interactionRange, relayCost, switchCost.

## Credits and AI use
Concept selected with the student; implementation and documentation generated with ChatGPT. Three.js r160 (MIT; see three-MIT.txt). Geometry is procedural. Student should test, understand and revise the code and report actual AI use and testing before submission.

## Assignment completion
A working published link, two verified bibliography readings and a 315–385 word RATIONALE.md including real user testing are still required. No test observations have been invented.
