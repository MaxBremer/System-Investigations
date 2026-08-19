---
title: Stargate Port Washington — Lighthouse Site Report
date: 2026-08-17
status: research-v1
tags:
  - systems-investigation
  - ai-infrastructure
  - datacenters
  - stargate
  - wisconsin
investigation: 001-AI-Datacenters
---

# Stargate Port Washington — Lighthouse Site Report

**As of August 17, 2026**

## Bottom line

Lighthouse in Port Washington, Wisconsin, is a real four-building Stargate campus under construction, not the much larger speculative concept sometimes attached to the surrounding land. Vantage Data Centers' committed program is **2.5 million square feet**, **902 MW of critical IT load**, and **more than $15 billion** of campus investment on **672 active acres**, with all four buildings scheduled for completion in **2028**. Vantage owns about **1,644 acres** in total, leaving room for a later expansion, but planning references to as much as roughly **3.5 GW** on the broader site should not be mistaken for today's four-building build.

Construction began in December 2025. Foundation work on the first two buildings started in January 2026, and Vantage had topped out both structural frames by late June. The site has its principal state wetland/stormwater approvals and a minor-source air permit covering **45 diesel emergency generators**. The critical unresolved dependency is grid delivery.

We Energies is planning around a **1.3 GW utility load request** for a campus whose published critical IT load is 902 MW. The 398 MW difference is a **44% facility/reserve headroom** relative to IT load, but it is not a disclosed PUE. Supplying that request requires a large American Transmission Company program: roughly **90–107 miles** of new or rebuilt 345/138 kV lines and four or five new substations. The estimated transmission cost has risen to **$1.3–$1.7 billion**. On August 6, 2026, Wisconsin regulators revoked the application's completeness finding after ATC refiled or revised 564 documents and closed the case, requiring a fresh application. That is not a rejection of Lighthouse, but it resets the review clock and makes the advertised end-2027 grid-ready / 2028 campus-completion schedule materially less secure.

The site-level cost stack is clearer than most. Vantage's **$15B+** powered-campus investment equals at least **$16.6B per GW of critical IT load**. The separate transmission program adds **$1.44–$1.88B/GW** on the same denominator if it is ultimately built at the current estimate. Port Washington's tax-increment district authorizes up to **$455.4 million** of developer reimbursements from future site-generated property-tax increment, or about **$0.50B/GW**, while Vantage says at least **$175 million** will be fronted for local infrastructure. Oracle's tenant/equipment layer also has a Wisconsin qualified-data-center sales/use-tax exemption, but neither the eligible spend nor the tax value has been disclosed.

Financing risk is concentrated in the power contract. Wisconsin's new very-large-customer tariff requires credit support tied to dedicated utility assets. Oracle's current credit rating could require **more than $7 billion of security**, according to its own filing, versus Oracle's proposed roughly **$700 million**. The tariff is designed to prevent ordinary customers from inheriting stranded assets if a hyperscale tenant fails or leaves. Oracle voluntarily dismissed its lawsuit challenging the rule on **August 17, 2026**, leaving the requirement in place; We Energies says it is working with Oracle to obtain the collateral. The security is not the same as a $7 billion construction cost, but it is a real constraint on the site's capital structure.

Cooling is designed around air cooling plus liquid-to-liquid distribution in a closed loop, with outside-air economization and near-zero process-water intensity. The most concrete operating estimate is **22,000 gallons/day peak** for the campus, although the development framework reportedly preserves a much larger **1.2 million gallons/day legal maximum**. The narrow design number and the broad entitlement ceiling need to be shown together.

## Evidence labels used in this note

- **Disclosed** — stated by Vantage, Oracle, OpenAI, We Energies, or another project party.
- **Registered** — contained in a government approval, permit, tariff, development agreement, tax certification, or official filing.
- **Derived** — arithmetic from disclosed or registered inputs.
- **Scenario** — an explicit sensitivity or comparison, not a forecast.
- **Unknown** — not publicly disclosed or not supported well enough to state as fact.

## Hard-number snapshot

| Item | Best current number | Evidence | What it actually means |
|---|---:|---|---|
| Active campus | 4 single-story data centers | Disclosed | Vantage's committed Lighthouse program |
| Critical IT load | **902 MW** | Disclosed | Best denominator for compute-serving capacity |
| Utility load request | **1.3 GW** | Registered / disclosed | Grid-service planning level; not critical IT and not PUE |
| Gross floor area | **2.5M sq ft** | Disclosed | All four buildings |
| Active campus area | **672 acres** | Disclosed | About 500 acres expected to be developed/disturbed |
| Total Vantage landholding | ~1,644 acres | Registered | Includes expansion/undeveloped land, not current four-building footprint |
| Vantage campus investment | **>$15B** | Disclosed | Powered-campus program; tenant IT hardware inclusion not demonstrated |
| Construction state | First two buildings topped out | Disclosed | Structural milestone, not commissioning or energization |
| Target completion | **2028** | Disclosed | All four buildings; exact phased MW schedule undisclosed |
| Transmission program | ~90–107 route miles; 4–5 new substations | Registered | ATC grid reinforcement required for the utility request |
| Transmission estimate | **$1.3–$1.7B** | Registered / reported | Revised range before the August 2026 docket reset |
| Current transmission status | Application completeness revoked Aug. 6, 2026 | Registered | Case closed; ATC must file a new application |
| Renewable/resource plan | Nearly 2 GW nameplate; 70% campus / 30% general customers | Disclosed | Nameplate resource portfolio, not 24/7 firm zero-carbon supply |
| Emergency generation | **45 diesel generators** | Registered | Air-permitted standby fleet |
| Cooling | Air-cooled + liquid-to-liquid; closed loop | Disclosed | Supports high-density liquid cooling without evaporative towers |
| Expected peak water | **22,000 gal/day** | Disclosed / city fact sheet | Design expectation; not the legal entitlement ceiling |
| Water-service ceiling | Up to **1.2M gal/day** | Registered / reported | Contingency/legal maximum, not forecast demand |
| TID reimbursements | Up to **$455.4M** | Registered | Paid only from future tax increment; city says no general-obligation borrowing |
| Local infrastructure fronted | At least **$175M** | Disclosed | Roads, water/wastewater and related improvements; overlaps TID program |
| Power credit support | Potentially **>$7B** for Oracle | Registered / reported | Oracle's estimate of collateral exposure; suit dropped Aug. 17; not capex |

## What is actually being built

### The committed campus versus the optional future site

OpenAI and Oracle identified Lighthouse as the Wisconsin Stargate site in October 2025. Vantage's current specification is unusually precise: **four single-story facilities, 902 MW of critical IT capacity, 2.5 million square feet, and 672 active campus acres**, with completion scheduled for 2028. It markets rack density of up to **1.4 kW per square foot**, N+1 mechanical/electrical redundancy, diverse utility feeds, and an on-site substation. ([Vantage campus page](https://vantage-dc.com/data-center-locations/north-america/port-washington-wisconsin); [Stargate Lighthouse announcement](https://vantage-dc.com/news/openai-oracle-and-vantage-data-centers-announce-stargate-data-center-site-in-wisconsin/))

Vantage owns approximately **1,644 acres**, while the tax-increment district spans about **1,674 acres**. Utility and environmental-review materials have contemplated as much as roughly **3.5 GW** over a longer horizon, and earlier concepts showed more buildings. Those are expansion envelopes. The bankable current program remains 902 MW across four buildings. Mixing the 3.5 GW optional horizon with the $15B four-building budget would create an artificially low and meaningless cost per GW. ([WPR review of the broader-site figure](https://www.wpr.org/news/lawsuit-wisconsin-dnr-environmental-review-port-washington-data-centers))

The commercial chain is:

1. **Vantage Data Centers** owns/develops/operates the campus. DigitalBridge and Silver Lake are its largest North American investors.
2. **Oracle Cloud Infrastructure** is the hyperscale tenant and cloud operator.
3. **OpenAI** is the Stargate compute customer.
4. **We Energies** provides retail electric service and procures/owns generation resources.
5. **American Transmission Company (ATC)** develops the high-voltage delivery upgrades.
6. The **City of Port Washington** supplies municipal approvals and the tax-increment financing framework.

The $15B Vantage number should therefore be treated as the owner/developer's powered-campus investment unless evidence shows that Oracle's accelerator purchases are included. No such evidence has appeared.

### Construction and permits

Physical construction began in **December 2025**. Foundation drilling for the first two buildings was underway in January 2026, and Vantage reported the second of those buildings structurally topped out on **June 26, 2026**, implying both initial frames had reached that milestone. The remaining two buildings follow in the phased program. ([Local construction report](https://www.ozaukeepress.com/content/vantage-marks-start-15b-data-center-project); [second-building top-out](https://www.datacenterdynamics.com/en/news/vantage-tops-out-second-building-at-openais-lighthouse-campus-in-wisconsin/))

Wisconsin DNR issued the principal wetland and stormwater approvals on **December 11, 2025** and a minor-source air permit on **June 12, 2026**. The air permit covers **45 diesel emergency generators**, with a reported annual fuel cap of about **324,000 gallons** and potential greenhouse emissions of approximately **48,500 tons per year**. These are backup units, not the primary 1.3 GW supply. ([Wisconsin DNR project page](https://dnr.wisconsin.gov/topic/EIA/Portwashington.html); [air-permit reporting](https://www.wpr.org/news/port-washington-residents-urge-dnr-to-deny-air-quality-permits-for-data-center))

Sierra Club Wisconsin, represented by Midwest Environmental Advocates, sued DNR on July 10, alleging that the agency should have prepared a full environmental impact statement before issuing those approvals. DNR prepared an environmental-analysis summary instead. The case is pending; the sources reviewed do not show an injunction stopping construction. Its near-term effect is legal uncertainty around the permit package, not a current shutdown. ([WPR report on the DNR lawsuit](https://www.wpr.org/news/lawsuit-wisconsin-dnr-environmental-review-port-washington-data-centers))

The building permits are not the project-wide critical path. High-voltage transmission is.

## Power and transmission

### 902 MW of IT versus a 1.3 GW grid request

Vantage discloses **902 MW critical IT**. Utility planning uses a **1.3 GW** requested service level. The difference is:

> 1,300 MW − 902 MW = **398 MW**

> 398 / 902 = **44.1%**

That 398 MW can include cooling, pumps, fans, power conversion losses, networking/non-critical loads, charging/storage, redundancy, reserve, and headroom for ramp/peak conditions. It is not valid to convert the ratio mechanically into a PUE of 1.44 because the denominators may be defined at different operating states and the 1.3 GW request may include contractual reserve. **No design or measured PUE has been published.**

At 90% utilization, the two denominators imply:

- critical IT energy: 0.902 GW × 8,760 × 90% = **7.11 TWh/year**;
- utility-input sensitivity: 1.3 GW × 8,760 × 90% = **10.25 TWh/year**.

### Transmission scope and reset

ATC's “Ozaukee County Area Transmission Project” is not a short interconnection spur. The filed alternatives involved roughly **90–107 miles** of new or rebuilt **345 kV and 138 kV** lines, **four or five new substations**, and modifications at four existing substations. ATC sought to begin construction in December 2026 and place the system in service by the end of 2027. ([Wisconsin PSC case page](https://psc.wi.gov/Pages/CommissionActions/CasePages/OzaukeeTransmission.aspx))

The estimated cost rose to approximately **$1.3–$1.7 billion**. Then ATC submitted hundreds of revisions. On **August 6, 2026**, the Public Service Commission unanimously revoked the application's completeness determination, closed docket **137-CE-221**, and required a new application rather than trying to evaluate a moving record containing **564 refiled or revised documents**. ([WPR report on the PSC decision](https://www.wpr.org/news/psc-denies-transmission-project-port-washington-data-center))

The accurate interpretation is:

- the PSC did **not** deny Vantage permission to operate the data center;
- it did **not** decide that no transmission route can be approved;
- it **did** erase the current review schedule and require ATC to restart with a coherent application;
- every month of refiling and renewed review compresses the end-2027 energization target.

This is the largest current schedule risk to the 2028 campus promise.

### Generation portfolio: nameplate is not firm energy

Vantage and We Energies say the utility will add **nearly 2 GW** of new energy resources, with roughly **70% associated with the campus and 30% available to other customers**. The portfolio language emphasizes solar, wind, and battery projects. Vantage says about 70% of its power will originate from zero-emission resources, with the remainder matched annually through renewable-energy purchases. ([Vantage Lighthouse announcement](https://vantage-dc.com/news/openai-oracle-and-vantage-data-centers-announce-stargate-data-center-site-in-wisconsin/))

Three disclosed 2026 projects include the **150 MW Dawn Harvest solar project plus 50 MW of battery capacity**, the **110 MW Badger Hollow wind project**, and a **75 MW Darien battery project**. These are part of We Energies' system-wide build for rapidly growing demand; the utility's August announcement does not allocate each project's MWh to Lighthouse. This is a real procurement/build program, but the units and accounting require care. ([We Energies construction announcement](https://news.we-energies.com/we-energies-launches-construction-on-solar-wind-and-battery-storage-projects/))

- 2 GW is **nameplate**, not 2 GW of 24/7 firm output.
- A battery's MW rating does not disclose its MWh duration.
- Annual renewable matching does not guarantee that Lighthouse is physically served by carbon-free electricity every hour.
- We Energies' broader reliability plan also includes gas generation; the exact Lighthouse-attributable share and cost are not isolated publicly.

The existing approximately **1.15 GW Port Washington Generating Station** is geographically adjacent, but proximity is not proof that it is contractually dedicated to Lighthouse. The campus is being served through the We Energies system and new dedicated network upgrades, not a disclosed behind-the-meter plant. ([We Energies station page](https://www.we-energies.com/company/port-washington-generating-station))

## Cooling and water

Vantage specifies a hybrid architecture: air-cooled heat rejection, liquid-to-liquid distribution, closed-loop chilled water, outside-air economization, and N+1 mechanical redundancy. It advertises water-usage effectiveness near zero. That design avoids the routine evaporation of a conventional cooling-tower campus and is technically consistent with dense liquid-cooled AI racks. ([Vantage technical specification](https://vantage-dc.com/data-center-locations/north-america/port-washington-wisconsin))

Two public water figures frame the design:

- a city fact sheet says the campus is expected to peak at about **22,000 gallons/day**, less than 2% of current city daily use; and
- the development/water framework reportedly permits a maximum of **1.2 million gallons/day** in extreme or contingency conditions.

([City fact sheet](https://www.portwashingtonwi.gov/home/showpublisheddocument/6430/638979481228470000); [reporting on the service ceiling](https://spectrumnews1.com/wi/milwaukee/news/2025/09/23/data-center-port-washington))

The expected peak is only about **8.0 million gallons/year** if it somehow occurred every day. The legal maximum is about 55 times larger. The gap does not prove expected use is misstated; a utility-service reservation can be designed for firefighting, fill events, abnormal heat, future phases, or conservative contingency. But Vantage has not published a design-day water balance that reconciles the two. Until it does, **22,000 gal/day is the design claim and 1.2M gal/day is the protected ceiling**.

Other missing cooling details include design PUE, liquid supply temperatures, CDU count, dry-cooler parasitic load, high-temperature derating, and the fraction of rack heat captured directly to liquid. “Near zero WUE” is not a substitute for those numbers.

## Financing structure

### Owner, tenant, and demand anchor

The project is financed across different corporate layers rather than a single Stargate project company:

- **Vantage** funds and owns the campus, backed principally in North America by **DigitalBridge and Silver Lake**.
- **Oracle** leases/uses the capacity and supplies the cloud and IT layer.
- **OpenAI** supplies the long-term compute demand under the broader Oracle Stargate relationship.
- **We Energies/ATC** finance regulated generation, substations, and transmission, recovering costs under tariffs subject to PSC oversight.

OpenAI and Oracle's broader five-year, more-than-$300B compute arrangement is an economic demand anchor, but no site-specific Lighthouse lease payment, capacity price, debt package, or OpenAI take-or-pay allocation has been disclosed.

The closest disclosed sponsor-level capital is Vantage's **$9.2 billion equity investment completed in June 2024**, led by DigitalBridge and Silver Lake. Along with other capital, Vantage said the raise would support about **$30 billion of development** across its platform. It is evidence that the sponsor has a large equity base, but it is not a Lighthouse-only equity commitment and cannot be assigned pro rata to Wisconsin. ([DigitalBridge financing announcement](https://www.digitalbridge.com/news/2024-06-13-vantage-data-centers-completes-92-billion-equity-investment-led-by-digitalbridge-and-silver-lake))

### Very-large-customer tariff and the $7 billion collateral requirement

In April 2026 Wisconsin approved a special We Energies tariff for customers above 100 MW. Its core purpose is to make the hyperscale customer—not ordinary ratepayers—bear the risk of dedicated assets becoming stranded. Credit support is tied to the net book value of dedicated generation and transmission and tightens when the customer falls below specified investment-grade ratings. ([We Energies tariff page](https://www.we-energies.com/payment-bill/very-large-customer-rate))

Oracle's rating is below the tariff's most favorable threshold. S&P cut the company to **BBB- on July 9**, one notch above speculative grade and well below the tariff's A- threshold. Oracle's own affidavit says the rule could require **more than $7 billion** of security, potentially as a letter of credit, with more than **$100 million per year** of carrying cost. Oracle proposed security closer to **10%**, roughly **$700 million**, and sought looser terms. The PSC declined reconsideration. Oracle then sued, but on **August 17 voluntarily dismissed the case**. The tariff's stronger credit-support rules therefore remain in force, and We Energies says it is working with Oracle to obtain the necessary collateral. ([WPR tariff report](https://www.wpr.org/news/we-energies-oracle-ask-state-regulators-to-loosen-financial-protections-for-data-centers); [Oracle drops the lawsuit](https://www.wpr.org/news/oracle-drops-wisconsin-suit-financial-requirements-data-centers))

The distinctions matter:

- **$7B is not the transmission estimate.** Transmission is currently $1.3–$1.7B.
- **$7B is not necessarily cash capex.** It is potential collateral/security exposure covering a broader dedicated utility-asset base.
- **The dispute is still material.** A multi-billion-dollar letter of credit consumes bank capacity and creates recurring fees even if never drawn.

The tariff is therefore both ratepayer protection and a financing condition for Stargate. Dismissal of the suit reduces legal uncertainty, but it does not disclose the form, amount, provider, or carrying cost of the collateral Oracle will actually post.

### Local tax-increment district

Port Washington created Tax Incremental District No. 5 around approximately **1,674 acres**. The district's project plan authorizes about **$458.6 million** of total expenditures, including up to **$455.4 million** of development-incentive reimbursements and roughly $3.15 million of administration/consulting. Vantage is expected to front eligible roads, water, wastewater, and other improvements and be repaid only from the site's future property-tax increment. The city says it does not issue general-obligation debt for the developer reimbursement. The district is projected to close in 18 years, with a 20-year maximum. ([TID No. 5 project plan](https://www.portwashingtonwi.gov/home/showpublisheddocument/6274/638962047469930000); [WPR TID report](https://www.wpr.org/news/port-washington-council-approves-tid))

Vantage's announcement highlights at least **$175 million** of local infrastructure investment. That is an initial/fronted program and overlaps the broader $455.4M reimbursement ceiling; it should not be added as a separate public subsidy. The TID plan projects about **$2.11 billion** of new taxable land and improvement value, far below the $15B total investment because servers and other personal property do not translate one-for-one into local real-property assessment.

### State sales/use-tax exemption

Wisconsin certified **Oracle America Cloud Services LLC (formerly Green Chile Ventures LLC)** for the Qualified Data Center sales and use tax exemption on October 31, 2025, at the four Lighthouse building addresses. Eligible categories can include servers, networking, fiber, substations, electricity, and cooling equipment. ([Wisconsin Department of Revenue exemption list and FAQ](https://www.revenue.wi.gov/Pages/FAQS/ExemptionforQualifiedDataCenter.aspx); [WEDC program description](https://wedc.org/programs/data-center-sales-and-use-tax-exemption/))

No public source states the eligible purchase base or foregone tax value. Vantage has said the exemption belongs to its tenant rather than the owner/operator. Any precise subsidy number would therefore be invented.

## Per-GW cost stack

### Disclosed and registered layers

| Cost layer | Public number | Per 902 MW critical IT | Per 1.3 GW utility request | Treatment |
|---|---:|---:|---:|---|
| Vantage powered campus | **>$15B** | **>$16.63B/GW** | **>$11.54B/GW** | Core disclosed capex; likely excludes Oracle IT |
| ATC transmission program | **$1.3–$1.7B** | **$1.44–$1.88B/GW** | **$1.00–$1.31B/GW** | Separate regulated-grid estimate; do not assume included in $15B |
| Local infrastructure, initial | **≥$175M** | **≥$0.19B/GW** | **≥$0.13B/GW** | Developer-fronted; overlaps TID ceiling and may overlap campus number |
| TID developer reimbursements | **≤$455.4M** | **≤$0.50B/GW** | **≤$0.35B/GW** | Future tax-increment reimbursement ceiling, not upfront city cash |
| Oracle tariff security | **potentially >$7B** | **>$7.76B/GW** | **>$5.38B/GW** | Collateral exposure, **not capex**; shown separately |
| State data-center tax exemption | Unknown | Unknown | Unknown | Eligible scope known; economic value undisclosed |
| Oracle IT hardware | Unknown | Unknown | Not applicable | No equipment budget disclosed |

The cleanest comparable metric is **at least $16.6B/GW of critical IT for the Vantage powered campus**. That sits above Abilene's companion-model powered-campus estimate of about $12.5B/GW and close to the Frontier campus headline of roughly $17.9B/GW. The comparison supports, but does not prove, that Vantage's $15B excludes the bulk of tenant accelerators.

Transmission raises the visible campus-plus-grid stack to roughly **$18.1–$18.5B/GW of critical IT** if the grid cost is incremental to the Vantage investment. Local infrastructure should not be blindly added again because some portion may already sit inside Vantage capex and the TID reimbursement base.

### All-in hardware scenario—not a forecast

Applying the Abilene companion-model hardware sensitivity of **$33.3B/GW** to 902 MW gives approximately **$30.0 billion** of IT hardware. Adding that scenario to the $15B Vantage campus gives an illustrative **$45.0 billion**, or **$49.9B/GW of critical IT**, before separately funded transmission.

That result is an order-of-magnitude Stargate system scenario, not a Lighthouse procurement disclosure. Accelerator mix, delivery cadence, depreciation, reuse, and whether the buildings open fully populated are all unknown.

### Annual electricity sensitivity

At 90% utilization:

| Denominator | Energy | Value at $40/MWh | Value at $80/MWh |
|---|---:|---:|---:|
| 902 MW critical IT | 7.11 TWh/year | **$284M/year** | **$568M/year** |
| 1.3 GW utility service | 10.25 TWh/year | **$410M/year** | **$820M/year** |

These are energy-value sensitivities, not the confidential tariff bill. Demand charges, dedicated-asset recovery, renewable contracts, collateral costs, and minimum-service obligations may matter as much as commodity energy.

## What the corporate language leaves out

1. **902 MW and 1.3 GW are different layers.** One is critical IT; the other is utility planning/service. The gap is not a published PUE.
2. **“Nearly 2 GW of new energy” is nameplate capacity.** It cannot be compared directly with a 24/7 AI load without capacity factors, storage duration, and firming resources.
3. **Annual renewable matching is not hourly physical supply.** The remaining load can still be served by the regional grid's thermal generation when renewables are unavailable.
4. **The transmission application has been reset.** “Under PSC review” understates the current state: the prior docket was closed and ATC must refile.
5. **The $7B figure is collateral, not cost.** It is economically important but must not be added to construction capex.
6. **The $455.4M TID is contingent reimbursement.** Vantage fronts costs; repayment comes only from tax increment generated inside the district.
7. **Near-zero cooling water does not erase a 1.2M gal/day entitlement ceiling.** The expected and legally protected cases are far apart and unreconciled publicly.
8. **The roughly 3.5 GW expansion discussion is not the committed campus.** The hard build is four buildings and 902 MW.

## Known, inferred, and unknown

### Known / registered

- Four single-story data-center buildings totaling 2.5M sq ft and 902 MW critical IT are under construction.
- The first two building structures had topped out by late June 2026.
- Vantage's disclosed investment is more than $15B and the target completion year is 2028.
- The utility is planning for a 1.3 GW service request.
- The ATC transmission application was reset and must be refiled.
- The transmission estimate is $1.3–$1.7B before any further redesign.
- The cooling design is closed-loop air/liquid, and the air permit covers 45 emergency diesel units.
- DNR's decision to issue approvals without a full environmental impact statement is being challenged in state court.
- The TID authorizes up to $455.4M of developer reimbursements from future tax increment.
- Oracle's four-building tenant project is certified for Wisconsin's qualified-data-center tax exemption.

### Strongly inferred

- Vantage's $15B is predominantly land, buildings, substations, and mechanical/electrical campus infrastructure rather than the complete Oracle accelerator fleet.
- The 1.3 GW utility request includes meaningful reserve/headroom beyond the 902 MW critical IT load.
- A clean 2028 full-campus completion is increasingly dependent on a very fast ATC refiling and PSC review.
- The roughly 3.5 GW figure is a long-run land/utility option rather than funded current scope.

### Unknown

- Design PUE, expected facility load at full 902 MW IT, and the binding contractual peak.
- Building-by-building MW and 2027–2028 energization ramp.
- Oracle lease rate and term, OpenAI's site-specific capacity commitment, and Vantage's debt/equity mix.
- Exact division of the $15B among land, shell, electrical, cooling, substation, and financing costs.
- Whether $15B includes any Oracle-furnished IT or ATC network cost.
- Final transmission route, final cost, revised in-service date, and cost allocation.
- Exact generation assets dedicated to Lighthouse, storage duration, hourly carbon-free percentage, and delivered power price.
- Expected versus worst-case water balance and the basis for the 1.2M gal/day ceiling.
- Value of the state sales/use-tax exemption.

## Falsifiers and next evidence to watch

1. **ATC's replacement transmission application**, including route, cost, construction start, and in-service date.
2. **A new PSC completeness finding** and the statutory review schedule that follows it.
3. **Proof of posted or approved credit support** under the very-large-customer tariff, including amount, form, bank/guarantor, and carrying cost.
4. **Building-level energization notices** showing how much of 902 MW arrives in each tranche.
5. **A disclosed PUE and design-day water balance** reconciling 22,000 gal/day with the 1.2M gal/day service ceiling.
6. **Generation PPAs or utility certificates** that identify the Lighthouse-attributable MW, MWh, storage duration, and cost.
7. **Vantage/Oracle financing disclosures** separating powered-campus capex, tenant hardware, regulated grid assets, and collateral.
8. **TID reimbursement statements** showing actual eligible costs and tax increment paid.
9. **The DNR environmental-review judgment**, especially any remand, permit stay, or requirement for a full environmental impact statement.

## Assessment

**Project reality: high. Construction schedule confidence: medium. Grid schedule confidence: low-to-medium. Cost transparency: medium for campus and transmission, low for IT and power-contract economics.**

Lighthouse has the clearest critical-IT denominator among the planned Stargate sites: **902 MW**, not a rounded corporate “about a gigawatt.” That makes its disclosed Vantage investment—**at least $16.6B/GW of critical IT**—a useful powered-campus benchmark. The likely all-in system cost becomes far larger only after the still-undisclosed accelerator layer is added.

The project is structurally advancing and its closed-loop cooling plan is credible. The weak link is upstream. A 1.3 GW service request depends on a regional-scale transmission rebuild whose initial regulatory record was so extensively revised that the Wisconsin PSC closed it and ordered a restart. The companion financing issue is equally concrete: the regulator requires Oracle to secure the dedicated utility assets so ratepayers do not absorb the exit risk. Oracle objected to the burden but has now dropped its court challenge, leaving execution of that security package—not the legal standard—as the remaining question.

The hard conclusion is therefore not that Lighthouse is stalled. It is that **the buildings are ahead of the wires**. Unless ATC quickly produces an approvable replacement filing and Oracle/We Energies settle the credit-support structure, the physical campus can remain on schedule while the usable megawatts slip.
