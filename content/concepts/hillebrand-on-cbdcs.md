---
title: "Hillebrand on Central Bank Digital Currencies"
volatility: warm
category: concept
created: 2026-05-16
updated: 2026-05-17
tags: [hillebrand, cbdc, financial-surveillance, programmable-money, austrian-economics, privacy, state-power, intervention]
aliases: [Hillebrand on CBDCs, CBDCs as total intervention, Praxeology of Privacy Ch. 10]
short: "Hillebrand's claim that CBDCs combine Rothbard's three intervention types into a unified surveillance-and-control mechanism, with programmable expiry and direct ledger access as the load-bearing features."
---

# Hillebrand on Central Bank Digital Currencies

> Hillebrand's Chapter 10 of [[the-praxeology-of-privacy|The Praxeology of Privacy]] reads CBDCs through the Rothbardian intervention typology that [[power-and-market|Power and Market]] developed. Where current bank-mediated money permits surveillance only through *triangular* intervention against commercial-bank intermediaries, a CBDC eliminates the buffer and unifies all three intervention types — *autistic*, *binary*, *triangular* — into the monetary medium itself.

## The Passage

> "Central Bank Digital Currencies combine all three intervention types into a unified control mechanism. CBDCs are programmable money enabling comprehensive surveillance and control, not simple digital versions of existing currency. … Money can be programmed to expire, forcing spending and preventing saving; this implements negative interest rates without the zero lower bound. Money can be programmed to work only in specified regions … Money can refuse purchase categories … Transactions can require verified identity of both parties … Money can be programmed to activate only when conditions are met: vaccination status, social credit score, tax compliance, political loyalty tests."

## What the Chapter Argues

Hillebrand's claim is architectural, not rhetorical. Chapter 9 of [[the-praxeology-of-privacy|The Praxeology of Privacy]] establishes that today's monetary architecture interposes commercial banks between citizens and base money: citizens hold money substitutes (claims on banks), and the central bank reaches them only through regulatory intermediaries. Chapter 10 then shows that a CBDC removes this buffer. The central bank becomes the direct counterparty to every retail balance, so observation requires no subpoena and control requires no regulatory mandate. The frictions that currently slow financial surveillance — "legal process, institutional compliance, and enforcement resources" in Hillebrand's words — vanish.

The "two-tier" design that retains commercial banks as customer-facing intermediaries does not, in Hillebrand's reading, restore the buffer. The authoritative ledger is still the central bank's; the commercial bank is "a service provider operating within parameters the central bank defines, not [an] independent institution creating actual money substitutes." Programmability follows directly from this architecture: because the money is the central bank's liability, the central bank can attach rules to it. Expiration, geographic limits, category refusals, identity gating, and conditional activation become design parameters, not separate enforcement actions.

Hillebrand's adoption analysis is praxeological in the strict sense: revealed preference under existing payment-system convenience predicts that explicit cash bans are unnecessary. The state need only ensure that the CBDC is more convenient than the alternative; the network-effect contraction of cash-handling infrastructure does the rest. The endpoint is "surveillance that individuals chose for convenience [but] cannot escape without exiting the national currency entirely."

## Mechanism

The three intervention types map directly onto the CBDC. *Autistic* intervention is embedded in the protocol — the currency itself refuses disfavored payments, so "no prosecution is needed; the transaction simply fails." *Binary* intervention is automatic — every transaction is reported instantly because the state is the counterparty. *Triangular* intervention is imposed through merchant acceptance rules, compliance verification, and spending restrictions baked into the medium. The architectural change is therefore decisive in [[state-power-and-intervention|State Power and Intervention]] terms: the same three categories that previously required three separate institutional channels now run on one ledger.

## See Also

- [[praxeology-of-privacy|Praxeology of Privacy]] - parent concept article for the Austrian theory of privacy this chapter applies
- [[the-praxeology-of-privacy|The Praxeology of Privacy]] - source book; Chapter 10 is the direct origin of this article
- [[max-hillebrand|Max Hillebrand]] - author reference
- [[state-power-and-intervention|State Power and Intervention]] - the broader Rothbardian intervention frame the chapter applies
- [[power-and-market|Power and Market]] - source of the autistic/binary/triangular typology Hillebrand uses
- [[hayek-on-rule-of-law|Hayek on the Rule of Law]] - the constraint the programmability inverts
- [[privacy-and-cryptography|Privacy and Cryptography]] - topic map containing the implementation side
- [[2026-05-16-digital-euro-launch-cbdc-total-intervention|The Digital Euro Launch as CBDC Total Intervention: Analysis]] - thesis applying this article to the ECB's confirmed Q1 2027 design

## Sources

- [The Praxeology of Privacy: Economic Logic in Cypherpunk Implementation](https://towardsliberty.com/pop) - Chapter 10 "Financial Surveillance and Capital Controls," §10.5 "Central Bank Digital Currencies as Total Intervention" — the architectural argument, the three-intervention-types fusion, the programmable-control list, and the two-tier-illusion analysis
