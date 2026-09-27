# Heparin drip calculator — clinical review draft

Open `index.html` in a browser. For GitHub Pages, upload `index.html` to the repository root and enable Pages for the main branch / root. On iPhone, open that URL in Safari and choose Share → Add to Home Screen. Runs offline with no dependencies; entries are never stored or transmitted.

Source: user-provided Heparin Infusion Monitoring Flowsheet, referring to main policy MD07-05. Features: indication-specific initial bolus and infusion, aPTT titration, stroke/TIA no-bolus rule, fixed-rate pathway, therapeutic monitoring intervals, and optional conversion using the actual bag concentration.

Clinical review points: the repeat 40 units/kg bolus has no explicit maximum on the flowsheet; the aPTT table leaves decimal gaps between 50–51 and 80–81 seconds; reductions that yield zero or less are blocked. For aPTT >100, the flowsheet says stop for 60 minutes and decrease by 200 units/hr; verify restart timing in the main policy/order. Infusion and bolus rounding follows the flowsheet. No automatic cap is applied to adjusted infusion rates, since only *initial* rate caps are stated. Pharmacists may deviate from table rates based on clinical judgment. Confirm all outputs against active institutional policy and orders before clinical use.
