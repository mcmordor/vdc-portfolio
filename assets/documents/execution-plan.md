# ST-VDC-01 | Electrical VDC capstone working plan

**Prepared by:** Isaak Meakin  
**Date:** September 29, 2026  
**Status:** Internal S04 working plan; BEP-inspired, not an issued project BEP  
**Project:** Independent educational Snowdon Towers capstone; not for construction

**Who this is for:** I use this plan to keep my scope, file setup, modeling rules, checks, and evidence consistent as I work. It is primarily an internal project guide. A future portfolio case study may summarize the relevant decisions and offer this plan as optional supporting evidence; reviewers do not need to read the full plan to understand the finished work.

## 1. What I am building

I am creating an original, limited electrical power and raceway model that starts near Parking Utility P05 and serves a small study area around Retail 109 and Stair S3. My study boundary is approximately grids **7–9/A–D**, with modeling emphasis **8–9/A–C**. Parking, L1 Block 43, and L2 provide the vertical context. This is my educational project; I am not claiming that a contractor assigned or built this work.

My project brief defines the intended equipment, devices, conduit rack, cable tray, schedules, six sheets, one prefab assembly, a simulated field change, and final exports. If I work outside this zone, I will record why.

## 2. Model ownership and starting file

| File role | Rule |
|---|---|
| Autodesk architectural, structural, HVAC, and plumbing RVTs | I will preserve them as received and link them into my electrical model for context and coordination. |
| Autodesk completed electrical RVT | I may consult it as a reference. I will not copy its elements into my original work or present it as mine. |
| My electrical RVT | I will create a **Project** from the installed **English-Imperial/Electrical-Default.rte** template in Revit 2027. My first working filename is `ST-VDC-01_Electrical_Isaak_v001.rvt`. |
| Outputs | I will name PDFs, DWGs, NWCs, screenshots, schedules, and records with the project code and version and keep them separate from the received files. |

I will use my existing capstone folder structure. My new RVT lives directly in `Working`, beside the `Reference Models` folder containing the received files. I will leave those files in place after establishing links; a move would require path repair and another alignment check.

## 3. Linked-model setup

1. I will add the architectural model first and compare a known grid intersection and the Parking, L1 Block 43, and L2 datums in plan and 3D.
2. I will add structural, HVAC, and plumbing references, then verify their grids/levels or fixed architectural features in at least one plan and one 3D/section view. I will record the placement method and any adjustment.
3. I will check actual alignment, not just whether a link loaded. If a link is missing or displaced, I will record the issue before routing around it.

I will choose the link placement method from the actual models in S06; I have not yet verified their origins or shared coordinates.

## 4. Modeling and drawing rules

- I will use feet and inches and verify Project Units after creating the model.
- I will give equipment and devices unique, consistent identifiers. I will label assumed characteristics as *educational inputs*, not engineered values.
- I will record conduit/tray size, elevation, and route intent, then check fittings and continuity in plan, section, and 3D before calling a run coordinated.
- I will keep a Parking power plan, L1 power plan, relevant L2/overhead view, at least one section, and a cropped 3D coordination view, with descriptive saved-view names.
- I will use the sheet index in my project brief: `E0.01`, `E1.01`, `E2.01`, `E2.02`, `PF1.01`, and `IS1.01`. I will set sheet scales and title block when I make the first test sheet.
- I will check modeled geometry and data before exporting and keep issue, decision, change, and QA records with the deliverables.

## 5. Coordination finding and scope rule

I found a labeled conduit chase and services near the selected area in the L2 mechanical plan. A close 3D slice through grids 7–9/A–D shows **little ductwork directly in my proposed route**. I have not confirmed a duct collision or clearance problem. Busier service areas appear elsewhere in the broader mechanical model.

My brief targets three documented coordination problems. I will use observed spatial, access, or constructability questions and show each condition, decision, and before/after evidence. **I will not claim artificial clashes to meet a count.** After the linked baseline works, I will test this zone. If it lacks enough meaningful issues, I will either extend a route into a nearby busier area and document the boundary change or revise my brief and tracker.

## 6. Evidence and review rhythm

At the end of each session, I will save/version my working file, capture a useful image or export, note decisions and open questions, update the tracker, and write my next action. I will select verified evidence for the public portfolio and label screenshots of Autodesk's model as reference context.

**Gate 0 review before S05:** I have defined the scope, source ownership, model name/template, zone, and evidence rules. I will determine link placement, equipment characteristics, routing elevations, and coordination issues from linked-model checks. My first modeling checkpoint is a saved electrical RVT with verified units. I will place electrical elements after the reference links align.
