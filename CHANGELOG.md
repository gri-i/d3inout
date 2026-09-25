# Changelog

## Unreleased

- Fade the Volume of audio layers (layers without Brightness).
- Rename the plugin to "In Out": folder `plugins/in-out`, archive
  `in-out-plugin.zip`.
- Show Designer's own error message instead of a bare HTTP status.

## 1.1.0 — 2026-09-24

- Redraw the interface in the style of native Designer widgets: property rows,
  collapsible section, flat In/Out actions.
- Show results and errors in a status bar instead of a blocking alert.

## 1.0.0 — 2026-09-21

- Apply Brightness In and Out automation to selected Designer layers.
- Place automation at layer edges or relative to the playhead.
- Configure separate In and Out durations in seconds.
- Convert seconds to timeline beats and clamp automation to layer bounds.
- Use cubic keyframe interpolation.
- Preserve Brightness keys outside the generated automation interval.
- Provide a compact dark interface with no external dependencies.
