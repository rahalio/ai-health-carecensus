# Carecensus — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Model owner, a service-line clinical leader

- As a service-line leader, I want to register a deployment by answering questions about what it does and to whom rather than by writing a technical document, so that governance costs me an hour and not a week.
- As a service-line leader, I want the system to tell me exactly what evidence my next gate requires and what is already on file, so that I am not preparing for a committee whose expectations I have to guess.
- As a service-line leader, I want to record a baseline before go-live and be reminded if I am about to launch without one, so that I do not lose the ability to prove my own result.
- As a service-line leader, I want to retire a deployment that did not work without it being treated as a failure of judgement, so that the honest answer is available to me.

### Validation and clinical informatics analyst

- As a validation analyst, I want to attach a local validation study with subgroup results and the completeness of the demographic data behind them, so that the committee reads a caveated result rather than a flattering one.
- As a validation analyst, I want drift and performance monitoring signals to land against the registered deployment and its version, so that a degradation has an owner and a review date rather than a dashboard nobody opens.
- As a validation analyst, I want to see which vendor-supplied models we have never independently validated, so that I can prioritise the ones with the widest clinical reach.

### Compliance, privacy, and regulatory affairs officer

- As a regulatory officer, I want each deployment's device determination recorded with its reasoning and its clearance conditions, so that I can answer an inspector without reconstructing a decision made two years ago by someone who has left.
- As a regulatory officer, I want to see every deployment running outside its intended-use conditions and who signed the acceptance, so that off-label operation is a decision the organisation owns rather than a discovery.
- As a privacy officer, I want the secondary-use basis and the business associate agreement recorded for any validation that used patient data, so that our own evaluation activity is defensible.

### Chief financial officer and finance business partner

- As a finance business partner, I want realised benefit reported against the hypothesis, net of total cost of ownership and on an attribution rule we agreed in advance, so that the portfolio number survives contact with my own forecast.
- As a chief financial officer, I want duplicate deployments across service lines surfaced with the spend attached, so that consolidation decisions are made on evidence rather than during budget season.
- As a chief financial officer, I want null and negative results reported as prominently as wins, so that the portfolio's credibility does not depend on selective reporting.

### Governance committee chair and internal auditor

- As a governance chair, I want a deployment that scaled beyond its approved scope to appear automatically as an exception with the expansion it made, so that scope creep is detected by the system rather than by rumour.
- As a governance chair, I want a live deployment whose owner has departed or whose monitoring has lapsed to be flagged for suspension, so that unattended algorithms do not accumulate.
- As an internal auditor, I want to reconstruct the gate decisions, evidence, and thresholds that were in force on any past date, so that an audit or a legal request can be answered from the record.
