# Decision Matrix Engine — Live Test

Public HTML demo of a recursive decision architecture.

**Live app:** https://htmlpreview.github.io/?https://github.com/digitalexploits-cmd/decision-matrix-engine-demo/blob/main/index.html

**Alternate renderer:** https://raw.githack.com/digitalexploits-cmd/decision-matrix-engine-demo/main/index.html

**Repo:** https://github.com/digitalexploits-cmd/decision-matrix-engine-demo

Loop: Decision → Prediction → Action → Outcome → Error → Evidence Update → Matrix Revision → Next Decision

Rules never auto-activate. Observed fact → inference → proposed adjustment → validation → active rule.

State is stored in the browser (`localStorage`). Export JSON from the header for a portable audit copy. Works on mobile and desktop; no build step.
