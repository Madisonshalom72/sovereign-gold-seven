# SOVEREIGN GOLD SEVEN (SG7)
## Programmable Money for the Agent Economy — Authorized, Identity-Verified, Settled in Nano-Amounts

**White Paper — Concept Draft v0.1 · October 2026**
**Status: CONCEPT / PAPER STAGE ONLY. No token has been issued. Nothing in this document is an offer to sell a security or any other asset. See Section 10 (Risks & Disclaimers) before reading anything else as fact.**

---

## 1. Abstract

The next economy will not be run by people clicking "buy." It will be run by AI agents — software acting on behalf of humans — requesting data, hiring other agents, paying for services, and moving money thousands of times a day in amounts too small for today's payment rails.

That economy has two unsolved problems. First, **money that was designed as a joke**: the most famous "agent-era" coin, Dogecoin, is a meme with no identity layer, no authorization layer, and no native utility — its value rests on attention alone. Second, **agents that cannot prove who sent them**: in September 2026, Amazon blocked Meta's Muse shopping agent from its marketplace because the agent could not reliably prove whose behalf it was acting on or what that person had actually approved. The industry's own verdict, in four words: **access is not authority.**

Sovereign Gold Seven (SG7) is a concept for the opposite design: a **programmable coin for the agent economy** in which every agent transaction is (a) **identity-verified and human-authorized** under the x401 pattern — the owner's wallet signs the exact terms, and if an agent changes the amount, the recipient, or any signed term, the signature no longer validates; (b) **settled in nano-amounts** over an x402-style pay-per-claim rail built for machine-speed micropayments; and (c) **gated by the issuer's own nanobot swarm** — there is no public sale in this design; the coin is acquired only by acquiring and running Alice's nanobots, and it is useful on day one as an access key across a real, already-operating ecosystem of products — AI agents for local businesses, an AI news station, sovereignty education, and local services — rather than a promise of future utility.

This paper describes the concept, the utility design, the bot-gated distribution model, the ecosystem it plugs into, proposed (not final) token parameters, and — plainly — the risks, the legal gate that stands before any issuance, and the facts a reader must not mistake for promises.

---

## 2. The Problem

### 2.1 Meme money has no floor of usefulness

Dogecoin and the meme coins that followed it proved that a community and a ticker can move markets. They did not prove anything else. A meme coin:

- has **no identity layer** — nobody, human or agent, proves anything about who is transacting or why;
- has **no authorization layer** — possession of a key is the only "permission" that exists, so a compromised or rogue agent spends exactly like an honest one;
- has **no native utility** — it buys nothing inside any product its issuer operates, because there is no product;
- depends entirely on **continued attention**, the one resource that reliably disappears.

Attention is a marketing asset. It is not a monetary design.

### 2.2 Agents are being handed money with no authority model

AI agents are already shopping, booking, quoting, and paying. In September 2026 the structural flaw surfaced in public: Meta released its Muse assistant (which reached No. 1 on the U.S. App Store, with Shopify connecting Shop Pay), and within weeks Amazon blocked Muse from its marketplace, citing concerns that the agent did not adequately identify itself or demonstrate that the person it acted for had authorized what it was doing.

In the same month, FinCEN and federal banking regulators issued guidance recognizing digital certificates and verifiable credentials — under certain conditions — as a permissible way for banks to verify customer identity. The direction of travel is unmistakable: **the agent economy will run on verified identity and provable authorization, or it will not be allowed to run at all.**

On October 15, 2026, the company Proof put that model into production with **x401**, an open protocol that lets any website ask an AI agent to prove who it is acting for and what that person approved — backed by an agent identity wallet in which the person approves, on their own device, exactly what their agent may do, and signs it. Change the amount, the recipient, or any signed term afterward, and the signature breaks.

### 2.3 Today's rails are the wrong size

Card networks and bank rails were built for human-sized, human-speed purchases. An agent economy clears thousands of claims worth fractions of a cent — an API call, a data claim, a per-article read, a per-route quote. Fees and settlement times designed for $40 purchases cannot carry $0.004 claims. The x402 pattern — paying per claim over ordinary HTTP — exists precisely to close this gap.

**The problem, in one line:** the agent economy is arriving with joke money, anonymous agents, and oversized rails. SG7 is designed against all three.

---

## 3. The Asset

**Sovereign Gold Seven (SG7)** is a proposed programmable digital asset with four defining properties:

1. **Authorization is native, not bolted on.** SG7 transactions initiated by agents are designed to carry an x401-pattern authorization: a signed mandate from the asset owner specifying who the agent acts for, what it may do, and within what limits. A transaction outside the mandate is not merely discouraged — it fails verification.
2. **Settlement is nano-native.** SG7 is designed to move in amounts as small as a fraction of a cent over an x402-style pay-per-claim rail, so agents can pay for single claims, calls, and actions without batching, accounts, or card minimums.
3. **Utility precedes speculation.** SG7 is designed as an access and settlement key inside an ecosystem that already exists and already sells products (Section 6). The coin's usefulness does not depend on a future roadmap being believed; it depends on products that are live today choosing to honor it.
4. **Access is gated by the swarm.** SG7 is designed to be acquired only through an active deployment of the issuer's nanobots (Section 4.5). The bots are the front door: no swarm, no coin. Distribution is a product relationship, not an open-market sale.

**On the word "Gold":** gold in the name is brand and treasury *policy* (Section 4.4), not a redemption promise. SG7 is **not** redeemable for gold, is **not** presently backed by gold, and Section 10 states this again in plain language. Any reserve would exist only if and when it is built, disclosed, and independently verifiable.

---

## 4. Utility — The Five Pillars

### 4.1 Pillar One: Authorized Money

The owner of SG7 sets **programmable spending mandates** for their agents: signed instructions that define, in advance, what an agent may do with money — maximum amount per transaction and per day, approved categories of counterparty, approved purposes, expiry. The agent transacts freely *inside* the mandate and cannot transact outside it, because every spend carries the owner's signature over the exact terms (the x401 pattern). If the agent — buggy, compromised, or manipulated — alters the amount, the recipient, or any term, the signature no longer validates and the payment does not settle.

This is the structural answer to the Amazon–Muse problem: not "trust the agent," but "the agent can only ever show you a signed instruction from its human."

### 4.2 Pillar Two: Agent Settlement

Agents increasingly need to pay *each other*: a receptionist agent buying a data claim, a content agent paying a research agent, a quoting agent paying for a measurement. SG7 is designed as the settlement asset for these machine-to-machine nano-payments, with **verified identity on both ends** — each side's agent presents the identity and mandate of the principal it acts for. Settlement between strangers becomes possible without accounts, invoices, or card rails, and without anonymity: both principals are identified, both mandates are signed, both limits are enforced by the rail itself.

### 4.3 Pillar Three: Ecosystem Access

SG7 is designed to function as an **access key** across the issuer's operating ecosystem (Section 6): tiered access to AI agent services, the AI News Daily station's premium layers, sovereignty and business training, and local services. Holding or spending SG7 inside these products is the coin's demand floor — utility that exists whether or not any exchange ever lists it. Access tiers, thresholds, and pricing are business decisions to be published by each product, and may change; the *design commitment* is that the ecosystem honors the coin from the start rather than retrofitting utility after a sale.

### 4.4 Pillar Four: Treasury Discipline — the Gold Policy

The project adopts a **gold-referenced treasury policy**: the stated long-term policy is to build and hold a treasury reserve referenced to physical gold, acquired from ecosystem revenue according to a published schedule, held with a disclosed custodian, and reported on a regular cadence if and when such a reserve exists.

Read this precisely:

- This is a **policy and an aspiration**, not a backing. As of this paper, **no gold reserve exists, no coin is redeemable for gold, and no holder has any claim on gold.**
- The gold theme expresses a monetary philosophy — discipline, scarcity, and an anchor outside pure attention — and a treasury *target*. Targets can be missed, delayed, or abandoned; Section 10 covers this.
- If a reserve is ever established, its existence, custodian, and verification method will be disclosed in writing at that time, and not before claims are made about it.

---

## 5. How It Works (Plain English)

### 5.1 The signing flow (x401 pattern)

1. **You set the rules once.** In your wallet, you approve a mandate for your agent: who it acts for (you), what it may buy, from whom, up to what amount, until when. You sign it on your own device.
2. **Your agent goes to work.** When it needs to pay — say, a fraction of a cent for a data claim — it presents its mandate and a payment request stating the exact amount, recipient, and purpose.
3. **The other side checks the signature.** The receiving service verifies: Is this agent acting for a real, identified person? Did that person actually approve *these* terms? Is the amount inside the signed limits?
4. **Tampering breaks it.** If anything about the request differs from what was signed — a changed amount, a swapped recipient — the signature no longer validates, and the payment does not happen. No phone call, no chargeback, no argument: the math refuses.

### 5.2 The nano rail (x402 pattern)

Payments ride an x402-style pay-per-claim rail: a service names a tiny price for a single claim (one API response, one verified data point, one article, one action); the agent's wallet pays that exact amount over ordinary web requests; the service delivers instantly. No subscriptions to manage, no minimums, no invoices. The working demonstration of this pattern — identity check plus nano-payment, in the browser — already runs in the project's own Alice NanoPay Bots lab.

### 5.3 A worked example

A contractor's AI receptionist (an Alice agent) needs a verified property measurement to quote a job. It requests the measurement from a data service. The service quotes $0.006 for the claim. The receptionist's mandate — signed by the contractor — allows data purchases up to $0.50 per day from approved services. The claim is inside the mandate, identity verifies on both ends, six-tenths of a cent settles instantly, and the quote goes out. Total human involvement: the signature given once, days earlier. Total time: seconds. Total paperwork: none.

---

## 6. Ecosystem Map — The Coin Plugs Into Products That Already Exist

The competitive claim of SG7 is not a whitepaper promise. It is that the issuing ecosystem is **already built and operating**:

| Property | What it is | SG7's designed role |
|---|---|---|
| **Alice AI Office Hub** (aliceaihub.xyz) | AI agents for local businesses — receptionists, estimators, follow-up, reputation, content agents; live storefront with subscription plans and a $1 trial | Access + settlement: agent tiers honored in SG7; agents settle nano-claims in SG7 |
| **Alice NanoPay Bots** (live lab) | Interactive lab demonstrating the x401 signing flow and the x402 nano-payment pattern | The public proof-of-concept for Pillars 1 and 2 |
| **AI News Daily** | An AI news station — daily editions, newspaper-style hook ads, video wire — "brought to you by Alice" | Access: premium station layers, archives, and features keyed to SG7 |
| **Private Money Rights Playbook & Founders** | Sovereignty/UCC education, the Private Money Rights Playbook, and the application-only Founders Program | Access: training and program tiers honored in SG7 |
| **Capital 7 Logistics** | A real, operating local services company (moving, handyman, gutter services) in Luzerne County, PA | Access/settlement pilot: a physical-world business inside the same system |

Most token projects promise an ecosystem later. This one starts from an ecosystem and adds the coin. That inversion — **utility first, asset second** — is the core of the design.

---

## 7. Token Design — Proposed Parameters

> **Everything in this section is a PROPOSAL for discussion, not a final specification and not a promise.** Final parameters, if the project ever proceeds past the legal gate (Section 9), will be published in a superseding document. No parameter here creates any right or expectation.

- **Supply (proposed):** a fixed, capped supply with no inflationary minting after issuance. A cap in the range of **77 million** is proposed, keeping the Seven motif (77,000,000) while remaining scarce relative to meme-coin supplies printed in the hundreds of billions. Final figure to be set at design lock.
- **Distribution (proposed):** allocations across ecosystem treasury, public circulation, team/founder vesting, and a reserve fund — with vesting and lock periods for insider allocations published before any circulation. No allocation figure is final in this draft.
- **The Seven Standard rate (proposed):** ecosystem access is denominated at **seven coins to the dollar — $1 = 7 SG7** — for bot-gated acquisition and in-ecosystem service pricing (e.g., a $29/mo swarm service is a 203 SG7 service). The rate is the house conversion standard inside the ecosystem, in keeping with the Seven motif; it is an access/pricing parameter of the ecosystem, **not** a market price, a redemption promise, or a valuation. Arithmetic note (illustration only): at the proposed 77,000,000 cap, full distribution at the Seven Standard rate corresponds to $11,000,000 of ecosystem throughput — a measure of the design's scale, not a forecast.
- **Burn (proposed concept):** a portion of ecosystem fees collected in SG7 *may* be permanently burned on a published schedule, introducing deflationary pressure tied to real product usage rather than speculation. A burn is a design concept under consideration — it is not scheduled, not guaranteed, and would only ever be described factually after it occurs.
- **Fees (proposed concept):** a small settlement fee on rail transactions, directed to ecosystem operations and the treasury policy in Section 4.4. Rate not set in this draft.
- **Governance (proposed):** no governance rights are promised. If any holder-input mechanism is ever introduced, it will be described in its own document at that time.

**Deliberately absent:** any statement about price, listing, exchange availability, yield, or return. None is made anywhere in this paper, and none should be inferred.

---

## 8. Competitive Advantage

### 8.1 Versus DOGE and the meme coins

| Dimension | Meme coins (e.g., DOGE) | SG7 (as designed) |
|---|---|---|
| Reason to exist | A joke that caught attention | Settlement + access in an operating ecosystem |
| Identity layer | None | x401-pattern verified identity on agent transactions |
| Authorization | Key possession only | Signed human mandates; tampering breaks the signature |
| Native utility | None — buys nothing its issuer runs | Access key across live products from design day one |
| Payment size fit | Retail speculation amounts | Nano-amounts native — built for per-claim machine payments |
| Scarcity | DOGE is inflationary by design | Proposed fixed cap (77M concept) |
| Anchor story | A dog | Sovereignty, gold-policy discipline, and the Seven brand |

DOGE's advantage is fame. Fame is real, and this paper does not pretend otherwise — but fame is the *only* advantage, and it belongs to whoever holds attention this week. SG7's bet is that when agents start moving serious money, the market will pay for the coin whose transactions can **prove who authorized them**. Beating a meme does not require being funnier. It requires being *usable for the thing the economy actually needs next*.

### 8.2 Versus plain stablecoins

Stablecoins are excellent digital dollars — and deliberately featureless. A stablecoin can settle a nano-payment, but it carries no native mandate system (the authorization must be built elsewhere), no ecosystem access function, and no treasury discipline beyond its peg. SG7 does not compete with stablecoins as a dollar substitute; it is designed as the **authorized-agent layer** stablecoins lack: mandates, identity, and ecosystem utility wrapped around settlement. In practice the two can coexist — the rail pattern is asset-agnostic — but only one of them is designed, end to end, for agents acting under signed human authority.

### 8.3 The moat

The moat is not the token contract; anyone can copy a contract. The moat is the combination: (1) an **operating ecosystem** that honors the coin, (2) a **brand** (Sovereign / Seven / gold) with years of content and community already attached to it, and (3) an **authorization-first design** aligned with where regulators and platforms demonstrably moved in September–October 2026. Copying any one is easy. Copying all three, already assembled, is the work of years.

---

## 9. Roadmap — With the Legal Gate First

- **Phase 0 — Concept (current).** This paper. Name, brand, and trade dress development. Ecosystem continues operating and growing without the coin. Community discussion.
- **Phase 1 — Design lock.** Finalize token parameters, mandate specification, and rail integration design against the live NanoPay pattern. Publish a superseding specification.
- **Phase 2 — LEGAL REVIEW GATE.** Independent legal review of the entire design — securities law, money transmission, tax, and consumer-protection analysis in every jurisdiction the project would touch — **must be completed, and its conclusions satisfied, before any issuance, sale, or distribution is even scheduled.** If the review says the design cannot proceed as drawn, the design changes or the project stops. **There is no issuance before this gate. There are no exceptions to this gate.**
- **Phase 3 — Test deployment.** Non-transferable test assets on a test network; mandate and settlement flows exercised against the live ecosystem in sandbox form.
- **Phase 4 — Issuance decision.** Only after Phases 1–3, a separate written go/no-go decision, with final parameters, disclosures, and compliance measures published in advance.

No dates are attached to any phase. A roadmap with dates would be a promise; this is a sequence.

---

## 10. Risks & Disclaimers — Read This Section Twice

1. **Concept stage.** SG7 does not exist. No token has been issued, sold, or distributed. This paper is a design document, not an offering document.
2. **No returns are promised or implied.** Nothing here is a prediction of price, value, demand, or profit. Anyone who tells you SG7 will be worth any amount is not speaking for this document.
3. **Not gold-backed.** SG7 is not redeemable for gold. No gold reserve exists today. Section 4.4 describes a *policy target* for a future treasury, which may never be established. The word "Gold" in the name is branding and philosophy, not collateral.
4. **Legal gate.** Tokenization is gated on independent legal review (Phase 2). Digital assets are subject to securities, commodities, money-transmission, tax, and consumer-protection law, which varies by jurisdiction and changes frequently. The design may be altered, delayed, or abandoned to comply.
5. **Regulatory uncertainty.** The x401/x402 patterns and agent-identity frameworks referenced here are recent (October 2026) and evolving; standards, platform policies, and regulatory positions may change in ways that help or harm this design.
6. **Technology risk.** Smart contracts, wallets, and payment rails carry bug, exploit, and key-loss risk. A mandate system reduces authorization risk; it does not eliminate custody risk. Lose your keys, lose your assets — that remains true here.
7. **Market risk.** If issued, a token could lose some or all of its value, could be illiquid, and could fail to be listed or supported anywhere. Ecosystem access utility depends on the continued operation of the ecosystem's products, which are businesses subject to ordinary business risk.
8. **No affiliation.** This project is not affiliated with, endorsed by, or connected to Proof (the company behind x401), Meta, Amazon, Shopify, or any other company named in this paper as context. References to x401 and x402 describe open protocol *patterns* the design is modeled on.
9. **Forward-looking statements.** Everything in Sections 4–9 describes intentions and designs as of October 2026. Intentions change. Only facts stated in the present tense about the existing ecosystem (Section 6) are represented as current, and even those describe businesses that can change their offerings at any time.

---

## 11. Closing

The agent economy will have money. The only question is what kind: money that began as a joke and can prove nothing — or money designed, from the first line, so that every agent who touches it can prove **who sent it, what its human approved, and that nothing was changed along the way.**

Sovereign Gold Seven is the second kind — proposed, on paper, honestly gated, and plugged into products that already answer phones, book jobs, publish the news, and teach the system. Tiny payments. Verified agents. Your signature, or it doesn't count.

---

*Sovereign Gold Seven (SG7) — Concept White Paper v0.1 · October 2026 · Paper stage only · No token issued · Legal review precedes any issuance*
