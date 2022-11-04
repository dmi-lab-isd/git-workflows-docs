# Trunk Based

<center><img src="../.github/assets/trunk.png" width=70%></center>
Trunk-Based Development is a key enabler of Continuous Integration and by extension Continuous Delivery. When individuals on a team are committing their changes to the trunk multiple times a day it becomes easy to satisfy the core requirement of Continuous Integration that all team members commit to trunk at least once every 24 hours. This ensures the codebase is always releasable on demand and helps to make Continuous Delivery a reality.

The dividing line between small team Trunk-Based Development and scaled Trunk-Based Development is a subject to team size and commit rate consideration. The precise moment a dev team is no longer “small” and has transitioned to “scaled” is subject to practitioner debate. Regardless, teams perform a full “pre integrate” build (compile, unit tests, integration tests) on their dev workstations before committing/pushing for others (or bots) to see.
