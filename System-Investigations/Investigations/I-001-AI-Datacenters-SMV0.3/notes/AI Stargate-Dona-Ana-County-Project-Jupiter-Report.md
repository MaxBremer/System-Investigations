---
title: Stargate Doña Ana County — Project Jupiter Site Report
date: 2026-08-17
status: research-v1
tags:
  - systems-investigation
  - ai-infrastructure
  - datacenters
  - stargate
  - new-mexico
investigation: 001-AI-Datacenters
---

# Stargate Doña Ana County — Project Jupiter Site Report

**As of August 17, 2026**

## Bottom line

Project Jupiter is no longer a paper site. Earthwork and vertical construction are underway in Doña Ana County, Oracle reported the job roughly **9% complete** in late July, and the project had logged **2.1 million construction hours** and **2,755 workers to date**. The announced first operating capacity remains targeted for **Q4 2026**, with the initial 400-acre phase and its microgrid scheduled for **Q3 2028**. The physical program is four data-center buildings plus a warehouse on an active site Oracle describes as **818 acres**, inside a broader county-approved campus of roughly **1,400 acres**.

But the project's binding constraint is now fuel and permitting, not concrete. Oracle and the developers abandoned the original turbine-and-battery power design in April 2026 and replaced it with an islanded **up-to-2.45 GW Bloom Energy fuel-cell microgrid**. That removed the large combustion turbines and routine diesel backup, but it did not remove natural gas. The permit record says the new plant needs about **400 million cubic feet of gas per day**—roughly **146 Bcf per year** if sustained. New Mexico's State Land Commissioner has twice refused the rights-of-way needed for **0.6 mile of the proposed 17-mile Green Chili Lateral**, and no permitted alternate route has been publicly identified. A contested air-permit hearing is set to begin **September 14, 2026**, while opponents are also asking the hearing officer to dismiss the application as presently unbuildable. Construction can continue on portions of the campus, but commercial operation at the advertised scale cannot.

The finance numbers are unusually large and unusually easy to misread. Doña Ana County authorized as much as **$165 billion** of industrial revenue bonds over 30 years. That is a tax-structuring ceiling, not $165 billion of county debt and not proof that $165 billion has been spent. County documents divide the ceiling into roughly **$15 billion for the power layer**, **$25 billion for four building/site entities**, and **$125 billion for the tenant/equipment layer**. On the disclosed 2.45 GW generation denominator, those envelopes are **$6.1B/GW**, **$10.2B/GW**, and **$51.0B/GW**, respectively; the full 30-year ceiling is **$67.3B/GW**. This is the clearest public site-level cost stack in Stargate, but it is an authorization stack, not an audited construction budget.

Cooling is comparatively well specified. Each of four buildings is planned to receive a one-time **2.5 million gallon** non-potable fill in a closed-loop system. The fuel-cell system requires a **960,000 gallon** initial fill and about **167,000 gallons per year** thereafter. Those numbers support the narrow claim of near-zero operating water for cooling and power; they do not include construction water, dust suppression, or ordinary employee use.

## Evidence labels used in this note

- **Disclosed** — stated by Oracle, OpenAI, STACK/BorderPlex, Bloom, or another project party.
- **Registered** — contained in a government approval, permit filing, ordinance, bond document, tariff, or other official record.
- **Derived** — arithmetic from disclosed or registered inputs.
- **Scenario** — an explicit sensitivity or comparison, not a forecast.
- **Unknown** — not publicly disclosed or not supported well enough to state as fact.

## Hard-number snapshot

| Item | Best current number | Evidence | What it actually means |
|---|---:|---|---|
| Announced data-center program | 4 buildings + 1 warehouse | Disclosed | Physical campus program, not four independently disclosed IT-load blocks |
| Active development footprint | 818 acres | Disclosed | Oracle's current site description |
| Broader approved campus | ~1,400 acres | Registered | County/IRB project area; not all disturbed at once |
| Initial phase | ~400 acres | Registered | County schedule associates this phase with the microgrid |
| Construction status | 9% complete at July 28, 2026 | Disclosed | Oracle presentation; percentage basis is not independently defined |
| Construction labor to date | 2,755 workers; 2.1M hours | Disclosed | Cumulative through July 2026, not simultaneous headcount |
| Initial operation target | Q4 2026 | Registered | First capacity, not full campus |
| Phase-one completion target | Q3 2028 | Registered | 400-acre phase plus microgrid |
| On-site generation | Up to 2.45 GW | Disclosed / permit pending | Installed fuel-cell nameplate; **not disclosed critical IT load** |
| Fuel-cell units | 2,275 | Registered | Air-permit application configuration |
| Natural-gas requirement | ~400 MMcf/day | Registered | Permit-case figure; about 146 Bcf/year if sustained |
| Initial investment commitment | At least $50B in first five years | Registered | County IRB commitment/envelope; allocation and draw timing undisclosed |
| Maximum IRB authorization | Up to $165B over 30 years | Registered | Tax-advantaged eligible-investment ceiling, not county-funded capex |
| Power-layer IRB authorization | $15B | Registered | Series 2025A / Yucca Growth Infrastructure envelope |
| Four building/site authorizations | $25B total | Registered | Four $6.25B Series 2025B subseries |
| Tenant/equipment authorization | $125B | Registered | Series 2025C envelope associated with Green Chile Ventures / Oracle |
| PILOT | $12M/year for 30 years | Registered | $360M nominal total, separate from other tax receipts and community commitments |
| Cooling initial fill | 2.5M gal × 4 buildings | Disclosed | 10M gallons of non-potable water, once |
| Fuel-cell initial fill | 960,000 gal | Disclosed | One-time non-potable fill |
| Fuel-cell annual top-off | ~167,000 gal/year | Disclosed | Normal operating water for the power plant |
| Employee potable-water cap | 60,000 gal/day | Registered / disclosed | Maximum; project estimate is ~20,000 gal/day average |

## What is actually being built

### Campus and parties

OpenAI added Doña Ana County to the Stargate program in September 2025 as one of three Oracle-linked sites. Its announcement said the three sites plus a possible Abilene expansion could provide more than **5.5 GW** of capacity, but it did not assign a site-specific IT load to Jupiter. ([OpenAI announcement](https://openai.com/index/five-new-stargate-sites/))

The project chain is more complicated than the Stargate label suggests:

1. **BorderPlex Digital Assets and STACK Infrastructure** are the development sponsors identified by the county.
2. **Yucca Growth Infrastructure LLC** is the power/microgrid project company and the applicant for Air Quality Permit No. 10883.
3. Four **Red Chiles** project entities correspond to the building/site layer in the IRB documents.
4. **Green Chile Ventures LLC**, now identified in Wisconsin records as Oracle America Cloud Services' former name, sits in the tenant/equipment layer.
5. **Oracle Cloud Infrastructure** is the cloud operator and anchor tenant; **OpenAI** is the principal Stargate compute customer.
6. During the IRB term, **Doña Ana County holds bare legal title** and leases the project back. That title is a tax-financing mechanism; the county does not operate the campus or guarantee the bonds.

Oracle's current project page describes **four data-center buildings and a warehouse across 818 acres**. County material uses a roughly **1,400-acre** total campus and a **400-acre** initial phase. These figures can coexist: 1,400 acres is the broader entitled/IRB project, while 818 acres is Oracle's currently described active campus footprint. They should not be blended into a false single number. ([Oracle project page](https://www.oracle.com/data-centers/dona-ana-county/); [Doña Ana County project page](https://www.donaana.gov/about_us/project_jupiter/index.php))

### Construction state

The site is under construction. Oracle's July 28 county presentation reported:

- **9% construction progress**;
- **2,755 construction workers to date** and **2.1 million hours worked**;
- nearly **700 New Mexico residents** employed on the job;
- **$734 million** in contracts with **151 New Mexico suppliers**; and
- **14% union labor**.

Those are developer-reported metrics, but they are materially harder than the generic “thousands of jobs” language. They also clarify that 2,755 is cumulative participation, not a promise of 2,755 permanent positions. Oracle now forecasts a peak or supported total of **7,000 construction jobs** and **1,500 ongoing jobs**; the original county IRB performance floor was much lower—**750 full-time, 50 part-time, and 2,500 construction jobs**—and is the more relevant number for enforcement. ([Oracle's July 2026 county presentation](https://cms2.revize.com/revize/donaanacounty/Documents/About%20Us/Economic%20Development%20Projects/PJ%20-%20BOCC%20Presentation%20-%207.28.2026.pdf?t=202607291203050))

County commissioners and staff had described the project as **out of compliance** in late June because required job reports and supporting records had not been submitted. Oracle's July presentation supplied a much fuller labor dataset, but the public materials reviewed for this report do not show a formal county finding that every reporting deficiency was cured. That is an oversight issue, not evidence that construction stopped. ([KRWG compliance report](https://www.krwg.org/krwg-news/2026-06-25/project-jupiter-out-of-compliance-says-dona-ana-county-commissioners-and-staff))

The county schedule still shows construction beginning in Q4 2025, initial operations in **Q4 2026**, and completion of the 400-acre first phase and microgrid in **Q3 2028**. “Initial operations” should not be read as 2.45 GW online. Neither Oracle nor the county has published the MW in the first energization tranche.

## Power: a 2.45 GW gas system wearing a fuel-cell label

### The April 2026 redesign

The original plan paired large natural-gas turbines with batteries and diesel backup. In April 2026 Oracle, BorderPlex, and Bloom announced a redesign around an **up-to-2.45 GW solid-oxide fuel-cell microgrid**. The planned **single islanded microgrid** removes the combustion turbines and routine diesel generators and is expected by the companies to emit **92% less NOx** than the prior turbine design. Oracle says it will pay all of the site's energy infrastructure and electricity costs. ([Oracle/Bloom announcement](https://www.oracle.com/news/announcement/oracle-borderplex-and-bloom-energy-to-power-project-jupiter-with-fuel-cell-technology-2026-04-27/))

The air application covers about **2,275 fuel-cell units**. The attractive reliability proposition is genuine: many modular units can be maintained while the balance of the plant keeps running, and islanding avoids waiting for a multi-gigawatt utility interconnection. But the system is still a very large natural-gas power plant. “Fuel cell” describes the conversion technology, not the fuel.

### Capacity denominator: what is known and what is not

**Known:** the generation design is up to **2.45 GW installed**.

**Unknown:** critical IT load, facility load, PUE, reserve margin, and the amount of generation assigned to each building.

Therefore, all `/GW` values in this report that use 2.45 GW are normalized to **installed generation capacity**, not GPU/IT load. Treating 2.45 GW as critical IT capacity would silently assume zero cooling/electrical overhead and zero reserve margin. That is not credible.

At continuous full output, 2.45 GW is **21.46 TWh/year**. At a 90% utilization sensitivity it is **19.32 TWh/year**. Those are generation-energy ceilings/sensitivities, not a forecast of IT consumption.

### Gas supply is the gating item

The permit case identifies a requirement of roughly **400 MMcf/day** of natural gas. Annualized, that is:

> 400 MMcf/day × 365 = **146,000 MMcf/year**, or **146 Bcf/year**.

The planned supply route is the **17-mile, 24-inch Green Chili Lateral**. The New Mexico Commissioner of Public Lands denied two rights-of-way and a business lease covering about **0.6 mile** of state trust land in March and again denied reconsideration on July 14. Her letter says the same permit application could authorize more than **10 million metric tons of CO₂-equivalent per year** at its ceiling. ([State Land Office denial](https://www.nmstatelands.org/2026/07/15/commissioner-garcia-richard-again-denies-request-to-run-portion-of-project-jupiter-pipeline-through-state-lands/); [July 14 decision letter](https://www.nmstatelands.org/wp-content/uploads/2026/07/2026-07-14-Letter-re-Informal-Request-for-Reconsideration_Final.pdf))

This is not a final statewide prohibition on the project: the developer can appeal, reroute, or propose another lawful supply arrangement. It is nevertheless a concrete blocker. As of this report, no alternate route or already-authorized source capable of delivering 400 MMcf/day has been placed in the public permit record.

### Air permit status

Yucca Growth Infrastructure's Air Quality Permit No. 10883 remains pending in NMED docket **AQB 26-57(P)**. The contested hearing is currently scheduled to begin **September 14, 2026**, moved forward from October at the applicant's request. Opponents have requested restoration of the later date and, separately, dismissal on the theory that the application is no longer capable of construction without an obtainable gas route. The hearing officer had sought threshold briefing, then ruled the issue should be developed through sworn testimony; a motion to reconsider that procedural decision was filed August 10. These are litigant positions, not an NMED finding that the project is dead. ([NMED docketed matters](https://www.env.nm.gov/opf/docketed-matters/); [August 10 motion](https://www.env.nm.gov/opf/wp-content/uploads/sites/13/2026/07/2026-08-10-AQB-26-57-NEEs-Mtn-for-Reconsideration-filed.pdf); [hearing schedule report](https://sourcenm.com/2026/07/31/hearing-for-project-jupiter-data-centers-air-quality-permit-application-rescheduled-to-september/))

The practical status is therefore:

- **site construction:** active;
- **fuel-cell procurement/design:** announced and in permitting;
- **air permit:** unresolved;
- **gas route:** unresolved after a second denial;
- **full-scale energization:** not yet legally secured.

## Cooling and water: hard numbers, narrow claim

Oracle describes a closed-loop, non-evaporative liquid-cooling design. The project says it will not use public potable water for cooling or power in normal operations. The detailed water table is more useful than the slogan: ([Project Jupiter water disclosures](https://projectjupitertogether.com/))

| Use | Initial fill | Ongoing use |
|---|---:|---:|
| Four data-center cooling loops | 2.5M gal each; **10M gal total** | 0–1,000 gal/year in the published table |
| Bloom fuel-cell system | **960,000 gal** | **167,000 gal/year** |
| Employee/domestic use | Not stated | ~20,000 gal/day average; **60,000 gal/day cap** |

The cooling and fuel-cell initial fills total **10.96 million gallons** of non-potable water. The disclosed ongoing process-water figure is approximately **168,000 gallons per year** if the cooling top-off line is campus-wide, or at most roughly **171,000 gallons per year** if 1,000 gallons applies to each building. The source is ambiguous on that point; the difference is immaterial at campus scale.

The near-zero operating-water claim is credible **for the cooling and fuel-cell process loops**. It does not mean the construction project uses almost no water. Dust control, concrete, grading, landscaping, firefighting reserves, and workforce demand sit outside that narrow metric unless separately counted. It also does not answer heat-rejection performance during extreme desert conditions; no design-day PUE, dry-bulb limit, or parasitic fan/pump load has been disclosed.

## Financing structure

### What the $165 billion IRB is—and is not

Doña Ana County approved an industrial revenue bond framework with an initial commitment of at least **$50 billion in the first five years** and a maximum of **$165 billion over 30 years**. Under the structure, the county holds bare legal title and leases the assets back to the project companies. A project affiliate or third party purchases the bonds; the project company, not the county, is responsible for repayment. The bonds are non-recourse to the county. The title-and-lease structure can exempt eligible property from property tax and eligible purchases from gross-receipts/compensating tax. ([County project and IRB explanation](https://www.donaana.gov/about_us/economic_development_projects.php); [county authorization release](https://www.donaana.gov/news_detail_T7_R35.php))

In plain English:

- **It is not a $165 billion county borrowing.** Taxpayers are not lending $165 billion to Oracle.
- **It is not evidence of $165 billion of day-one capex.** It is a not-to-exceed eligible-investment envelope across 30 years.
- **It is economically meaningful.** The structure can shelter an enormous quantity of buildings, power assets, equipment, and equipment refreshes from taxes that would otherwise apply.

### Bond series map

The executed/form transaction documents disclose a useful layer map:

| Series | Project entity / layer | Maximum authorization | Derived per 2.45 GW |
|---|---|---:|---:|
| 2025A | Yucca Growth Infrastructure / power system | **$15B** | **$6.12B/GW** |
| 2025B-1 through B-4 | Four Red Chiles building/site entities | **$6.25B each; $25B total** | **$10.20B/GW total** |
| 2025C subseries | Green Chile Ventures / Oracle tenant-equipment layer | **$125B total** | **$51.02B/GW** |
| **Total** | All authorized layers over 30 years | **$165B** | **$67.35B/GW** |

The category descriptions are based on the transaction entities and leased-property roles, not an audited vendor-level budget. The full face authorization also may never be issued or drawn. ([Executed IRB ordinance](https://cms2.revize.com/revize/donaanacounty/Documents/About%20Us/Economic%20Development%20Projects/Ordinance%20No.%20367-2025%20IRB%20Adoption_Executed%26Recorded.pdf?t=202606221845080); [county index to executed Series 2025A/B/C documents](https://www.donaana.gov/departments/administration/economic_development/project_jupiter/index.php))

### Payments and public support

The property-tax abatement is partly offset by a **$12 million annual payment in lieu of taxes for 30 years**, or **$360 million nominal**. Oracle also committed **$50 million** for regional water infrastructure and **$6.9 million** in additional community investments. By July 2026, Oracle said 80% of the water commitment was funded and the project had generated almost **$80 million** in tax revenue to date. It projects approximately **$600 million** of construction gross-receipts/sales tax and **$680 million** during 17 years of operation. These are developer forecasts and gross tax flows, not the value of taxes abated. ([Oracle July 2026 update](https://www.oracle.com/news/announcement/project-jupiter-2026-07-28/))

The county's frequently cited **$4.7 billion economic impact** is modeled economic activity. It should not be added to tax receipts, treated as capital investment, or used as a financing source.

Two pending lawsuits challenge the county's approval process and IRB ordinances. Their existence creates legal risk; it does not by itself invalidate the bonds. ([New Mexico Environmental Law Center case page](https://nmelc.org/our-work/projectjupiter/))

## Per-GW cost stack

### Registered authorization stack

The 2.45 GW denominator is the only project-specific GW figure supported in public records, but it is installed generation rather than critical IT. With that caveat:

| Cost layer | Public number | $/GW of installed generation | Confidence |
|---|---:|---:|---|
| Power / microgrid authorization | $15B | **$6.1B/GW** | High for authorization; low for actual spend |
| Four building/site authorizations | $25B | **$10.2B/GW** | High for authorization; medium-low for layer allocation |
| Tenant/equipment authorization | $125B | **$51.0B/GW** | High for authorization; low for timing and draw |
| Full 30-year IRB ceiling | $165B | **$67.3B/GW** | High arithmetic; not an upfront-capex metric |
| Initial five-year commitment | $50B | **$20.4B/GW** | Capacity/phase mismatch; lower-bound envelope only |

The stack is internally informative even though the absolute numbers are ceilings. The **$40 billion A+B envelope** implies up to **$16.3B/GW** for power plus the four-building campus before tenant equipment. That is in the same broad range as the companion Stargate campus reports. The **$125 billion C envelope** is large enough to accommodate several generations of accelerators over 30 years, which is why it should not be read as an initial server purchase.

### Comparable all-in scenario—not a forecast

The Abilene companion model used an illustrative **$33.3B/GW of IT hardware** and **$12.5B/GW of powered campus**. Applying only the hardware component to Jupiter's 2.45 GW generation denominator gives **$81.6 billion**. Pairing it with the registered $40 billion A+B power/building envelope gives a rough **$121.6 billion**, or **$49.6B/GW**, all-in system scenario.

This scenario is deliberately not added to the $125 billion Series C authorization because Series C appears designed to hold the tenant/equipment layer. Adding both would double-count the same economic layer. It is useful as an order-of-magnitude check, not as a forecast that the site will buy $81.6 billion of accelerators.

### Operating-energy sensitivity

At 90% utilization, 2.45 GW produces about **19.32 TWh/year**. Valued at a generic **$40–$80/MWh** power sensitivity, that is **$0.77–$1.55 billion per year**, or **$0.32–$0.63B/GW-year**. Jupiter is not buying all of this energy through a conventional retail PPA; it will buy fuel and operate/contract for an on-site generation system. The calculation is an electricity-equivalent sensitivity, not a disclosed tariff or gas bill.

## What the corporate language leaves out

1. **“2.45 GW” is generation, not disclosed compute load.** There is no public PUE or critical-IT MW.
2. **“Clean fuel cells” still require pipeline gas.** The design changes the conversion process and local pollutants; it does not make the fuel supply renewable.
3. **The pipeline denial is only 0.6 mile, but that 0.6 mile breaks the disclosed route.** Scale of the denied segment is not the same as importance.
4. **The $165 billion is a ceiling, not a check.** It is also not meaningless: it maps the intended tax shelter across power, buildings, and repeated equipment investment.
5. **The water figure is process-specific.** It is strong evidence for low operational cooling water, not total-site water consumption during construction.
6. **The job numbers changed categories.** “2,755 workers to date,” “7,000 construction jobs,” and “1,500 ongoing jobs” are not interchangeable headcounts, and the enforceable minimum is lower.

## Known, inferred, and unknown

### Known / registered

- Four data-center buildings and a warehouse are under construction.
- The active Oracle-described site is 818 acres inside a broader roughly 1,400-acre project.
- Oracle reported 9% construction progress on July 28, 2026.
- The power design is an up-to-2.45 GW islanded fuel-cell microgrid.
- The air permit remains pending and the disclosed pipeline route lacks required state-land rights-of-way.
- The county authorized up to $165B of non-recourse IRBs over 30 years and a $12M annual PILOT.
- The published cooling system is closed-loop and has quantified initial and maintenance-water requirements.

### Strongly inferred

- Series 2025A is primarily the power-infrastructure envelope, Series 2025B the four-building/site envelope, and Series 2025C the tenant/IT-equipment envelope.
- The $125B tenant/equipment ceiling anticipates hardware refresh over the 30-year term rather than a single initial installation.
- The Q4 2026 “initial operations” target represents a fraction of the 2.45 GW ultimate generation design.

### Unknown

- Critical IT MW, facility MW, PUE, reserve margin, and first-energization MW.
- The executed Bloom purchase price, EPC contract value, gas commodity/transport contract, and microgrid operating-cost model.
- Whether an alternate gas route has been engineered or contracted.
- Actual IRB issuance/draws by series and the value of taxes foregone.
- Oracle's site lease payment, OpenAI's site-specific compute commitment, and project-specific debt/equity terms.
- GPU type, quantity, rack density, network topology, and hardware refresh schedule.

## Falsifiers and next evidence to watch

The current assessment should change materially if any of the following appears:

1. **A final NMED air permit** with enforceable emission, fuel, and construction conditions.
2. **A lawful gas-supply route**—successful appeal, new right-of-way, alternate interconnection, or redesigned supply.
3. **A disclosed first-phase MW figure** and explicit separation of generation, facility, and critical-IT capacity.
4. **IRB issuance statements or project-company financials** showing actual proceeds and spend by Series A/B/C.
5. **A Bloom procurement/EPC value** that converts the $15B envelope into an actual power-system cost.
6. **Measured operating data**: PUE, fuel use, heat rate/electrical efficiency, water top-off, availability, and emissions.

## Assessment

**Project reality: high. Schedule confidence: medium-low. Cost transparency: medium for authorization envelopes, low for actual spend.**

Jupiter is physically real and substantially mobilized, but its energy design is not yet executable on the route disclosed in its own permit materials. The developers' pivot to modular fuel cells is technically plausible and sharply reduces local NOx and routine cooling water relative to the original plan. It also concentrates the project's vulnerability in one very large, continuous gas requirement.

The most defensible economic reading is not “New Mexico financed a $165 billion data center.” It is: Oracle and its partners obtained a **30-year, $165 billion tax-advantaged investment envelope**, divided into a **$15B power layer, $25B building/site layer, and $125B tenant/equipment layer**, while committing at least $50B early and $360M of PILOT payments over the term. That structure makes Jupiter potentially the largest and best-documented Stargate cost stack—but the gap between authorization and expenditure remains enormous.

Until the air permit and gas route are resolved, the hard conclusion is simple: **the campus can keep being built, but the advertised 2.45 GW machine cannot yet be fueled legally as proposed.**
