# autiva-media

Public media assets for AUTIVA posts. Files under `assets/` are served by
GitHub Pages at:

    https://adityamondal-ai-spec.github.io/autiva-media/assets/<name>

Those URLs exist so a posting API can reference a real image or video by URL —
Publora and LinkedIn take `media_urls`, never file uploads.

Publish with AUTIVA/workflows/media_host.sh, do not copy files in by hand:

    bash workflows/media_host.sh ~/shot.png

.nojekyll is deliberate: Jekyll skips files beginning with an underscore.
