# SHS Global Technologies — website

Built static output of the SHS Global Technologies website, published to
GitHub Pages so it can be viewed without running anything locally.

**Live:** https://mannamgopi666.github.io/shs-site/

This repository contains generated files only (HTML, CSS, JS, fonts). The
source lives in a separate private repository.

## Note on the contact form and admin sign-in

The website is fully browsable here, but it is the front end only. The contact
form and the `/admin` sign-in both talk to a Spring Boot API and a PostgreSQL
database that are not part of this static deployment, so those two actions are
marked as unavailable in the interface. Everything else — the 3D scene, the
scroll, the case studies, the capability sequence and the tonal inversion —
works exactly as built.
