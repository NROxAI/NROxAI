# Carlos Nogueira

### Electrical engineer, building in AI in the open

I trained as an electrical engineer, then found that working in industry meant building what other people wanted built. So I made my own specialty instead: for ten years I ran an automation company, delivering residential and commercial projects, and I assembled that expertise course by course — choosing what to learn, and when, and how, as I went. I hold an MBA.

I am doing the same thing again with AI. Not through a research degree: I would rather stay broad and build things that ship than narrow down to defend a thesis. Outside work I study for the pleasure of it — science, mathematics, music, film. None of that is what I do for a living; it is simply why I have never waited for someone to offer a course before starting to learn something.

So I am studying deliberately, building in public, and publishing the tools I build along the way.

---

## What I am building

**Business Project Manager (BPM)** — an open framework that gives AI-assisted projects the governance layer they usually skip.

<p align="center">
  <img src="assets/bpm-architecture.svg" alt="BPM architecture: Second Brain, Dual-Track and immutable decision records" width="100%" />
</p>

It did not start as a framework. It started because I was losing work. Context from one AI session would not survive into the next: decisions we had already settled came back up for debate, the reasoning behind them disappeared, and I kept re-explaining the same project from the beginning. So I started writing decisions down in a fixed shape, and handing a written baton from each session to the next.

Only afterwards did I find out that what I had arrived at by intuition already had names and a literature behind it — architecture decision records, progressive summarisation, the separation of build from run. BPM is the result: something learned by losing projects, then reconciled with the people who had formalised it first.

It does three concrete things:

* **Separates engineering decisions from business ones.** Technical choices are recorded as ADRs, operational and commercial choices as ODRs, so a pricing call never quietly rewrites the architecture.
* **Freezes a decision once it is made.** Context, rejected alternatives and trade-offs are written down, so the next session inherits the conclusion instead of reopening the debate.
* **Carries context across sessions.** Session minutes distil into a handoff, and the handoff into a boot register that the next session reads first — no amnesia, no re-explaining the project from scratch.

Version 1.0.0. Early, opinionated, and open to being argued with. The repository is temporarily private while I rework its structure, and will be public again shortly.

---

## Why this, rather than another coding tool

Most people who pick up AI build the product and neglect the business around it. Having run one, I know the product is the smaller half. A project that actually survives also needs a brand, a registered trademark, domains and email that belong to the company rather than to a person, legal footing in the markets it sells into, and decisions that outlast whoever made them.

BPM exists because AI assistants are very good at the visible half and blind to the rest.

---

## What I am currently learning

* Building software with AI coding assistants, and finding where that approach holds up and where it quietly falls apart.
* Designing and orchestrating agents — getting several of them to do useful work without losing the thread between them.
* Workflow automation with n8n, and judging when an automated flow is the right answer instead of code.
* Taking small applications end to end, from an idea to something that actually runs.

---

## Background

* Electrical engineer.
* Ten years running my own automation company, delivering residential and commercial projects.
* MBA in Business Administration.
* **EMPRETEC** — the United Nations entrepreneurship programme (UNCTAD), delivered in Brazil by SEBRAE and built on David McClelland's Harvard research into entrepreneurial behaviour.
* Brazilian. I work in English and Portuguese, which is why BPM treats Brazilian and US legal ground as two separate concerns rather than one.

---

Open to conversations about governance for AI-assisted work, and to contributions on BPM.
