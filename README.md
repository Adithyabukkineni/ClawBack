# ClawBack

**Get back the tariff money you quietly paid for your buyers.**

When US tariffs hit, many Indian exporters cut their prices to keep their buyers happy. The buyers then got the tariff refunds, and the exporters got nothing. ClawBack helps you work out exactly how much you absorbed, prove it with your own documents, and ask for it back in a way a buyer can't easily wave off.

It reads your invoices, price-revision emails, and bank realization documents, does the math the same way every time, and turns the result into a claim you can actually send.

> ClawBack is a negotiation tool, not a chatbot. AI reads your documents. Plain, deterministic code does the arithmetic. Every number can be traced back to the line it came from.

---

## What it does

### Absorption Ledger
Drop in your invoices, price-revision emails, and bank receipts. ClawBack pulls out the details that matter:

- Buyer
- Invoice number
- Date
- HS code
- Quantity
- Original price
- Revised price
- Incoterm
- Amount realized

From those, it calculates:

- Tariff paid by the buyer
- Tariff cost absorbed by you, the exporter
- Absorption ratio
- Fair claim amount
- Proportional interest

Tariff rates come from a dated IEEPA lookup table, so each shipment is matched to the rate that applied on its date.

### Click-to-Proof Provenance
Every important figure in the ledger is clickable. Click it and the original document opens with the exact supporting line highlighted. Each extracted field carries a confidence badge, so you know what to double-check. If something was read wrong, correct it by hand and the whole ledger recalculates.

### IOR Triage
ClawBack detects the Incoterm on each shipment and sends it down the right path:

- **DDP** shipments go toward the direct CBP claim route.
- **FOB / CIF** shipments continue through the negotiation workflow.

### Refund Clock
Estimates when your buyer's tariff refund probably landed, shows the timeline, and tracks the interest building up since then. It makes the cost of waiting visible.

### Claim Pack
Generates a negotiation-ready claim document with:

- Cover letter
- Claim summary
- Absorption ledger
- Exhibit numbers
- Source-document references
- Evidence annex
- Settlement options

### Settlement Ladder
Gives the buyer more than one way to say yes:

- Full cash credit note
- 50/50 settlement
- Credit applied to the next order's invoice

### Portfolio Dashboard
See what's recoverable across all your buyers in one place. Buyers are ranked by recoverable amount and by leverage, which takes into account:

- Share of your revenue
- Length of the relationship
- Open orders

### Objection Handler
Buyers push back. ClawBack answers with rules-based responses tied to your own ledger evidence, covering the usual objections:

- "We passed the cost on to retail."
- "It was FOB, so it's not your concern."
- "We haven't received the refund yet."
- "The discount was for volume, not the tariff."

### Recovery Pipeline
A Kanban board for your claims: **Drafted → Sent → Countered → Settled**. Each card shows the recovery amount in INR.

### Buyer Response Portal
Generates a shareable, buyer-facing page with the claim summary and supporting information. Buyers can review the settlement options and accept a credit-note option right there.

### Indian Bank-Document Awareness
Supports e-BRC and FIRA-style realization data. ClawBack uses your bank documents to establish what you were actually paid, so the difference between invoice value and realized payment is clear.

### Evidence-First Calculation
- AI is used only to extract data from documents.
- All financial calculations are deterministic.
- Every calculated figure traces back to its inputs and source evidence.
- A calculation receipt shows each formula with the real values plugged in.

### Negotiation Support
Produces evidence-backed negotiation positions and structured settlement alternatives. The focus stays on recovering value, not just analyzing paperwork.

---

## The interface

ClawBack looks like a financial and legal workbench, because that's the kind of work it does:

- Tabular data layouts
- Monospace financial figures
- Exhibit-style evidence references
- A document viewer with highlighted evidence
- A muted, professional color palette
- No chat window, and nothing that feels like a generic AI wrapper

---

## Disclaimer

ClawBack provides negotiation support and document-based calculations. **It is not legal advice.** For legal questions about your claim, talk to a qualified professional.
