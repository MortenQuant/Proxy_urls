# Proxy URL Registry

Pre-constructed proxy URLs for authoritative government portals that
rate-limit automated clients.

Used by the Aegir offshore-wind-project-searcher skill as a fast path
to consent register pages when direct `web_fetch` returns 429.

## Contents

- [Portal registry](portal-registry) — UK NSIP consent register

## How it works

Each registry entry contains a pre-constructed proxy URL via
`urltomarkdown.herokuapp.com`. The target portal is the UK Planning
Inspectorate's NSIP register. The proxy converts the HTML page to
clean Markdown that is easier to parse.

Maintained by Morten Jensen
