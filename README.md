# Pulse AI Workplace

Pulse is an editor-native operating system for AI-assisted software work. It is
not a task list, a chat wrapper, or a static project dashboard. Pulse is built to
run the workday: assign agents, keep the board truthful, preserve evidence, route
reviews, and move launch work through proof-backed gates.

The product source is proprietary. This public repository exists so developers
can understand what Pulse does and find the canonical public surfaces without
exposing private implementation history.

## What Pulse Does

Pulse coordinates the full loop of agentic product work:

- **Plan the work** with action items, priorities, dependencies, sprint context,
  launch pillars, due dates, owners, and review states.
- **Run the workday** from one command surface that shows queue pressure, active
  sessions, blockers, review load, and launch readiness.
- **Dispatch agents** through role selection, skill loading, pool rules,
  validation expectations, and git receipts.
- **Capture proof** with build output, runtime evidence, screenshots, review
  notes, presentations, narration, and source-truth links.
- **Preserve memory** through Knowledge Items that keep decisions, artifacts,
  research, and prior remediation available to the next agent.
- **Ship through gates** that connect product readiness, website readiness,
  billing, support, legal, docs, listing, and launch content.

## Core Surfaces

### Workday

Workday is the operator surface. It answers: what is running, what is blocked,
what needs review, what is next, and whether the launch room has enough pressure
on the right work.

Typical Workday state includes:

- active dispatch slots
- queued and blocked items
- review-ready tasks
- current sprint focus
- launch blockers
- daily operating notes

### Action Board

The board is the source of truth for work state. Items carry more than titles:
owner, priority, dependencies, timestamps, validation notes, deliverable links,
review status, and completion evidence.

Pulse treats board state as operational truth, not decoration. If a task says it
is done, the evidence has to agree.

### Dispatch System

Dispatch turns work into accountable agent execution. Agents are expected to
adopt roles, load relevant skills, read prior context, inspect source state,
make narrow changes, validate them, commit, push, and leave a receipt.

Dispatch exists so agent work does not disappear into terminal history.

### Roles and Skills

Pulse uses roles and skills to keep work bounded:

- product roles define judgment and scope
- engineering roles define implementation responsibility
- review roles define approval standards
- skills encode repeatable workflows, quality bars, and known failure modes

This is how Pulse prevents every agent from acting like a generic coding helper.

### Knowledge Base

Knowledge Items preserve the project memory that usually gets lost between
sessions. They hold research, launch decisions, audit results, presentations,
narration, screenshots, validation output, and remediation notes.

The goal is simple: the next agent should not have to rediscover what the last
agent already proved.

### Review and Proof Gates

Pulse review is evidence-based. A reviewer checks the actual diff, source state,
runtime behavior, acceptance criteria, regressions, missing tests, and whether
the board and Knowledge Item agree with reality.

Approval is not a rubber stamp. It is a release-control step.

### Launch Operations

Pulse tracks launch readiness across the real surfaces that matter:

- extension runtime
- website and docs
- billing and account flows
- support and legal pages
- Marketplace/listing readiness
- content packages
- changelog/status/release notes
- evidence that each claim is live, current, and supportable

## Public Links

- Website: https://pulse-ai.dev
- Documentation: https://pulse-ai.dev/docs
- Help center: https://pulse-ai.dev/help
- Research: https://pulse-ai.dev/research
- Contact: https://pulse-ai.dev/contact
- Privacy: https://pulse-ai.dev/privacy
- Terms: https://pulse-ai.dev/terms
- Support email: support@pulse-ai.dev

## Extension Listing

The public Marketplace link is intentionally withheld until the live listing URL
is verified. Pulse will not publish or repeat an inferred Marketplace URL from
package metadata or internal release artifacts.

## Repository Scope

This repository contains only the static GitHub Pages site for the public
developer doorway:

- `index.html`
- `styles.css`
- public-facing image assets

It does not contain the Pulse product source code, board data, launch records,
private Knowledge Items, customer data, or operational history.

## Ownership

Pulse AI Workplace is proprietary software by IZA NOIR LLC.
