# The Agency Inversion

**An interactive, evidence-aware exploration of what happens when financial institutions continue to hold assets and execute regulated transactions, while AI agents increasingly shape discovery, comparison, recommendation and decision-making.**

Created by **Christopher Hayes, CDAIO**.

> **Publication status:** Interactive research and educational experience  
> **Current release:** v1.4  
> **Research cutoff:** 27 October 2026  
> **Primary entry point:** [`index.html`](./index.html)

## Live experience

- **Interactive experience:** [Open the experience](https://chrisdhayes.github.io/the-agency-inversion/)

## Repository description

Recommended GitHub repository description:

> Interactive exploration of how agentic AI may reshape financial decision-making, institutional economics, delegated authority and trust.

## Why this project exists

Financial institutions may retain custody, execution and regulated accountability while AI agents increasingly influence how customers discover alternatives, compare providers, receive recommendations and make decisions.

This project examines that **agency inversion** through an interactive story. It separates five questions that are often collapsed into one:

1. Who controls attention and discovery?
2. Who shapes the recommendation?
3. What has the customer actually authorised?
4. Which institution or system executes the action?
5. Who remains accountable when the result is disputed, incomplete or wrong?

The experience is designed to make those questions explorable rather than merely descriptive. Readers can change assumptions, inspect control boundaries and distinguish observed evidence from scenarios, illustrations and design proposals.

## Core thesis

The strategic challenge is not simply whether financial institutions should allow or block AI agents.

It is whether institutions can participate in an agent-mediated financial system without allowing intelligence to define its own authority.

The project argues for a deliberate separation between:

- **Reasoning:** what the agent interprets or recommends;
- **Mandate:** what the customer has explicitly delegated;
- **Policy:** what institutional controls permit, block or escalate;
- **Execution:** what the transaction system actually performs;
- **Evidence:** what can later be reconstructed, explained or challenged;
- **Recovery:** how authority can be suspended and uncertain outcomes resolved.

## Interactive exhibits

The experience contains 12 exhibits across eight chapters.

### V01 · Inversion Morph

Compares traditional institution-mediated finance with an emerging agent-mediated model. The emerging-state label includes a hover, focus and tap explanation of the shift and its implications.

### V02 · Decision Influence Map

Moves through the financial decision journey from discovery and comparison to recommendation, authorisation, execution and monitoring. It demonstrates that influence, authority and execution are distinct.

### V03 · Capability Paradox

Shows how the same AI capability can create both opportunity and exposure. Readers can change stakeholder perspectives across the customer, institution, advisor and regulator lenses.

### V04 · Friction Dividend Simulator

Illustrates how balances, rate differences, account volumes and switching assumptions affect a simplified customer-level financial scenario.

### V05 · Institutional Economics Waterfall

Explores a separate hypothetical institutional scenario involving acquisition, savings, margin pressure, attrition and governance costs.

### V06 · Authority and Consequence Matrix

Compares representative financial workflows and proposes different control postures based on authority and consequence.

### V07 · Agent Swarm Experiment

Uses a closed, normalised four-bank system to illustrate how adoption, strategy similarity, response speed and relative attractiveness could influence concentration. It is a sensitivity demonstration, not a forecast.

### V08 · Delegated Authority Laboratory

Lets readers configure a mandate and test whether a proposed action would be allowed, blocked or escalated under an example policy.

### V09 · Decision and Execution Receipt

Creates an illustrative receipt showing mandate, policy, provenance and execution-state information that could support accountability and reconstruction.

### V10 · Institutional Trust Boundary

Contrasts credential sharing, governed read-only access and governed execution.

### V11 · Strategic Response Explorer

Examines three non-exclusive institutional responses: defend the perimeter, enable governed interoperability and compete through trusted agents.

### V12 · Evidence and Claim Explorer

Separates reported developments, primary institutional material, scenarios, illustrations and original synthesis.

## Direct links to chapters

The following fragment links can be appended to the public URL:

- `#inversion` · Agency inversion and V01
- `#influence` · Decision influence and V02
- `#paradox` · Capability paradox and V03
- `#economics` · Economic illustrations and V04–V05
- `#authority` · Authority and consequence and V06
- `#system` · Agent swarm experiment and V07
- `#controls` · Delegated authority, receipts and trust boundaries and V08–V10
- `#strategy` · Strategic response explorer and V11
- `#evidence` · Evidence and claim explorer and V12

These anchors are intended for deep links from the published experience and any related write-up.

## Evidence model

The project intentionally distinguishes different forms of evidence:

- **Reported:** attributed contemporary journalism or institutional statements;
- **Fact:** directly supported primary regulatory, standards or institutional material;
- **Scenario:** a condition-dependent possibility;
- **Illustration:** simplified arithmetic or a deliberately constrained model;
- **Synthesis:** the author's interpretation across sources;
- **Design proposal:** a recommended architecture, control or operating model.

This distinction is central to the project. Simulations and design proposals should not be represented as observed outcomes or established standards.

## Governed Authority and Execution Plane

The **Governed Authority and Execution Plane** is an original design synthesis introduced in the project. It is not represented as an existing regulation or recognised industry standard.

Its proposed flow is:

> Agent proposes → identities are verified → mandate is checked → current data and preconditions are validated → independent policy is applied → human approval is obtained where required → execution is recorded and evidence is preserved.

The design is intended to keep model reasoning separate from business authority and transaction execution.

## Limitations

This experience should be interpreted within the following boundaries:

- The economic models are simplified illustrations, not forecasts.
- The swarm experiment is a closed, normalised system and does not model actual bank balance sheets, liquidity buffers, depositor diversity, payment timing, regulatory intervention or crisis probability.
- Example policy decisions are conceptual and are not connected to real accounts or production execution systems.
- The authority matrix presents design recommendations, not universal risk ratings.
- Regulatory, product and institutional conditions may change after the stated research cutoff.
- Contemporary reporting may rely on overlapping underlying sources and should not be treated as independent corroboration merely because it appears in multiple publications.

## Disclaimer

Independent research and educational content by **Christopher Hayes, CDAIO**. Views are my own. Illustrations and simulations are conceptual, not financial, investment, legal, regulatory or security advice. They are designed to examine a strategic arrangement of authority, evidence and execution under changing conditions.

## Technology

The experience is intentionally distributed as a single, self-contained HTML file:

- semantic HTML;
- embedded CSS;
- embedded vanilla JavaScript;
- no build step;
- no package manager;
- no application framework;
- no server-side dependency.

This makes the project straightforward to inspect, archive and publish through GitHub Pages.

## Accessibility and interaction

The experience includes:

- keyboard-focus treatments;
- semantic buttons and links;
- reduced-motion handling;
- responsive layouts for desktop and mobile;
- dark and light themes;
- accessible expanded-state handling for the emerging-model explanation;
- tap and keyboard alternatives for hover-triggered content.

Automated browser checks do not replace manual accessibility testing. Before treating the experience as fully validated, test it with screen readers, Safari, Firefox and physical mobile devices.

## Run locally

Because the project is self-contained, either open `index.html` directly in a modern browser or serve the repository from a local web server.

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Using Visual Studio Code, the **Live Server** extension can also serve `index.html` locally.

## Publish with GitHub Pages

1. Create a public GitHub repository using the recommended name below.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Save the Pages configuration.
7. Confirm the resulting public URL and update the links in this README if needed.
8. Test every chapter anchor after deployment.

No path changes should be required because the experience is self-contained and the entry file is named `index.html`.

## Recommended repository settings

### Repository name

`the-agency-inversion`

### Description

`Interactive exploration of how agentic AI may reshape financial decision-making, institutional economics, delegated authority and trust.`

### Suggested topics

`agentic-ai` · `financial-services` · `ai-governance` · `responsible-ai` · `interactive-storytelling` · `systems-thinking` · `delegated-authority` · `github-pages`

### Homepage

Set the repository homepage to the GitHub Pages URL after deployment.

### Social preview

Create and upload a 1280 × 640 pixel social preview image using the title **The Agency Inversion** and subtitle **When an AI agent increasingly controls the financial decision journey**. Avoid including unstable or speculative claims in the visual summary.

## Suggested repository structure

```text
the-agency-inversion/
├── index.html
├── README.md
├── LICENSE
└── docs/
    ├── research-brief.pdf
    └── qa-report.md
```

The current publication package includes only the two files required for deployment: `index.html` and `README.md`. The `LICENSE` and `docs` items are recommended additions, not included assumptions.

## Validation before publication

Complete the following checks after deployment:

- [ ] The landing page loads from the GitHub Pages root.
- [ ] The author is displayed as Christopher Hayes, CDAIO.
- [ ] Dark and light themes work.
- [ ] Desktop and mobile navigation work.
- [ ] Every V01–V12 exhibit is present.
- [ ] Calculators respond to changed inputs.
- [ ] The deposit experiment conserves the normalised total.
- [ ] The delegated-authority laboratory returns allowed, blocked and escalated outcomes under the relevant example conditions.
- [ ] The decision receipt updates with the scenario.
- [ ] Hover content also works with keyboard focus and touch.
- [ ] Direct chapter links resolve correctly.
- [ ] Source links open correctly.
- [ ] The disclaimer is visible in the evidence section.
- [ ] The layout is checked in current Chromium, Firefox and Safari browsers.
- [ ] The experience is reviewed on at least one physical mobile device.
- [ ] Screen-reader testing is completed.

## Versioning

Use semantic release tags for the published experience:

- `v1.4.0` · current interactive experience, including author attribution, expanded disclaimer and accessible hover/focus/tap explanation for the emerging model;
- future patch releases · copy edits, accessibility fixes or non-material corrections;
- future minor releases · new exhibits or meaningful interaction changes;
- future major releases · material changes to the thesis, architecture or evidence model.

Keep `index.html` as the stable public entry point. Version history should be managed through Git commits, branches and release tags rather than version numbers in the deployed filename.

## Citation

Suggested human-readable citation:

> Hayes, Christopher. *The Agency Inversion: An Interactive Financial Systems Story*. Interactive research experience, 2026.

Suggested BibTeX entry:

```bibtex
@misc{hayes2026agencyinversion,
  author       = {Christopher Hayes},
  title        = {The Agency Inversion: An Interactive Financial Systems Story},
  year         = {2026},
  howpublished = {Interactive web experience},
  note         = {Independent research and educational content}
}
```

Add the final GitHub Pages URL to the citation after publication.

## AI-use transparency

AI was used as a research, design and editorial partner to organise source material, test the interactive experience, challenge claims, identify counterarguments and refine the presentation. The author retains responsibility for the framing, argument and final editorial decisions.

## Contributions and reuse

This repository is primarily a published research experience rather than an open product roadmap. If contributions are enabled, use GitHub Issues for:

- broken links;
- accessibility defects;
- calculation or interaction defects;
- evidence corrections supported by primary sources;
- browser compatibility problems.

Do not submit real customer information, account details, credentials, personal financial data or other sensitive information.

A software and content licence has not yet been selected. Until a `LICENSE` file is added, the repository should not imply that reuse, redistribution or adaptation rights have been granted.

## Author

**Christopher Hayes, CDAIO**

Independent research on enterprise AI, governed autonomy, data foundations and the changing relationship between intelligence, authority and execution.

---

© 2026 Christopher Hayes. All rights reserved unless a future repository licence states otherwise.
