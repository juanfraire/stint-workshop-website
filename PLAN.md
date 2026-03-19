╭───────────────────────────────────────────────────────────────────────────────╮
│ Plan to implement                                                             │
│                                                                               │
│ Plan: STINT 2026 Website                                                      │
│                                                                               │
│ Context                                                                       │
│                                                                               │
│ STINT 2025 is over. We need to promote STINT 2026 (co-located with IEEE WiSEE │
│  2026, Leuven, Belgium, Sept 14–15) while keeping the 2025 site accessible    │
│ (it has embedded keynote/talk videos). The 2025 index.html becomes            │
│ stint2025.html and a fresh index.html is built for 2026.                      │
│                                                                               │
│ ---                                                                           │
│ Files to Change                                                               │
│                                                                               │
│ ┌────────┬─────────────────────────────┐                                      │
│ │ Action │            File             │                                      │
│ ├────────┼─────────────────────────────┤                                      │
│ │ Rename │ index.html → stint2025.html │                                      │
│ ├────────┼─────────────────────────────┤                                      │
│ │ Create │ index.html (STINT 2026)     │                                      │
│ └────────┴─────────────────────────────┘                                      │
│                                                                               │
│ No other files change (images, fonts, logos reused as-is).                    │
│                                                                               │
│ ---                                                                           │
│ Color Palette Update                                                          │
│                                                                               │
│ Replace space-* (indigo) + cosmic-* (sky-blue) with:                          │
│ - orbit-* — orange palette (primary accent)                                   │
│   - 400: #fb923c, 500: #f97316, 600: #ea580c, 700: #c2410c, 900: #7c2d12      │
│ - stellar-* — amber/gold palette (secondary)                                  │
│   - 300: #fcd34d, 400: #fbbf24, 500: #f59e0b, 600: #d97706                    │
│                                                                               │
│ Background stays bg-gray-900. Gradient accents (from-orbit-500                │
│ to-stellar-600) replace the old indigo-to-blue gradients. This gives a "deep  │
│ space + star fire" aesthetic — subtle but distinct from 2025.                 │
│                                                                               │
│ ---                                                                           │
│ 2026 Content                                                                  │
│                                                                               │
│ Hero                                                                          │
│                                                                               │
│ - Title: STINT 2026                                                           │
│ - Subtitle: Space-Terrestrial Internetworking Workshop                        │
│ - Tagline: The Forum for Delay-Tolerant and Space Networking Research         │
│ - Dates: September 14–15, 2026 (STINT days within WiSEE Sept 14–16)           │
│ - Location: Leuven, Belgium                                                   │
│ - Buttons:                                                                    │
│   - Keynotes (→ #speakers)                                                    │
│   - Submit Paper (→ EDAS/WiSEE link, placeholder for now)                     │
│   - STINT 2025 (→ stint2025.html, secondary style) ← archive link             │
│                                                                               │
│ Scope                                                                         │
│                                                                               │
│ Identical topics list. Update CFP block to reference WiSEE 2026 submission    │
│ via EDAS STINT track. Paper format: IEEE conference template (double-column,  │
│ 10pt), 6 pages, published in IEEE Xplore if accepted and presented on-site.   │
│                                                                               │
│ Keynote Speakers                                                              │
│                                                                               │
│ Two cards (no videos yet — just photos + bios):                               │
│                                                                               │
│ 1. Edward Birrane — Johns Hopkins University APL, USA                         │
│ Talk: "Great networks start with great nodes: building routers for the solar  │
│ system internet"                                                              │
│ Photo: bio-feldmann.jpg (as specified by user)                                │
│ 2. Marius Feldmann — D3TN GmbH, Germany                                       │
│ Talk: "Simplifying Consumption of Delay- and Disruption-tolerant Networking   │
│ Capabilities"                                                                 │
│ Photo: bio-birrane.jpg (as specified by user)                                 │
│                                                                               │
│ No YouTube iframes (event hasn't happened). Cards will be same .speaker-card  │
│ style but without video blocks.                                               │
│                                                                               │
│ Program                                                                       │
│                                                                               │
│ Keep section structure but make it forward-looking (no videos). Describe      │
│ expected program format:                                                      │
│ - Keynote talks                                                               │
│ - Invited talks                                                               │
│ - Peer-reviewed paper sessions                                                │
│ - Panel discussion                                                            │
│ - Links TBD (agenda, papers Google Drive) — placeholders with "Coming soon"   │
│ state                                                                         │
│                                                                               │
│ Important Dates (timeline)                                                    │
│                                                                               │
│ ┌───────────────────────────┬───────────────────────┐                         │
│ │         Milestone         │         Date          │                         │
│ ├───────────────────────────┼───────────────────────┤                         │
│ │ Paper submission deadline │ June 15, 2026         │                         │
│ ├───────────────────────────┼───────────────────────┤                         │
│ │ Acceptance notification   │ July 1, 2026          │                         │
│ ├───────────────────────────┼───────────────────────┤                         │
│ │ IEEE PDF eXpress due      │ August 14, 2026       │                         │
│ ├───────────────────────────┼───────────────────────┤                         │
│ │ Early bird registration   │ August 14, 2026       │                         │
│ ├───────────────────────────┼───────────────────────┤                         │
│ │ STINT 2026                │ September 14–15, 2026 │                         │
│ └───────────────────────────┴───────────────────────┘                         │
│                                                                               │
│ Venue (new section — between Dates and Committee)                             │
│                                                                               │
│ Small new #venue section with:                                                │
│ - KU Leuven info (international research university, Leuven Belgium)          │
│ - Embedded Google Maps <iframe> from                                          │
│ https://maps.app.goo.gl/nXxqTGwPkkF7yNqR8                                     │
│ - Link to https://www.kuleuven.be/english/kuleuven                            │
│ - Nav link added for Venue                                                    │
│                                                                               │
│ Committee                                                                     │
│                                                                               │
│ All 6 members from 2025 unchanged: Fraire, Burleigh, Birrane, Feldmann,       │
│ Caini, Farina.                                                                │
│                                                                               │
│ History                                                                       │
│                                                                               │
│ Same list + add:                                                              │
│ - STINT 2025: Co-located with IEEE WiSEE in Halifax, NS, Canada (October)     │
│                                                                               │
│ Sponsors                                                                      │
│                                                                               │
│ D3TN and IPNSIG (same as 2025).                                               │
│                                                                               │
│ Contact / Footer                                                              │
│                                                                               │
│ Same contact email (juan.fraire@inria.fr). Footer "Resources" adds a STINT    │
│ 2025 link pointing to stint2025.html.                                         │
│                                                                               │
│ ---                                                                           │
│ Cross-link: stint2025.html                                                    │
│                                                                               │
│ Add a small banner or button at the top of stint2025.html pointing back to    │
│ the 2026 site (the new index.html), so visitors who land on the archive can   │
│ find the current edition.                                                     │
│                                                                               │
│ ---                                                                           │
│ Verification                                                                  │
│                                                                               │
│ 1. Open stint2025.html in browser — confirm 2025 content intact with          │
│ back-link banner.                                                             │
│ 2. Open index.html — confirm 2026 hero, orange palette, keynote cards, dates, │
│  venue map.                                                                   │
│ 3. Check all anchor links in nav work (especially new #venue).                │
│ 4. Check mobile menu includes Venue.                                          │
│ 5. Confirm "STINT 2025" button in hero links to stint2025.html.               │
╰───────────────────────────────────────────────────────────────────────────────╯