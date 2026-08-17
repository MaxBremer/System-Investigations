---
title: Stargate Abilene — Per-GW Cost Stack
date: 2026-08-03
status: research-v1
tags:
  - systems-investigation
  - ai-infrastructure
  - datacenters
  - stargate
  - project-finance
investigation: 001-AI-Datacenters
---

# Stargate Abilene — Per-GW Cost Stack

**As of August 3, 2026**

## Bottom line

A defensible public estimate can be built for the flagship Abilene campus, but it is a **two-layer stack**, not one disclosed project budget:

| Layer | Full 1.2 GW campus | Per GW | Confidence |
|---|---:|---:|---|
| Powered buildings, cooling, electrical plant and site development | $15.0B | **$12.5B/GW** | High that this is the development-JV total; low on its internal breakdown |
| Oracle's reported Nvidia hardware purchase | ~$40.0B | **~$33.3B/GW** | Medium; reported by the *Financial Times*, not disclosed by Oracle as a campus BOM |
| **Combined initial capital** | **~$55.0B** | **~$45.8B/GW** | Medium-low as a precise total; useful as an order-of-magnitude estimate |

This is remarkably close to Stargate's program-wide headline ratio of **$500B / 10 GW = $50B/GW**. It suggests that the $500B headline is economically plausible if it means fully equipped AI capacity—not merely land and buildings. It does **not** prove that $500B is committed, funded, or free of double counting.

The biggest cost is not concrete or electricity. It is the short-lived compute equipment. Roughly 73% of the reconstructed initial stack is hardware, and 27% is the powered campus.

## What is actually being built

The base campus consists of eight buildings on Lancium's site:

- Lancium supplies the powered site and a **1.2 GW ERCOT-approved grid interconnection**, plus power orchestration and planned on-site resources ([Lancium](https://lancium.com/locations/)).
- Crusoe designs, builds and operates the campus. The first two buildings were announced as **206 MW and 998,000 square feet**; the completed eight-building campus is described as **1.2 GW** ([initial phase](https://www.crusoe.ai/resources/newsroom/crusoe-blue-owl-capital-primary-digital-joint-venture), [full buildout](https://www.crusoe.ai/resources/newsroom/crusoe-blue-owl-capital-and-primary-digital-infrastructure-enter-joint-venture)).
- Blue Owl, Primary Digital Infrastructure and Crusoe sponsor the real-estate joint venture; bank debt supplies most of its capital.
- Oracle leases the campus, installs and operates the IT systems, and sells the compute to OpenAI.
- OpenAI is the ultimate anchor customer. Parts of the campus began training and inference workloads in 2025; OpenAI said in April 2026 that GPT-5.5 was trained there ([OpenAI](https://openai.com/index/building-the-compute-infrastructure-for-the-intelligence-age/)).

The separate 600 MW expansion once proposed near Abilene was shelved in March 2026. That does not change the eight-building, 1.2 GW base used here ([Reuters](https://www.reuters.com/business/oracle-openai-end-plans-expand-texas-data-center-site-bloomberg-news-reports-2026-03-06/)).

## 1. Powered-campus capital: $12.5B/GW

The campus owners announced a **$15B joint venture to fund the 1.2 GW data center**. Normalized:

> $15.0B / 1.2 GW = **$12.5B per GW**

The announcement does not divide this into land, shell, substations, switchgear, backup power, cooling, fiber, construction labor or developer margin. Accordingly, **$12.5B/GW is the smallest reliable public bucket** for the physical facility; a more granular Abilene-specific facility stack cannot presently be built without speculation.

The first phase provides a useful cross-check:

| Facility phase | Capacity | Capital | Normalized |
|---|---:|---:|---:|
| First two buildings | 206 MW | $3.4B | $16.5B/GW |
| Full eight buildings | 1.2 GW | $15.0B | $12.5B/GW |

The lower full-campus ratio may reflect shared infrastructure and scale economies, but it may also reflect rounded capacities or a changing definition of what the announced capital covers. It should not be read as a measured 24% construction-cost decline.

At the building level, the full-campus capitalization averages **$1.875B per building**. The first two average $1.7B each; the additional six average about $1.93B each. This consistency supports—but does not prove—that the $15B figure is principally a full-campus real-estate and mechanical/electrical budget.

### How the facility is financed

Public financing announcements indicate:

| Phase | Total capital | Construction debt | Implied equity/other capital |
|---|---:|---:|---:|
| First two buildings | $3.4B | $2.3B | ~$1.1B |
| Six-building expansion | $11.6B additional | $7.1B | ~$4.5B |
| **Total** | **$15.0B** | **~$9.4B** | **~$5.6B** |

Newmark announced the [$2.3B first-phase construction loan](https://www.nmrk.com/insights/press-releases/newmark-arranges-2-3-billion-construction-financing-for-206-mw-build-to-suit-data-center) and the [$7.1B second-phase loan](https://www.nmrk.com/insights/press-releases/newmark-facilitates-7-1-billion-construction-loan-to-develop-ai-data-center), both led by JPMorgan lender groups. On those rounded figures, the campus is approximately **63% debt-funded and 37% equity/other capital**, equal to about **$7.85B of facility debt and $4.65B of equity per GW**.

The actual interest rate, amortization, lease rate and Oracle guarantees are not public. A sensitivity—not a claim about the loan terms—puts annual interest on $9.4B of debt at:

| Assumed interest rate | Campus interest/year | Per GW-year |
|---:|---:|---:|
| 6% | ~$565M | ~$471M |
| 7% | ~$659M | ~$549M |
| 8% | ~$754M | ~$628M |

This is gross interest on the eventual debt balance. Construction-period draws, capitalized interest, principal repayment and refinancing make actual cash flows different.

## 2. Compute hardware: approximately $33.3B/GW

The *Financial Times* reported that Oracle planned to spend roughly **$40B for about 400,000 Nvidia GB200 chips** for Abilene and lease the resulting compute to OpenAI for 15 years ([FT](https://www.ft.com/content/a9cd130f-f6bf-4750-98cc-19d87394e657)). Normalized:

> $40B / 1.2 GW = **$33.3B/GW**  
> $40B / 400,000 = **$100,000 per reported chip**

This figure should be treated as a reported systems-purchase estimate, not a literal retail GPU price. A GB200 deployment includes Grace CPUs, Blackwell GPUs, memory, rack-scale NVLink equipment and supporting components; the report does not publish Oracle's precise configuration or contract pricing. It is also unclear how much external networking, storage and installation is included.

Crusoe says each of the eight buildings can operate up to 50,000 Nvidia GB200-class units, consistent at a high level with the reported 400,000-chip campus total. It is not an engineering bill of materials. For example, the initial claim of 206 MW supporting up to 100,000 GPUs implies 2.06 kW of facility capacity per GPU, while 1.2 GW divided by 400,000 implies 3.0 kW. The public maxima and capacity labels are therefore not precise enough to infer PUE or rack design.

### Hardware replacement is the dominant recurring economic cost

If the $33.3B/GW hardware layer is economically consumed over four to six years, the annual capital consumption is:

| Assumed economic life | Hardware cost consumed per GW-year |
|---:|---:|
| 4 years | ~$8.3B |
| 5 years | ~$6.7B |
| 6 years | ~$5.6B |

This is not necessarily Oracle's accounting depreciation schedule, and the equipment may remain physically functional much longer. It expresses the economic problem: accelerator price/performance can make a cluster commercially old well before the 15-year customer contract or the much longer building life ends.

## 3. Electricity: roughly $0.3B-$0.6B per GW-year

One GW running continuously consumes 8.76 TWh per year. At a 90% average facility load:

> 1 GW × 8,760 hours × 90% = **7.884 TWh/GW-year**

Because the campus power-purchase contracts, hedges, transmission charges and on-site generation economics are private, the most honest result is a sensitivity table:

| All-in electricity assumption | Cost per GW-year at 90% load | Cost for 1.2 GW campus |
|---:|---:|---:|
| $40/MWh | $315M | $378M |
| $60/MWh | $473M | $568M |
| $80/MWh | $631M | $757M |

ERCOT publishes granular day-ahead and real-time settlement prices, but those spot prices are not Oracle's delivered cost ([ERCOT](https://www.ercot.com/mktinfo/prices)). Lancium says the site combines its grid connection with nearby wind, on-site gas generation, and planned behind-the-meter battery and solar resources ([Lancium](https://lancium.com/2025/03/18/crusoe-expands-ai-data-center-campus-in-abilene-to-1-2-gigawatts/)). The ownership and capital cost of those resources are not separately disclosed, so adding generic power-plant costs on top of the $15B campus figure risks double counting.

Electricity is therefore substantial, but far smaller than hardware turnover. At the midpoint above, power is about **$0.47B/GW-year**, versus **$5.6B-$8.3B/GW-year** of hardware capital consumption.

## 4. Taxes, labor, maintenance and networking: real but not publicly separable

These categories cannot be responsibly assigned Abilene-specific dollar values from current public disclosures:

- **Property tax:** The City of Abilene lists executed phase-by-phase tax-abatement agreements, but the eventual taxable values, eligibility dates and ownership of each asset class require a parcel/entity-level tax model ([City of Abilene](https://abilenetx.gov/2476/Tax-Abatements)).
- **Sales tax:** Texas offers temporary state sales-tax exemptions for qualifying data-center equipment, while local use taxes can remain due. Qualification and the exact purchasing entities matter ([Texas Comptroller](https://comptroller.texas.gov/taxes/data-centers/)).
- **Operations and maintenance:** Crusoe is the physical operator and Oracle the cloud operator, but neither discloses campus staffing, maintenance contracts, spare-parts inventory, insurance or security costs.
- **External fabric and storage:** The $40B Nvidia estimate may not include all cross-building optics, switches, storage and host systems. If excluded, the reconstructed $45.8B/GW is a floor rather than a complete total.
- **Land and interconnection:** Lancium's land acquisition, engineering and interconnection work are economically essential, but public materials do not show whether all of their cost is embedded in Crusoe's $15B JV or recovered separately through site and power agreements.

## Reconstructed unit economics

### Initial capital per 1 GW

| Item | Per GW | Share of reconstructed total |
|---|---:|---:|
| Powered campus | $12.5B | 27% |
| Nvidia hardware | ~$33.3B | 73% |
| **Reconstructed total** | **~$45.8B** | **100%** |

### Illustrative annual capital burden per 1 GW

This is an economic-cost view, not reported annual cash expense:

| Item | Illustrative per GW-year |
|---|---:|
| Hardware consumption (4-6 years) | $5.6B-$8.3B |
| Facility interest sensitivity (6-8%) | $0.47B-$0.63B |
| Electricity (90% load, $40-$80/MWh) | $0.32B-$0.63B |
| Facility depreciation, maintenance, labor, taxes, insurance | Not publicly measurable |

Even before the unknown categories, the system must recover approximately **$6.3B-$9.6B per GW-year** during the early hardware generation merely to cover hardware consumption, facility interest and electricity. This is not the revenue Oracle must report—principal, equity returns, cloud operating margin and utilization losses also matter—but it shows the scale of the revenue engine required.

## What this changes in the system model

1. **The Stargate headline is less arbitrary than it first appears.** Abilene's reconstructed fully equipped cost is about $46B/GW, close to the program's $50B/GW headline ratio.
2. **“Data-center cost” is an ambiguous phrase.** The landlord's $12.5B/GW facility and Oracle's ~$33.3B/GW IT layer belong to different entities, financing structures and asset lives.
3. **Hardware, not power, dominates the near-term economics.** Power is the physical bottleneck, but accelerator obsolescence is the larger dollar risk once capacity is energized.
4. **Long contracts bridge incompatible asset lives.** A 15-year OpenAI compute relationship supports financing for buildings that may last decades, while the productive hardware may require several replacement cycles.
5. **The risk ultimately concentrates downstream.** Blue Owl and lenders look primarily to Oracle's lease; Oracle looks to OpenAI's compute payments; OpenAI must convert the capacity into sufficiently high-margin model and product revenue.

## Confidence and unresolved questions

**Overall confidence: Medium on the broad ratio; low on a precise all-in total.**

High-confidence inputs are the 1.2 GW capacity, $15B development JV, eight-building plan and announced construction loans. The $40B hardware layer is credible financial reporting but lacks a public Oracle contract or component schedule. Annual power, operating and tax costs remain scenarios rather than observations.

The most useful next documents would be:

1. Oracle's Abilene lease term, rent escalators, guarantees and equipment-financing structure.
2. The campus power-supply agreements and the split between grid, gas, wind, solar and storage.
3. Texas sales-tax registrations and Taylor County appraisal records for each Abilene DC entity.
4. A rack-level GB200 deployment count that distinguishes GPUs, Superchips and NVL72 systems.
5. Oracle's actual utilization and revenue per energized MW, rather than planned nameplate capacity.

