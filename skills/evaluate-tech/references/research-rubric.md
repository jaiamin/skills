# Research rubric

## Evidence ledger

Keep concise working notes per candidate: current version/edition, role in the category, sources and dates, verified strengths, limitations, adoption signals, cost inputs, and unresolved questions. Build rankings from this ledger rather than impressions. Label a source's publication date separately from the date it was checked. Older authoritative documentation can still describe a current product; do not discard it solely because its publication predates this year.

Use the following distinctions in reasoning:

- **Verified fact:** Supported by a current primary source.
- **Measured performance:** Supported by a benchmark whose methodology can be inspected; indicate vendor versus independent results.
- **Adoption signal:** Supports usage or ecosystem strength, with stated limits. An official project linking to users is weaker than users independently documenting use.
- **Inference:** A reasoned implication of evidence, such as how a tool's architecture affects integration effort. Label it when material.
- **Unknown:** Missing, conflicting, inaccessible, or unsuitable evidence. An unknown is not automatically a failure.

Do not make technical claims from forum anecdotes alone. Use discussions to locate issues, then inspect maintainer responses, reproducible reports, official limitations, or relevant release changes. Distinguish historical problems from unresolved current problems.

## Capability and practical performance

Compare task completion and output quality first, then latency, throughput, resource use, reliability, and scale as relevant. Consider required integrations, supported languages/platforms, debugging, testing, observability, documentation quality, and deployment friction. Count capabilities that serve the user's task rather than raw feature counts.

Avoid comparing benchmark numbers across incompatible workloads. If no common benchmark exists, compare documented capability and operational fit, report the performance uncertainty, and suggest a small representative evaluation rather than inventing an ordering.

## Total cost and value

Check official billing units and the terms that matter for the use case:

- Subscription minimums, seat counts, usage meters, regional prices/currency, and annual versus monthly billing.
- Free tier versus time-limited trial, credits, sandbox-only access, restricted production use, and credit-card requirements.
- Included usage, quotas, overage, rate limits, retention, premium features, data export/egress, support, and licensing rights.
- Underlying model/API charges, infrastructure, database/storage, and whether these are included or charged separately.
- For self-hosting: existing hardware, additional hardware, memory/VRAM, electricity, hosting, and maintenance effort. Do not call self-hosting free without explaining its cash costs and effort.
- For continuous workloads: calls/events per interval, active hours, retries, polling, cache hits, background refreshes, and whether billing is per call, resource, user, or connection. A program running 24/7 does not imply paid calls every second.

Calculate only from verified rates and explicit workload assumptions:

`monthly cash cost = fixed fees + billable usage above allowances + necessary external services + infrastructure`

For time-based usage, state the month length and activity assumption, such as 30 days and 24 hours/day. Distinguish averages from upper bounds. Avoid double-counting quotas or confusing per-million prices with per-unit prices. Show ranges when uncertain; mark sales-only pricing as unknown rather than zero. Note the relevant free-tier ceiling and how costs change at higher usage. Keep setup and maintenance effort separate unless the user supplies a value for their time.

## Learning and professional value

Assess these independently of current feature quality:

- Transferable concepts and skills, including architecture, protocols, evaluation, debugging, reliability, and deployment.
- Depth available beyond tutorials, quality of docs/examples, and how quickly the user can complete a meaningful project.
- Realistic adoption in the user's target engineering work; distinguish beginner popularity, production use, and employer demand.
- Breadth of integration, portability, vendor lock-in, migration effort, and likelihood that learning survives tool changes.
- Maintenance health and stability: release activity appropriate to project maturity, governance, ownership, compatibility policy, and licensing. Do not equate rapid releases with quality or a mature project's quiet release cadence with abandonment.

Avoid generic promises that a tool will improve employability. Cite current postings, surveys, or other direct evidence when asserting hiring demand. When evidence is sparse, explain transferable value without claiming demand. Recommend one focused starting point; do not turn a comparison into a long list of tools the user must master.

## Final decision check

Before answering, check whether:

- Every discovered mainstream candidate received evidence-based assessment or an explicit scope/disqualification reason.
- The recommendation fits the actual task, hardware, deployment, and budget.
- Capability, cost, and learning value all influenced the choice.
- Strong claims have suitable citations and versions/dates where needed.
- Costs include the usage behavior that could surprise the user.
- The runner-up has a clear reason to choose it, and the winner has a stated drawback.
- Unknown evidence or changed priorities could reverse the result, and that possibility is stated when material.
