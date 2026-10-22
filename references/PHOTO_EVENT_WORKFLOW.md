# Photo-first event posters

Use this branch only when the user explicitly wants a real supplied photograph as the background and asks for editorial typography, even if they invoke `mono-color`. This is a deliberate exception to the default one/two-ink print treatment. The photograph remains full color; restrict the *added overlays* to a small, intentional palette.

## Input contract

Record before generating: source photo, face/pose/props to preserve, exact event copy, requested logo assets, output ratio, requested treatment of the photograph, palette source, and approval sequence. Distinguish a reference poster's transferable properties (blur, hierarchy, atmosphere) from its exact lettering/layout. Do not infer an event year or venue address.

If the official brand logo has not been supplied or cannot be accessed, put neutral placeholder text in a mockup and state that it is not an official logo. Do not redraw, recolor, invent, or approximate a logo. A brand kit can color event metadata; it does not authorize recoloring the logo.

## Sequence

1. **Feed first.** When Instagram Feed is the primary requested format, create at 4:5. If asked for two options, show two distinguishable previews and label them. Wait for the user's choice before adapting Story or other formats.
2. **Approve a direction.** Capture what the user approved at the level of layers: portrait, treatment of background, headline, accent, information band, copy, and logo status. A later request to mix features means borrow those features, not silently change approved facts.
3. **Make a concept.** Image generation is suitable for testing atmosphere and composition. Ask it to retain a real person's face, pose, clothing, and props, but inspect for altered identity, anatomy, letterforms, and background artifacts. Describe the result as a mockup when exact identity or text is not guaranteed.
4. **Make the production version.** Use the untouched original photo as an image layer and overlay editable typography, shapes, and an official logo in a design app or deterministic layout workflow when authorized and available. Do not substitute a model-regenerated face for a preserved photo. Recheck export dimensions (1080 x 1350 for Feed) and text.
5. **Revise by coordinates.** Translate feedback such as `x=26.4%, y=58.1%` to the displayed image dimensions and inspect a crop around it. Name the actual layer or boundary there. Change only that component, then compare the rest with the approved version. If an image edit changes the face, copy, or layout, revert and use layer editing.
6. **Quality gate.** Inspect at full size and phone thumbnail: face and hands natural; background blur limited to background; text exact; hierarchy legible; accent color only on event information; brand asset genuine; ruled lines intentionally level when requested; no unnecessary Story before Feed approval. Report remaining provisional parts honestly.

## Two failure modes to avoid

| Symptom | Cause and repair |
|---|---|
| Background looks AI-generated near a person's silhouette | Image model re-rendered the whole photograph. Return to the untouched photo, blur only background where feasible, and edit the overlay as layers. A verbal instruction to preserve identity is not pixel-level preservation. |
| A lime underline angles upward or appears brushy | A manual gesture was inherited from mono-color's print grammar. For precise event typography, specify `horizontal, level, constant thickness, clean endpoints` and verify it visually; a vector line is more reliable. |

See [Guest Shift case study](GUEST_SHIFT_CASE_STUDY.md) for the real iteration and visual diagrams.

