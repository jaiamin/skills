---
name: evaluate-tech
description: Deeply research and compare current technical tools, frameworks, libraries, developer platforms, and software within a category. Use when the user asks which options are best, worth learning, worth using, most popular, or best value; requests alternatives or rankings; or names a category for a technical buying or learning decision. Evaluate the mainstream developer and enthusiast ecosystem using current evidence, practical performance, total cost, and transferable learning and career value.
---

# Evaluate Tech

Turn a category into a researched decision about what to use and what to learn. Give capability/performance, economic value, and learning value equal importance by default. Treat popularity as evidence of ecosystem strength, not proof of quality. Adapt priorities to the user's actual goals and constraints.

## 1. Frame the decision

- Establish the current date from the session. Research the current year through today; never assume a fixed year or predict future releases as facts.
- Extract the use case, existing stack, experience, hardware, budget, expected workload, deployment preference, and whether the goal is learning, practical use, or both from available context.
- If given only a category, proceed with a stated default: an individual developer evaluating tools for hands-on learning and realistic personal projects, with potential professional use. Favor low recurring costs while preserving capability and valuable skills. Do not require an intake questionnaire.
- Ask at most a few focused questions only if missing context could materially reverse the recommendation. Continue independent research when possible.
- Define category boundaries. Distinguish direct substitutes from complementary products, layers, hosted services, and self-hosted editions. Group distinct subcategories rather than force incomparable products into a single ranking.
- Identify hard requirements first. Disqualify incompatible options before weighing tradeoffs; show consequential disqualifications.

## 2. Discover the ecosystem broadly

- Browse the web on every evaluation. Search both the category broadly and alternatives to the apparent leaders; include established tools, newer tools with demonstrated traction, open-source/self-hosted options, and paid services where applicable.
- Triangulate discovery across official projects and package registries, developer surveys or documented production use, and recent community discussions or comparisons. Use community material to discover candidates and recurring concerns, then verify technical claims with primary sources.
- Maintain an internal candidate list with inclusion/exclusion reasons and adoption evidence. Investigate every identified mainstream or heavily used option within the stated scope. Do not select only three familiar tools and stop.
- Use multiple adoption signals where available: registry usage, active users or projects, integrations, surveys, employer postings, production case studies, contributor activity, release cadence, and community breadth. Cite counts with dates. Account for inflated downloads, stars, marketing, and duplicated vendor comparisons.
- Include credible emerging challengers separately when their capability or value could change the choice. Label uncertain adoption honestly.
- Continue discovery until two distinct additional searches produce no new credible mainstream candidates. Expand research if the finalists' own documentation reveals overlooked competitors. This is a coverage heuristic, not proof of exhaustiveness.
- State the scoped coverage and any omissions. Never claim to have evaluated every product in existence. For a huge category, map its subcategories and cover their mainstream contenders; explain the boundaries explicitly.

## 3. Verify every serious candidate

Read [research-rubric.md](references/research-rubric.md) before assessing candidates or estimating costs.

- Open relevant sources, not just search snippets. For each viable candidate verify current documentation, supported capabilities, pricing/license, deployment and integration requirements, and maintenance status. Use release notes or a current repository when versions matter.
- Prefer official documentation, pricing, repositories, original benchmarks, published surveys, and firsthand production reports. Use independent primary evidence to check vendor claims when available. Do not use unsourced rankings as evidence.
- Seek evidence against the likely winner as well as evidence for it. Investigate recurring issues, migration costs, breaking changes, free-tier restrictions, and unsupported requirements.
- Compare performance only under relevant, comparable workloads. Explain versions, hardware, settings, workload, and benchmark origin where they affect interpretation. Separate measured results from documented features and reasoned judgments. Do not manufacture benchmarks or run paid workloads without authorization.
- Evaluate current job relevance from current evidence when making career claims. Separate direct demand for a named tool from transferable concepts. Do not assume GitHub stars establish hiring value.
- Resolve conflicting or stale claims with current authoritative sources. Mark unavailable pricing, unverified limitations, weak adoption evidence, and uncertain performance instead of filling gaps with guesses.
- If browsing is unavailable, disclose that a current researched ranking cannot be verified. Provide a provisional framework or analysis only; do not present it as completed current-year research.

## 4. Compare the tradeoffs

- Use three equally important default dimensions: (1) practical capability and performance, (2) total economic value, (3) transferable learning and professional value. Use maturity/adoption, maintainability, developer experience, privacy, and portability to explain durability and fit.
- Change priorities when the user supplies goals, budgets, or constraints. State decisive assumptions briefly. Do not let a composite score override hard constraints or strong evidence.
- Prefer evidence-backed qualitative assessments to arbitrary numeric scores. If scores are requested, explain the scale and weights, mark judgments as subjective, and avoid false precision. Leave unknowns unknown.
- For paid or self-hosted options, estimate realistic costs for the user's workload. If workload is unknown, state small and growth scenarios in explicit units. Distinguish confirmed prices from estimates, cash costs from setup/maintenance effort, and introductory allowances from ongoing usage.
- Identify the best option to use now and the best option to learn when they differ. Recommend complementary tools only when needed for the task. Explain why the winner beats its closest credible rival.
- Check whether the choice changes under a tighter budget, greater scale/performance, or stronger learning/career priorities. Report meaningful changes rather than invent a winner for every niche.
- Stop when discovery coverage is adequate and additional evidence is unlikely to change the decision. Do not prolong research solely to create a larger report.

## 5. Deliver a clear decision

Research deeply; write concisely. Lead with the recommendation and the decisive reason. Show the verification date and the assumed use case near the top.

Then provide:

1. A compact ranked comparison covering all viable mainstream contenders in scope. Use columns such as option, best use, capability/performance, cost/value, learning value, and main tradeoff. Split by subcategory when needed; do not rank complementary tools as substitutes.
2. A short explanation of the top choices, especially why the winner beats the runner-up. Include the strongest drawback of the recommendation and material evidence gaps.
3. A concise list of screened-out notable options with specific reasons, if applicable. Keep them distinct from viable but lower-ranked options.
4. The recommended next action: one starting tool or a minimal combination, a useful first task, and a concrete condition for switching or adding another tool.

- Cite current factual claims close to the relevant text, including pricing, adoption, and performance. Make assessments traceable to evidence without flooding the answer with source lists.
- Put detailed cost arithmetic or extensive coverage notes after the decision only when needed. Honor requested brevity and provide fuller reports when requested.
- Do not install software, subscribe, create accounts, or modify a project merely to make a recommendation. Act on implementation only when requested.
