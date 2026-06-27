# Project Brief – Milestone-Based Crowdfunding Platform

## Vision

Create a transparent crowdfunding platform that enables individuals to receive financial support for achieving meaningful goals through milestone-based funding.

Unlike traditional crowdfunding platforms where funds are transferred immediately, contributions are held securely until predefined milestones are completed and approved by contributors.

The first implementation of the platform will be my own personal journey toward becoming an independent freelance software engineer and relocating to Thailand.

The long-term vision is to evolve this into a reusable platform that anyone can use to fund life-changing goals while maintaining transparency and accountability.

---

# Core Philosophy

The project is not about asking people to "trust me."

It is about asking people to trust a transparent process.

Supporters always know:

* what they are funding
* why the funding is needed
* how progress is measured
* when milestones are completed
* what evidence is provided
* how funds are released

Trust should come from transparency rather than promises.

---

# Project Goals

The platform should allow a project owner to:

* Define a long-term mission.
* Break the mission into milestones.
* Specify funding requirements for each milestone.
* Describe measurable success criteria.
* Receive contributions.
* Submit evidence of completion.
* Allow contributors to approve or reject milestones.
* Release funds only after approval.
* Refund contributors if milestones fail.

---

# Initial Use Case

Mission

Become a self-employed software consultant within 12 months and relocate to Thailand.

Example milestones

## Milestone 1

Professional Portfolio Website

Funding Goal

€400

Success Criteria

* Portfolio website published
* Contact page
* Services page
* GitHub integration
* Responsive design

Evidence

* Website URL
* GitHub repository

---

## Milestone 2

Blockchain Portfolio Project

Funding Goal

€700

Success Criteria

* Smart contract completed
* Frontend completed
* Unit tests
* Documentation
* Video demonstration

Evidence

* GitHub repository
* Live deployment
* Demo video

---

## Milestone 3

Acquire First Freelance Client

Funding Goal

€1000

Success Criteria

* Signed client contract
* First invoice issued

Evidence

* Documentation where appropriate
* Public progress update
* Optional testimonial

---

## Milestone 4

Relocation to Thailand

Funding Goal

€3500

Success Criteria

* Visa obtained
* Accommodation arranged
* Working environment established

Evidence

* Relevant documentation where appropriate
* Photos
* Progress report

---

# Smart Contract Philosophy

The blockchain should provide trust.

The blockchain should not replace communication.

Smart contracts should only manage:

* Contributions
* Escrow
* Voting
* Fund release
* Refunds

Everything else belongs in the web application.

---

# Smart Contract Workflow

Campaign Created

↓

Contributors deposit funds

↓

Funds remain in escrow

↓

Milestone owner submits evidence

↓

Contributors review evidence

↓

Voting period begins

↓

Approved?

YES

↓

Funds released

NO

↓

Refund contributors

---

# Website Goals

The website should feel personal rather than financial.

Navigation

Home

Mission

Roadmap

Milestones

Progress Updates

Support

About

Dashboard

---

# Dashboard

Supporters should immediately understand:

Mission progress

Funding progress

Completed milestones

Current milestone

Latest updates

Voting opportunities

Evidence

Trust score

---

# Progress Updates

Transparency is one of the platform's biggest features.

Instead of disappearing after receiving funding, the project owner regularly publishes updates.

Examples

Week 1

Finished backend architecture.

Week 2

Completed smart contract tests.

Week 3

Portfolio website launched.

Week 4

Applied to twenty freelance opportunities.

Week 5

Completed first client interview.

Supporters can follow the journey in real time.

---

# Evidence

Evidence should be public whenever possible.

Examples

GitHub repository

Website

Demo video

Blog article

Screenshots

Technical documentation

Progress report

Supporting documentation when appropriate

---

# Voting

Version 1

One contributor

One vote

Milestone approved if

* Approval threshold reached
* Minimum participation reached

Future versions may support weighted voting.

---

# Trust Score

Instead of measuring popularity, the platform measures reliability.

Possible metrics

Completed milestones

On-time completion

Contributor participation

Successful approvals

Refund history

This becomes the public reputation of the project owner.

---

# Long-Term Vision

Today's platform supports one creator.

Tomorrow it could support:

Students

Artists

Entrepreneurs

Open-source maintainers

Freelancers

Researchers

Anyone pursuing a meaningful goal that benefits from transparent, milestone-based funding.

---

# Technical Architecture

Frontend

Next.js

React

TypeScript

Tailwind CSS

Wallet connection

Responsive UI

Backend

Node.js

REST or GraphQL API

Authentication

Notifications

Evidence storage

Database

PostgreSQL

Prisma

Blockchain

Solidity

Foundry

OpenZeppelin

Sepolia for testing

Ethereum Mainnet or Layer 2 for production

Storage

IPFS for immutable evidence

Cloud storage for media if needed

Deployment

Vercel

Railway

Docker

GitHub Actions

---

# MVP Scope

Smart Contract

Create campaign

Contribute

Escrow

Submit evidence

Vote

Withdraw

Refund

Frontend

Mission page

Roadmap

Milestones

Wallet connection

Contribution flow

Voting interface

Dashboard

Backend

User profiles

Progress updates

Evidence management

Notifications

---

# Repository Structure

/apps

```
frontend

backend
```

/packages

```
smart-contracts

ui
```

/docs

```
architecture.md

roadmap.md

smart-contract.md

api.md

frontend.md

backend.md

product.md

user-stories.md
```

---

# Development Roadmap

Phase 1

Architecture

Documentation

Wireframes

Phase 2

Smart Contracts

Testing

Deployment

Phase 3

Backend APIs

Authentication

Database

Phase 4

Frontend

Wallet Integration

Dashboard

Phase 5

Evidence Submission

Voting

Notifications

Phase 6

Public Beta

Collect feedback

Improve UX

---

# Guiding Principles

Transparency over trust.

Simple before clever.

Security before convenience.

Clear communication over unnecessary decentralization.

Build a platform that solves a real problem before making it generic.

Every feature should answer one question:

"Does this make supporters feel more confident that meaningful progress is being made?"

