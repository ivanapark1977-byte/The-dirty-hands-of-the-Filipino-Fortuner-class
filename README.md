Dirty Hands: The Fortuner Class and the Philippine Grey Economy
The Anglophone Blind Spot · Investigative Analysis · May 2025

About this report
This is an interactive HTML research report examining the structural gap between visible affluence and declared income among the Philippine upper-middle class — the Fortuner class — and the grey economy architecture that funds it.
The report argues that roughly 80 percent of Filipino households sustaining a mid-range SUV, private school, and gated subdivision lifestyle cannot account for that lifestyle on declared income alone. It traces the mechanisms — professional income underreporting, BIR audit extortion, kotong, lagay, and public budget theft — that collectively move an estimated ₱2–3 trillion annually through channels the Philippine state cannot or will not see. It connects this grey economy to the Philippines' chronic competitiveness underperformance, its colonial political economy, and the structural reasons reform has not arrived in 38 years of constitutional democracy.
The piece is part of a broader series on Philippine political economy published by The Anglophone Blind Spot.

Contents
SectionTheme01 — The Arithmetic of the FortunerThe lifestyle-income gap, quantified02 — What the Tax Data RevealsBIR's Top 25,000; the SEP income gap03 — The Grey Economy ArchitectureLagay, kotong, BIR extortion, mutual hostage-taking04 — Income Sources by Social ClassSeven-class income composition analysis05 — The Political MachineDynasty dominance, vote buying, 23:1 ROI on political investment06 — More Latin Than AsianThe Iberian colonial inheritance; the booty state07 — The CostCompetitiveness, FDI, IMF counterfactual, 2025 growth data08 — ConclusionThe dividend; the dirty hands sentenceGlossaryLagay, kotong, SALN, SEP gap, tongpats, booty stateReferences13 Chicago-style footnotes

Visualisations
The report contains six embedded data visualisations, all rendered client-side with no external data dependencies beyond CDN-hosted libraries:

Sankey diagram — Philippine income flows from GDP through formal and grey economy channels into four social class destinations, including OFW remittances as a separate source (D3 / d3-sankey)
Bar chart — Monthly lifestyle cost vs. declared income by job type (Chart.js)
Stacked horizontal bar — Estimated income composition by social class across seven classes (Chart.js)
Bar chart — Return on political investment: election spending vs. corruption extraction (Chart.js)
Bar chart — ASEAN tax effort vs. IMD competitiveness ranking (Chart.js)
Horizontal bar — Annual economic cost of the grey economy by category (Chart.js)

All charts are responsive and render at any viewport width.

Technical notes
Dependencies (CDN, no local assets required)
Google Fonts
  Playfair Display
  Source Serif 4
  JetBrains Mono

Chart.js 4.4.1
  cdnjs.cloudflare.com

D3 7.8.5
  cdnjs.cloudflare.com

d3-sankey 0.12.3
  cdn.jsdelivr.net
Deployment on GitHub Pages

Place dirty-hands-fortuner-class.html in your repository root or in a /docs folder
In repository Settings → Pages, set source to the branch and folder containing the file
If deploying to the root, rename to index.html or link directly to the filename
No build step, no dependencies to install, no configuration required
The file is fully self-contained: all CSS and JavaScript are inline

Browser support
Tested on current versions of Chrome, Firefox, Safari, and Edge. The Sankey diagram requires a browser with SVG support. The sticky masthead requires position: sticky support (all modern browsers).
Fonts
Fonts are loaded from Google Fonts via <link> in the document head. If the report is being viewed offline or Google Fonts is blocked, the document falls back gracefully to Georgia (serif), system monospace, and system sans-serif respectively, with no layout breakage.

Data sources and methodology
All figures are sourced from publicly available data. Key sources:

Philippine Statistics Authority — FIES 2023, DepEd enrolment data, salary grade tables
Bureau of Internal Revenue — Revenue Regulation 6-2009 (Top 25,000 taxpayers), tax discrepancy data 2023–25
Bangko Sentral ng Pilipinas — OFW remittance data 2024
Asian Development Bank — Informal economy estimate (34.2% of GDP); ASEAN Investment Report 2024; Revenue Statistics Asia-Pacific 2025
IMD World Competitiveness Center — World Competitiveness Yearbook 2025
International Monetary Fund — Philippines Selected Issues, Country Report 22/24
University of the Philippines — Income underreporting correction factors (SEP gap methodology)
Philippine Center for Investigative Journalism — Dynasty mapping, election spending estimates 2025
Transparency International — Corruption Perceptions Index 2024

Income composition figures in the seven-class chart are structural estimates, not survey data. They are derived from the intersection of BIR administrative records, FIES income distribution data, the UP underreporting correction factors, and ADB informal economy estimates. They illustrate the direction and scale of income composition differences between classes rather than precise percentages, and are labelled as such in the chart notes.

Editorial note
The Anglophone Blind Spot covers geopolitics, energy, and political economy that the English-language press underreports. This report does not name individual subjects. All claims are attributed to publicly available institutional data, peer-reviewed research, or named journalistic sources. The 80 percent probability figure in the conclusion is derived from the residual calculation described in Section 01 and is explicitly framed as an arithmetical inference, not a survey finding.

Related outputs
FormatFilePlatformInteractive HTML reportdirty-hands-fortuner-class.htmlGitHub PagesSubstack long-formdirty-hands-substack.txtSubstack

Licence
© 2025 The Anglophone Blind Spot. All rights reserved. This report may be shared freely with attribution. Commercial reproduction requires written permission.

The Anglophone Blind Spot is an independent investigative publication. It accepts no advertising and is funded entirely by reader subscriptions.
