# Lebanese Civil Defense — Homepage Redesign (Concept)

A redesign concept for the homepage of the Directorate General of Civil Defense, Lebanon ([civildefense.gov.lb](http://www.civildefense.gov.lb/)). Arabic, right‑to‑left.

**Status:** design concept by Olon. This is not the official website.

## Features
- Real-time 3D hero (Three.js): the international civil-defence emblem, a moving point-cloud terrain, rising embers, and emergency light-bar lighting
- Scroll motion (GSAP + ScrollTrigger) and smooth scrolling (Lenis): masked headline reveals, a stacking mission-card section, a message that lights up word by word, a pinned horizontal news rail, 3D tilt cards, a radar map of the governorates
- Dark and light themes: follows the device setting, remembers the visitor's choice, and switches with a circular reveal
- Responsive from phone to desktop; reduced-motion and no-WebGL fallbacks

## Run
Open `index.html` in a browser. There is no build step. Libraries load from the jsDelivr CDN:
- three@0.160.0
- gsap@3.12.5
- lenis@1.1.13

## Content
Text, news items and safety guides come from the current official site. News images and the logo are loaded from civildefense.gov.lb.
