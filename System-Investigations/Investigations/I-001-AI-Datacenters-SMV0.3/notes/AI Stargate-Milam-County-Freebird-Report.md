---
title: Stargate — Milam County (Freebird) Site Report
date: 2026-08-17
status: research-v1
tags:
  - systems-investigation
  - ai-infrastructure
  - datacenters
  - stargate
  - texas
investigation: 001-AI-Datacenters
---

# Stargate — Milam County (Freebird) Site Report

**As of August 17, 2026**

## Bottom line

Milam County is an active construction project with a clear tenant and first building, but an unusually opaque end-state cost and power stack. OpenAI has signed a **1.2 GW data-center lease**, while SB Energy is building and will operate the campus near Burlington. The first building—Freebird Phase 1—is a **548,950-square-foot, four-data-hall facility** with a Texas registered cost of **$470 million** and a filed completion target of **October 15, 2026**. The building topped out in March, but no operating capacity has been announced.

The only public campus-scale capital figure found is a Milam County development notice describing **more than $3 billion** of investment across a roughly **595-acre, multi-building campus**. Dividing that by 1.2 GW gives a documented floor of **more than $2.5 billion/GW**. That is far below comparable all-in powered-campus numbers and should not be mistaken for a complete cost. It likely reflects an early or incentive-agreement capital commitment, an initial development scope, or a boundary that excludes major power and tenant equipment.

The project’s central unresolved variable is electricity. SB Energy says it will build new generation to support Milam and protect ratepayers, but has disclosed **no generation technology, MW capacity, fuel, interconnection structure, cost, or delivery schedule**. The adjacent Orion solar project is not evidence of dedicated Stargate power: SB Energy announced that Orion's output was contracted to Google for its Dallas-area cloud operations.

## Evidence labels

- **Disclosed:** stated by a company or government record.
- **Registered:** a project value or schedule in a Texas filing; not an audited final cost or proof of completion.
- **Derived:** arithmetic using disclosed numbers.
- **Scenario:** a comparability calculation, not a site disclosure.
- **Unknown:** no reliable public number found.

## Hard-number snapshot

| Item | Number | Status / interpretation |
|---|---:|---|
| OpenAI lease / planned site capacity | **1.2 GW** | Disclosed; source does not specify whether denominator is critical IT or total facility load |
| Campus land | **~595 acres** | County development notice; some summaries say 593 acres |
| Campus investment | **More than $3B** | County notice/early development figure; incomplete scope likely |
| Phase 1 registered cost | **$470M** | Texas filing estimate |
| Phase 1 floor area | **548,950 sq. ft.** | Texas filing |
| Phase 1 data halls | **4** | Texas filing |
| Phase 1 filed completion | **Oct. 15, 2026** | Schedule target, not an opening guarantee |
| State-certified phases | **2** | Large-project registrations effective Dec. 2025 and June 2026 |
| Operational capacity | **0 GW confirmed** | No energization or service announcement found |
| Construction jobs | **Thousands** | SB Energy forecast, not current headcount |
| OpenAI permanent jobs | **400+ reported** | Local incentive reporting; definition and timing not fully disclosed |
| New generation | **Planned; type and MW unknown** | SB Energy statement |

Sources: [SB Energy–OpenAI agreement](https://sbenergy.com/openai-and-softbank-group-partner-with-sb-energy/), [OpenAI Stargate site announcement](https://openai.com/index/five-new-stargate-sites/), [Texas Phase 1 filing](https://www.tdlr.texas.gov/TABS/Search/Print/TABS2026017746), [Texas qualifying-project registry](https://comptroller.texas.gov/taxes/data-centers/data-center-lists.php), and [Milam County meeting notice](https://newtools.cira.state.tx.us/upload/page/8999/MEETING%2006-09-2025.2.pdf).

## What is actually being built

The project has changed names and counterparties as it moved from local development approvals into Stargate:

1. A county notice identified **SE DC DevCo LLC** as developer of a multi-building data-center campus with more than $3 billion of investment.
2. **SB Energy**, a SoftBank Group company, now describes itself as the builder and operator of OpenAI's 1.2 GW Milam County site.
3. The Texas construction filing names **Milam County Data Center LLC** as Phase 1 owner and **OpenAI** as tenant.
4. The Texas tax registry uses building SPVs—**MDC Building 1 LLC** and **MDC Building 2 LLC**—with **Orion DC I LLC** as qualifying occupant and **Milam County DC LLC** as operator.
5. **DPR Construction and Sundt Construction** are delivering the project as a joint venture; **Corgan** is the Phase 1 architect.

The multiple LLCs are normal project-finance ring-fencing, but they make casual source matching dangerous. In particular, **“Orion DC I” should not be assumed to mean that the nearby Orion solar plant powers this data center.** The solar project's published offtake says otherwise.

Sources: [DPR project page](https://www.dpr.com/milam-county-data-center), [Phase 1 filing](https://www.tdlr.texas.gov/TABS/Search/Print/TABS2026017746), and [Texas registry](https://comptroller.texas.gov/taxes/data-centers/data-center-lists.php).

## Current state and schedule

Milam is farther along at the first-building level than the phrase “planned site” suggests, but it remains pre-operational.

- Site work began in 2025.
- Texas lists a Phase 1 start date of October 20, 2025.
- The structural frame topped out on March 19, 2026.
- Satellite imagery reviewed by Epoch AI on March 23 showed steel framing and roofing on the first building and assessed zero operational capacity.
- The state certified **Milam County Data Center** as a qualifying large project effective December 9, 2025 and **Phase 2** effective June 10, 2026. This shows a second legally organized phase, not that Phase 2 is built or energized.
- The Phase 1 registration targets October 15, 2026 completion. No public first-power, commissioning, or OpenAI service milestone had been announced by August 17.

The best current classification is **Phase 1 under advanced construction; Phase 2 organized/registered; full 1.2 GW build-out not publicly scheduled in enough detail to audit.** OpenAI's original announcement said the SoftBank sites could scale over 18 months, while independent site tracking treats the complete campus as a 2028-class project. Those statements describe different milestones and should not be collapsed into one “completion date.”

Sources: [Texas Phase 1 filing](https://www.tdlr.texas.gov/TABS/Search/Print/TABS2026017746), [April construction report](https://www.datacenterdynamics.com/en/news/openai-stargates-milam-texas-freebird-data-center-to-span-548950-sq-ft-in-first-phase/), [Epoch AI site survey](https://epoch.ai/publications/openai-stargate-where-the-us-sites-stand), and [OpenAI's five-site announcement](https://openai.com/index/five-new-stargate-sites/).

## Build-out geometry

Phase 1 contains four data halls plus support infrastructure, loading and administrative areas. The filing does **not** state MW. That omission blocks a defensible Phase 1 $/GW number.

Useful registered ratios are:

- **$856 per square foot** for Phase 1 ($470 million / 548,950 sq. ft.).
- **$117.5 million per data hall** if the cost is divided evenly across four halls; this is a geometric average, not a hall-level budget.
- If Phase 1 were exactly one quarter of the 1.2 GW lease, it would represent 300 MW and imply **$1.57 billion/GW**. That is an explicitly hypothetical sensitivity. Neither the filing nor SB Energy confirms 300 MW.

The difference between the 548,950-square-foot building and the broader multi-building campus also means that “Phase 1 completion” will not equal “Milam completion.”

## Power: announcement without a design

SB Energy says it will “build new generation” to support the data center and minimize effects on Texas ratepayers. That is strategically important but technically thin. The following remain undisclosed:

- Generation technology and fuel.
- Nameplate, firm and backup MW.
- Whether the 1.2 GW denominator is IT load or total facility demand.
- PUE and therefore actual site input power.
- Grid interconnection capacity and energization date.
- Storage, black-start and islanding design.
- Capital cost, heat rate or contracted energy price.
- Emissions, water consumption and permitting pathway.

The nearby **900 MWdc Orion I solar project** cannot be counted as Milam's power source. SB Energy's own commissioning announcement says Google contracted the project's output under a power-purchase agreement for its Texas cloud operations. Geographic proximity and the “Orion DC I” occupant name are not a power contract.

The state large-data-center registrations establish only that the projects meet program requirements, including power-system and investment commitments. They do not reveal a 1.2 GW deliverable interconnection or generation plant.

Sources: [SB Energy partnership release](https://sbenergy.com/openai-and-softbank-group-partner-with-sb-energy/), [Orion solar offtake announcement](https://sbenergy.com/american-made-solar-projects-power-google-data/), and [Texas program rules](https://comptroller.texas.gov/taxes/data-centers/).

## Cooling and water

SB Energy says Milam is designed to **minimize water usage**, but publishes no cooling architecture, WUE, annual gallons, source-water allocation, or drought case. Some secondary accounts use “closed loop,” but the company statement does not supply enough engineering detail to quantify it. Until a permit or design disclosure appears, Milam's water claim is a goal rather than a measurable specification.

## Cost stack per GW

The planned denominator is **1.2 GW**, but its exact electrical boundary is undisclosed. That makes comparisons to Vantage's “critical IT load” imperfect.

| Layer | Site total | Per GW | Evidence | What it means |
|---|---:|---:|---|---|
| County-notice campus investment | more than $3B | **more than $2.50B/GW** | Disclosed + derived | Documented floor, probably not a complete powered-campus budget |
| Phase 1 building | $470M | Not defensible | Registered | Capacity for this phase is not disclosed |
| Phase 1 if exactly 300 MW | $470M | **$1.57B/GW** | Scenario | Pure sensitivity; do not treat as a site fact |
| Compute hardware | Unknown | Unknown | Unknown | No chip count, generation, network or purchase cost disclosed |
| New generation | Unknown | Unknown | Unknown | Announced, but technology/MW/capex absent |
| Annual energy at 90% load, $40–$80/MWh | $0.378B–$0.757B/year | **$0.315B–$0.631B/GW-year** | Scenario | Comparative energy-value sensitivity; excludes PUE and does not forecast the power contract |

At 90% average utilization, 1.2 GW consumes **9.46 TWh/year** before facility overhead. If 1.2 GW is IT load and PUE were 1.2, total annual site input would be about **11.35 TWh**. If 1.2 GW is instead total facility load, that calculation would overstate demand. The denominator definition is therefore not bookkeeping trivia; it changes fuel, interconnection and cost conclusions.

### Why the $3 billion figure is almost certainly incomplete

The campus floor of $2.5 billion/GW is less than one-third of Frontier's registered building-only ratio and roughly one-seventh of Frontier's headline powered-campus ratio. Different design and accounting boundaries can explain some variation, but not enough to safely call Milam a radically cheaper full-stack campus.

The most plausible explanations are:

- The $3 billion is an early minimum capital commitment for local tax purposes.
- It covers only initial buildings or taxable property.
- New generation and high-voltage infrastructure sit in separate entities or later budgets.
- Tenant-furnished compute and networking are excluded.
- The eventual 1.2 GW is optional scale rather than fully funded scope.

These are hypotheses, not disclosed line items.

### Abilene comparability scenario—not a Milam estimate

Using the prior Abilene reference of roughly **$33.3 billion/GW of compute hardware**, a 1.2 GW Milam deployment would imply about **$40 billion** of hardware. Adding only the documented $3 billion campus floor gives **more than $43 billion**, or **more than $35.8 billion/GW**.

This is not a forecast. It shows that the visible $3 billion real-estate figure could be a small minority of the economic system once accelerators and networking are installed. Chip generation, purchasing discounts, refresh timing and the 1.2 GW boundary could all move the result materially.

## Financing and public support

OpenAI and SoftBank each invested **$500 million in SB Energy**, for **$1 billion of new platform equity**. SB Energy had also raised **$800 million of redeemable preferred equity from Ares** in 2025. These amounts support SB Energy's broader growth and data-center pipeline; the release does not allocate them to Milam. They should not be added to the $3 billion project figure.

The most project-specific financing fact is the **1.2 GW OpenAI lease**, which supplies the contracted demand needed to finance a build. Lease price, term, take-or-pay protection, commencement tests, escalators and credit support are undisclosed.

Texas lists both Milam phases as **qualifying large data center projects**. The program requires at least 250,000 square feet, $500 million of investment and 40 qualifying jobs, and grants a **20-year sales-and-use-tax exemption** on qualifying purchases including servers, electrical and cooling systems, and electricity. Phase 1's TDLR building estimate is only $470 million, so the certification necessarily relies on a broader five-year capital commitment than the building filing alone.

Milam County separately pursued a Chapter 312 property-tax abatement. Local reporting says the arrangement includes about **$13.5 million in payments in lieu of taxes**, but the public sources reviewed do not provide a clean net-present-value comparison of taxes waived versus payments received. State sales-tax relief and county property-tax treatment are separate subsidies and should be modeled separately.

Sources: [SB Energy financing and lease announcement](https://sbenergy.com/openai-and-softbank-group-partner-with-sb-energy/), [Reuters transaction report](https://www.reuters.com/business/energy/openai-softbank-invest-1-billion-sb-energy-2026-01-09/), [Texas project registry](https://comptroller.texas.gov/taxes/data-centers/data-center-lists.php), [Texas exemption rules](https://comptroller.texas.gov/taxes/data-centers/), [county notice](https://newtools.cira.state.tx.us/upload/page/8999/MEETING%2006-09-2025.2.pdf), and [local project reporting](https://www.mysanantonio.com/news/austin/article/data-centers-texas-22209790.php).

## What is known, inferred, and still missing

### High confidence

- OpenAI has contracted 1.2 GW of Milam County data-center capacity from SB Energy.
- Phase 1 is physically under construction and is not publicly operational.
- Phase 1 is a 548,950-square-foot, four-hall building registered at $470 million.
- At least two phases have been organized and certified for Texas's large-data-center tax program.
- SB Energy plans new generation, but has not disclosed its design.

### Medium-confidence interpretation

- The $3 billion campus figure is a floor or partial scope, not the complete 1.2 GW powered-campus budget.
- The first building could complete construction in late 2026, but meaningful compute service may follow commissioning and power availability later.
- The OpenAI lease is the principal bankability mechanism even though its economics remain private.

### Critical unknowns

- Capacity and rack count in Phase 1.
- Number, size and schedule of later buildings.
- Whether 1.2 GW means IT load or utility input.
- Generation technology, MW, capex, fuel and permits.
- Grid interconnection agreement and upgrade obligations.
- GPU vendor, model, count, networking and hardware capex.
- Numeric PUE, WUE and annual water requirement.
- Lease term and payment structure.
- Full local incentive value and net tax contribution.

## Falsifiers and next evidence to watch

- **Certificate of occupancy or first-power announcement:** would test the October 2026 Phase 1 target.
- **A Phase 2 construction registration:** would expose the next building's cost, area and timing.
- **Generation or interconnection permit:** would convert the largest unknown into an auditable engineering plan.
- **OpenAI/SB Energy capacity milestone:** would clarify whether 1.2 GW is firm build scope or a maximum lease envelope.
- **Detailed county abatement agreement:** would allow the public subsidy to be calculated instead of described.
- **Equipment procurement or transformer/generator orders:** would reveal whether the 2026–2028 schedule is physically plausible.

## Assessment

Milam is best understood as a **lease-anchored, vertically integrated SB Energy development** whose first building is visible but whose system boundary is not. The project has moved beyond PowerPoint: steel is up, a $470 million first phase is registered, a second phase has tax certification, and OpenAI is named in the tenant record. But the headline **1.2 GW** remains several disclosures away from bankable physical reality. The public cost floor is too low to represent a complete AI campus, and the promised “new generation” has no published design. Until phase MW and power infrastructure appear, Milam's most honest per-GW number is **more than $2.5 billion/GW of disclosed campus investment—and unknown total system cost**.

