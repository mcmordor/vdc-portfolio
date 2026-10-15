# Isaak Meakin — Electrical VDC / BIM

Style guide v1.0 · October 2026

## Direction

A technical portfolio with an editorial presentation. Visitors should understand the scope quickly, explore decisions through clear visual evidence, and reach original documents directly. The drawing-package index is the organizing idea.

The website and case-study PDF share warm paper, dark blue typography, teal accents, aligned columns, fine rules, and dark model-image backgrounds. Retain the original black-on-white appearance of the native drawing sheets.

## Colors

| Token | Value | Use |
| --- | --- | --- |
| `--paper` | `#F6F5F1` | Page background; matched to the case-study PDF |
| `--ink` | `#182F3D` | Headings and primary copy |
| `--muted` | `#53636C` | Captions and supporting copy |
| `--accent` | `#187D7C` | Section labels, identifiers, small highlights |
| `--accent-strong` | `#126361` | Text links and hover text |
| `--line` | `#D6DEDC` | Decorative rules and separators |
| `--hover` | `#E9EEEA` | Index hover and focus background |
| `--image-bg` | `#232A34` | Surrounding background for original model exports |

Most of the page is paper, ink, and imagery. Teal identifies navigation and structure. Pair color with labels to communicate meaning. Retain drawing-markup colors in revision evidence. Pale divider colors are not text or meaningful icon colors.

## Typography

- **Inter**, weights 400, 500, 600, 700: headings, body, navigation, captions.
- **IBM Plex Mono**, weights 400 and 500: section numbers, figure IDs, sheet IDs, small metadata labels.
- Google Fonts with `display=swap`; retain `system-ui` and `ui-monospace` fallbacks.
- Title: 44–68px, weight 600, line height 1.12.
- Section headings: 27–36px, weight 600.
- Body: 17px, weight 400, line height 1.65.
- Supporting copy: 14–16px. Captions: 13px. Metadata: 11–12px.
- Uppercase is limited to short labels. Keep paragraphs in sentence case.
- Existing PDFs may retain DejaVu Sans. Match hierarchy, palette, and composition across media. Future editable documents can adopt Inter when font embedding is supported.

## Layout

- Maximum width: 1200px. Desktop gutter: 32px; narrow-screen gutter: 18px.
- Spacing scale: 4, 8, 12, 16, 24, 32, 48, 64, 96px.
- Use left alignment, clear columns, generous section spacing, thin horizontal rules, and square image frames.
- Keep body copy near 60–65 characters per line where practical.
- Pair the short opening introduction with the electrical-only overview. Keep the index near the top.
- Chapter titles and return links remain visible beside content on wide screens; stack on mobile.

## Information architecture

The project introduction supplies purpose, scope, authorship, tools, and building context. The index remains the visitor's map. Retain stable anchors as evidence is added.

| No. | Section | Anchor | Evidence to collect |
| --- | --- | --- | --- |
| 01 | The electrical model | `#model` | Equipment, feeders, riser, model details |
| 02 | Coordination decisions | `#coordination` | Context, annotated issues, decisions, review record |
| 03 | Drawing package | `#drawings` | Sheet index, plans, enlarged views, installation sheets |
| 04 | Prefab + quantities | `#prefab` | Support detail, BOM, material takeoff |
| 05 | A field-driven revision | `#revision` | FC-01 before/after, affected sheets, updated quantities |
| 06 | Project documents | `#deliverables` | Register with file type, revision, and working links |

## Content patterns

**Project introduction:** project name, one-sentence scope, primary image, contribution, tools, and independent-study context.

**Technical story:** context → specific issue → decision and reason → visual or documentary evidence. Use a descriptive title and keep the explanation beside its image. Explain decisions rather than narrating every software command.

**Figure:** preserve the export and aspect ratio. Include meaningful alt text, figure ID, a short caption explaining what to notice, and a full-size link. Locate close-ups within the larger system. Give each image a distinct purpose.

**Before and after:** match camera position, scale, and framing. Label both states. Keep revision clouds with revision evidence. Include related document and quantity changes when supported by records.

**Document register:** show sheet ID or name, purpose, revision, format, and working link. Provide selected previews and direct access to the complete PDF. Add links after the files exist. Describe planned content as planned while assembling the site.

## Interaction and accessibility

- Links are identifiable, with visible keyboard focus. Essential content is accessible without hovering.
- Navigation works without JavaScript. Full-size images use ordinary links.
- Motion helps orientation or explanation. Respect reduced-motion settings.
- Ordinary text needs at least 4.5:1 contrast; large text needs 3:1. Teal `#187D7C` on paper `#F6F5F1` is approximately 4.52:1. Use darker `--accent-strong` for links and recheck contrast when backgrounds change.
- Use semantic headings, labeled navigation, a skip link, descriptive alt text, and readable mobile layouts.
- Future switches and comparisons must support keyboard and touch.

## Voice and claims

- Write active, concrete sentences: “I adjusted the hanger locations and updated the quantities.”
- Present completed work, decisions, and evidence. Reserve learning-goal checklists for private notes.
- Distinguish my electrical work from linked Autodesk building context.
- Identify FC-01 as a simulated field revision. Quantities reflect modeled objects.
- Distinguish approved intersections from resolved clashes; preserve the recorded review disposition.
- Keep independent-study context and “not for construction” visible in the project context and document footers.
- Use certification, client, cost-saving, code-compliance, and construction-readiness claims only when documented and appropriate.

## Files and future additions

| Path | Purpose |
| --- | --- |
| `index.html` | Homepage and project narrative |
| `assets/css/styles.css` | Shared design tokens and components |
| `assets/images/` | Selected original exports with descriptive lowercase filenames |
| `assets/documents/` | Future publishable PDFs and reports; create when adding documents |
| `STYLEGUIDE.md` | Design and editorial source of truth |

Use relative URLs so the site works at `/vdc-portfolio/`. Keep original master files outside the published site. Prioritize coordination stories, drawing previews, the revision comparison, and the document register. Add image switches when suitable exports exist; consider a 3D viewer when it communicates the scope more clearly than selected images. Preserve the index and direct document access.

Before release, check links, headings, contrast, keyboard access, mobile stacking, image legibility, captions, authorship, and document revisions. Review the page in a browser before considering its visual presentation final.


## October 2026 narrative update

The opening now explains the project purpose in plain first-person language. Keep the compact seven-section index near the opening. Purpose, source inputs, the selected zone and session planning precede the model narrative. The warm paper, navy, teal and font system remain unchanged.

Use `project` or `educational project` in public copy. Preserve the original authorship and simulation labels. Use the tracker to ground chronology, outputs and decisions. Do not publish internal application notes as narrative copy. Early session records are historical; the final scope is six receptacles and one junction box, with six conduit and eight tray supports.

Stable section anchors: `#planning`, `#model`, `#coordination`, `#drawings`, `#prefab`, `#revision`, `#deliverables`. Supporting pages: `documents.html`, `session-history.html` and `clash-review.html`.

The four HTML pages are buildless and work without JavaScript. Model images retain their original aspect ratio and are linked at full size. Drawing and PDF previews are rendered from the original documents. Keep revision clouds within revision evidence or original linked record drawings.
