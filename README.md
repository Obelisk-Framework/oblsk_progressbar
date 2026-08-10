# Oblsk_progressbar Plugin

## Description
The reference progress-bar UI, a Vue global element listening for
core:client:progress-start/complete/cancel and rendering an animated bar
with a cancel button. Talks to ProgressService (server and client, both in
core, unchanged). Fully swappable: replace this plugin with your own to
change how progress bars look, remove it entirely and provide your own
global element named "progressBars" instead.

## Installation
This plugin loads as part of the `core` resource. After adding it under
`plugins/`, run `obelisk registry:generate` from `core/` on the host, then
restart `core` (or the whole server).
