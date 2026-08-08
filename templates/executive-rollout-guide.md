# Executive AI Rollout Guide

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

Use this to move from interest to a governed first rollout.

## Phase 1: Direction

- Name the executive sponsor.
- Appoint and resource the AI programme owner.
- State the one-sentence outcome.
- Define risk appetite.
- Name the policy/tool owner.
- Decide what data is off-limits in public tools.
- Plan the executive, functional-leader, and team communication cascade.

Use the shared [AI Programme Owner Charter](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/templates/ai-programme-owner-charter.md) and this repo's [Executive AI Communications Cascade](executive-communications-cascade.md).

## Phase 2: Map

- Run the readiness assessment.
- Identify existing unofficial AI use.
- List current AI tools.
- Identify high-risk areas.
- Identify one low-risk Improve workflow per function.

## Phase 3: Guardrails

- Adopt ground rules or policy.
- Create an approved-tool register.
- Define public vs approved tool rules.
- Set customer-facing review requirements.
- Set incident reporting route.
- Confirm a Data Processing Agreement is in place for every tool touching personal data.

**On that last point.** Where your organisation decides what personal data is processed and why, you are the controller and the vendor is the processor, and the written contract between you is normally a Data Processing Agreement. The accountability is yours, not the vendor's, which is why this belongs in guardrails rather than in procurement's inbox.

Two things leaders get caught by. Free and consumer tiers generally come with no DPA, so a tool that spread through the team informally is usually unapprovable on contract grounds alone, whatever its privacy policy says. And existing suppliers that have bolted AI onto an established product may be operating under paperwork that predates the AI features entirely, so an old DPA is not evidence that the new processing is covered.

Full question set, including role mapping and sub-processors: [procurement due diligence](https://github.com/VictorOsondu/ai-governance-kit/blob/main/procurement/procurement-due-diligence.md).

## Phase 4: Pilot

- Choose one low-risk workflow.
- Name the owner.
- Train the users.
- Record prompts, checks, and outputs.
- Measure time, quality, risk, and user confidence.

Use the shared [AI Pilot Brief](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/templates/ai-pilot-brief.md) so the baseline, controls, stop conditions, feedback, and final decision are agreed before the pilot starts.

## Phase 5: Cascade

- Name champions.
- Give them time and boundaries.
- Share safe examples.
- Gather questions and near misses.
- Update training and policy.
- Create a community rhythm for peer questions and demonstrations.
- Move tested workflows into an approved use-case library.

Use the shared [Community of Practice Starter](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/scaling/community-of-practice-starter.md) and [Approved AI Use-Case Library](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/templates/approved-use-case-library.md).

## Phase 6: Sustain

- Add AI direction, approved tools, data rules, output review, and support routes to new-joiner onboarding.
- Review role-based learning and refresher needs.
- Review whether champions and the programme owner have enough capacity.
- Retire stale examples, tools, and guidance.

Use the shared [AI Onboarding Checklist](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/templates/ai-onboarding-checklist.md).

## Phase 7: Board Review

Report:

- value returned
- where saved time went
- risks and incidents
- approved tools and high-risk uses
- training coverage
- decisions needed

Use the shared [AI Adoption Measurement Framework](https://github.com/VictorOsondu/ai-adoption-toolkit/blob/main/measurement/adoption-measurement-framework.md) for optional reach and integration diagnostics. Keep value, risk, workforce experience, and decisions ahead of activity counts.

## Stop Conditions

Pause or escalate if:

- confidential or personal data enters an unapproved tool
- customer-facing output creates risk
- AI is shaping decisions about people
- a vendor changes data handling
- a workflow depends on unverifiable output
- users are bypassing policy because approved tools are unusable
