# Session 10: conduit routing and diagnostic judgment

Snowdon Towers electrical VDC capstone · Isaak Meakin · October 6, 2026

**Portfolio priority:** Feature this session as a learning and troubleshooting story on portfolio pages 3–4, and retain it as an interview talking point. Isaak described it as the most intense session so far, with valuable insights and challenges overcome.

## The story to preserve

Session 10 documented the initial equipment-room conduit routes and the route from P-208-1 to one Level 1 junction box. The route was difficult to inspect through walls and linked systems. Some apparent protrusions at the building edge came from the section-box cut. Two junction-box warnings then raised a separate question about connectivity.

The session worked through those questions using clearer views, selected-element properties, the junction-box family, and the actual warning list. The result was an initial routing milestone with recorded parameters and an explicit explanation of the remaining warnings.

## Challenges, decisions and lessons

| Challenge | What the session established | Lesson to discuss |
| --- | --- | --- |
| Walls and linked systems obscured the electrical route. | Hiding ARCH and HVAC links in the working 3D view produced a readable electrical-only overview. | Choose a view that answers the inspection question, and retain architectural context separately. |
| Pipes appeared to protrude at the building edge. | The appearance was explained by section-box clipping. | Check the view boundary before treating an apparent condition as a modeling defect. |
| Route elevations were hard to compare. | Selected segments showed different offsets and reference levels. | Record each elevation with its reference level before comparing heights. |
| The box showed disconnect markers despite having no conduit on those faces. | The tee junction-box family had three ports. The two stored warnings identified unused connectors #2 and #3 on element 963291. | A warning requires investigation. An unused connector can be intentional for the current scope. |
| The remaining warnings needed a closeout decision. | The family was retained and the two unused ports were documented as accepted for the current scope. | Record the reason for an accepted warning and revisit it if the routing or box changes. |

## Evidence to pair with the story

- **C024:** Clean electrical route overview, `image(20261007-002955).png`.
- **C021–C023:** Selected-segment properties, including trade diameter, elevations and reference levels.
- **C025:** Family Editor capture showing the three junction-box connection points.
- **C026:** Review Warnings capture identifying the two unused ports.
- **AD-010–AD-012:** Warning disposition, revised device scope and sampled geometry decisions.
- **Closeout record:** `ST-VDC-01_S10_Primary_Conduit_Layout_v001.pdf`.

The portfolio sidebar should pair the route overview with the connector and warning evidence. Explain the uncertainty, the checks performed and the decision reached. Preserve the earlier cluttered view as supporting process evidence if it is useful at readable scale.

## Interview talking point — first-person draft

“Session 10 was my most demanding capstone session so far. I was documenting the initial conduit route from the equipment area to a Level 1 junction box, but the linked building systems made it hard to see what was happening. I improved the view, checked the segment properties and their reference levels, and investigated the junction-box warnings in the family and warning list. The two warnings came from intentionally unused connector ports, so I documented that decision and kept the family intact. I learned to work from specific evidence when a view or warning is confusing, and to explain the result clearly.”

## Accurate portfolio framing

Present this as an initial routing and diagnostic milestone. The accepted unused ports do not establish a zero-warning model or prove every connection. The section-box appearance was a view condition. Later physical clash resolution, engineered sizing, supports and clearance checks require their own evidence. The current device scope is six receptacles and one junction box, with S11 overhead conduit rack next.
