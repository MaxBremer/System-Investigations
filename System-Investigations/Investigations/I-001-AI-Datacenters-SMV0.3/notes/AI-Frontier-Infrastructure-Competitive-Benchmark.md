---
title: "Frontier AI Infrastructure Competitive Benchmark: Stargate versus Hyperion, Rainier, Fairwater, and Colossus"
date: 2026-08-21
status: research-v1
type: comparative-system-report
tags:
  - ai-infrastructure
  - datacenters
  - capital-stack
  - power
  - frontier-ai
---

# Frontier AI Infrastructure Competitive Benchmark

## Stargate versus Hyperion, Rainier, Fairwater, and Colossus

**Research cutoff:** August 21, 2026  
**Scope:** U.S. physical and financial infrastructure for Meta Hyperion, AWS Project Rainier/New Carlisle, Microsoft Fairwater/Wisconsin, and xAI/SpaceXAI Colossus. Google/TPU is treated only as a follow-up signal. Lordstown is excluded.

## Reading guide and evidence discipline

The report uses three labels:

- **Fact** — directly disclosed by a company, regulator, financing party, government body, or SEC filing.
- **Derivation** — arithmetic from disclosed inputs; the input scopes and denominators are stated.
- **Inference** — an analytical conclusion from the disclosed structure. It is not presented as a contractual fact.

“Operational” means equipment is in service, not merely a completed building. “IT GW” means power delivered to information-technology equipment. It is not interchangeable with facility load, utility service capacity, or generation nameplate capacity. A headline dollar amount is not divided by a headline GW figure unless the scopes plausibly match.

## 1. Executive findings

### Bottom line

The Stargate model is **not a universal frontier-AI capital structure**, but neither is it an isolated oddity. The broader market is converging on a common physical stack while using several distinct financing regimes.

1. **The physical stack generalizes; the ownership stack does not.** Every program must assemble land, high-density shell/MEP, power, accelerators/network, and financing on different useful lives. What differs is whether one balance sheet owns the stack, a hyperscaler leases the long-lived layers, or multiple intermediaries transform an AI laboratory's demand into financeable claims.

2. **Stargate's powered-campus cost does not look obviously anomalous.** The existing Stargate control range is roughly **$12.5–18.5B per powered-campus GW**. Hyperion's financed initial long-lived infrastructure is about **$27B for more than 2 GW of compute capacity**, implying **less than $13.5B per stated initial compute GW** before accelerators. That is near the low end of Stargate, not an order of magnitude below it. It also does not establish a total cost advantage because Meta's accelerators and network are outside the $27B vehicle. [Meta's JV disclosure](https://investor.atmeta.com/investor-news/press-release-details/2025/Meta-Announces-Joint-Venture-with-Funds-Managed-by-Blue-Owl-Capital-to-Develop-Hyperion-Data-Center/default.aspx) and [Meta's capacity description](https://datacenters.atmeta.com/richland-parish-data-center/) support the inputs.

3. **No competitor publishes enough matched data to falsify the $43–52B/Stargate-IT-GW total directly.** AWS does not disclose Rainier's IT load or internal Trainium cost. Microsoft discloses investment and architecture but not Wisconsin IT MW or a hardware/building split. xAI's Mississippi announcement implies a much lower, roughly **$20B per incremental announced compute GW**, but it combines a rounded investment commitment, a brownfield conversion, leased GPU assets, and a future cluster denominator. This is evidence worth pursuing, not an apples-to-apples refutation.

4. **Stargate is unusually dependent on credit transformation, not uniquely financialized.** Meta's Hyperion vehicle is more visibly project-financed than many Stargate sites: Blue Owl owns 80%, the JV uses private debt, Meta leases every facility, and Meta supplies a 16-year capped residual-value guarantee. xAI has a $5.4B GPU acquisition-and-lease vehicle and a separately financed 900 MW power JV. Microsoft has a very large corporate-wide pipeline of uncommenced datacenter leases. Financialization is a sector feature. Stargate's distinction is that the financing chain must bridge from infrastructure investors and Oracle to an ultimate customer, OpenAI, that historically lacked hyperscaler cash flow and physical ownership.

5. **Legal ownership often overstates risk transfer.** Blue Owl legally owns most of Hyperion's long-lived infrastructure, but Meta manages construction, takes all space, owns 20%, and backstops residual value. The JV therefore transfers funding and some terminal-value exposure while leaving much of the utilization and economic downside with Meta. At xAI, Valor investors own compute assets, yet a triple-net lease pushes operating obligations and customer-credit dependence back toward xAI/SpaceXAI.

6. **AWS/Rainier is the cleanest custom-silicon control, but not a public cost benchmark.** Rainier is operational across multiple U.S. datacenters with nearly 500,000 Trainium2 chips; Anthropic now uses more than one million Trainium2 chips across its AWS deployment. AWS owns and co-designs chip, server, network, software, and datacenter. This can remove an external accelerator vendor's gross margin and improve system utilization, but public “price-performance” claims are customer-price claims—not manufacturing-cost or capital-cost disclosures. [AWS's Rainier architecture description](https://www.aboutamazon.com/news/aws/aws-project-rainier-ai-trainium-chips-compute-cluster) is explicit about vertical integration and multi-site scope.

7. **OpenAI's position is structurally unusual and economically important.** Amazon, Meta, and Microsoft can monetize a campus through diversified, existing platforms and fund it from investment-grade corporate cash flow. OpenAI typically buys compute through a provider such as Oracle while others own the real estate, GPUs, and power systems. That separation makes provider credit, long-term contracts, leases, and project debt more central. xAI originally resembled this startup-led profile, but its February 2026 acquisition by SpaceX and subsequent third-party compute contracts changed the risk pool.

8. **Power is now a separate capital system.** Hyperion requires a utility buildout of more than 5.2 GW of new combined-cycle generation, about 240 miles of 500 kV transmission, batteries, nuclear uprates, and potential renewables, all structured for Meta to bear its cost. xAI's 900 MW prime-power system sits in a customer/energy-company JV with its own secured debt. Indiana and Wisconsin have special very-large-load tariffs designed to prevent stranded assets from migrating to other ratepayers. Power is no longer merely “C inside datacenter capex”; it has its own owners, debt, regulation, contracts, and stranded-asset risk.

### Hypothesis scorecard

| Hypothesis | Verdict | Why |
|---|---|---|
| 1. Stargate is unusually expensive | **Unresolved; weakly supported for NVIDIA-heavy full stack, not established for powered campus** | Hyperion's powered-campus ratio overlaps Stargate. AWS and Microsoft lack matched denominators. xAI suggests a lower mixed/full-stack cost but with major scope and maturity caveats. |
| 2. Stargate is unusually financialized | **Supported only in a relative sense** | Corporate balance-sheet builds remain important, especially AWS and site-specific Microsoft. But Meta, xAI, utilities, and Microsoft's broader lease book show that external capital and long-dated contracts are widespread. |
| 3. OpenAI's position is structurally unusual | **Strongly supported** | OpenAI is usually the ultimate compute customer without owning the stack or possessing the same diversified investment-grade cash engine as a hyperscaler. Oracle and other intermediaries transform that demand into financeable obligations. |
| 4. Power is becoming a separate capital system | **Strongly supported** | Hyperion and Colossus make this explicit; large-load tariffs in Indiana and Wisconsin contractually isolate load risk. |

## 2. Stargate control model

The control is the repository's [consolidated Stargate capital-stack model](https://github.com/MaxBremer/System-Investigations/blob/main/System-Investigations/Investigations/I-001-AI-Datacenters-SMV0.3/notes/AI%20Stargate-Consolidated-Capital-Stack-Model.md), [Abilene per-GW cost stack](https://github.com/MaxBremer/System-Investigations/blob/main/System-Investigations/Investigations/I-001-AI-Datacenters-SMV0.3/notes/AI%20Abilene%20Campus%20Per-GW%20Cost%20Stack.md), and [Stargate system report](https://github.com/MaxBremer/System-Investigations/blob/main/System-Investigations/Investigations/I-001-AI-Datacenters-SMV0.3/notes/AI%20Stargate%20Project%20System%20Report.md).

### Control cost ranges

**Fact / prior model:** The repository estimates:

- powered campus: **$12.5–18.5B/GW**;
- initial compute and network: about **$33B/GW** where Abilene evidence permits estimation;
- initial full stack: roughly **$43–52B/IT-GW**, with the consolidated bottom line concentrated at **$46–52B/GW**.

**Representative derivation — Abilene:**

$$
\text{Powered campus} = \$15B / 1.2\text{ GW} = \$12.5B/\text{GW}
$$

$$
\text{Compute/network proxy} = \$40B / 1.2\text{ GW} = \$33.3B/\text{GW}
$$

$$
\text{Initial full stack} = (\$15B + \$40B) / 1.2\text{ GW} = \$45.8B/\text{GW}
$$

The 1.2 GW denominator is advertised campus capacity and is not always explicitly defined as IT rather than facility power. That ambiguity remains in the control itself.

### Control ownership and financing pattern

The recurring Stargate chain is:

1. a powered-land developer controls the site and initial interconnection;
2. a campus owner or SPV funds shell and MEP with project debt and infrastructure equity;
3. Oracle, or a site-specific provider such as Milam, leases facility capacity;
4. Oracle generally finances and operates NVIDIA compute/network and sells compute to OpenAI;
5. utilities or energy SPVs own generation and transmission; special contracts, collateral, or minimum payments protect those assets;
6. OpenAI bears much of the ultimate utilization risk through long-term compute demand while owning little of the physical stack.

**Inference:** Stargate is best understood as a credit-transformation system. The physical asset by itself is not enough. A lender wants a credible tenant; the campus owner wants a long lease; the compute provider wants a long compute commitment; the utility wants protection against stranded capacity. Oracle's balance sheet and contracts convert OpenAI demand into financeable claims at several layers.

### The benchmark question

The relevant comparison is not “who announced the smallest dollars per GW?” It is:

> For each layer, who supplies capital, who owns the asset, who guarantees cash flow, and who absorbs loss if AI demand or hardware value disappoints?

## 3. Meta Hyperion / Richland Parish, Louisiana

### Physical scale and status

**Fact:** Meta describes Richland Parish as a campus that will deliver **more than 2 GW of compute capacity** in its initial development and potentially **5 GW** at ultimate buildout. Construction is well underway, but the initial campus is not yet disclosed as operational. Meta's 5 GW and $50B-plus figures describe an expanded regional master plan, not a single financed phase. [Meta project page](https://datacenters.atmeta.com/richland-parish-data-center/)

**Fact:** The original utility plan called for 2,260 MW of new combined-cycle generation, two Entergy-owned substations, six customer-owned substations, nearly 100 miles of 500 kV line, and eight new 230 kV lines. The March 2026 expansion framework grew this to seven combined-cycle plants totaling more than 5,200 MW, about 240 miles of 500 kV transmission, batteries, nuclear uprates, and support for up to 2,500 MW of renewables. Generation and transmission are expected to arrive in phases rather than as one 5 GW energization event. [Entergy's original infrastructure plan](https://www.entergy.com/news/entergy-louisiana-power-meta-s-data-center-in-richland-parish) and [expanded agreement](https://www.entergy.com/news/entergy-louisiana-announces-a-new-agreement-with-meta-that-will-deliver-an-additional-2b-in-customer-savings)

**Status classification:**

| Item | Status at cutoff |
|---|---|
| Initial long-lived campus infrastructure | **Financed; construction underway** |
| Initial >2 GW compute capacity | **Under construction; not yet disclosed as operational** |
| Ultimate 5 GW | **Announced/master plan; utility buildout proposed and phased** |
| Accelerators/network | **Platform families disclosed at company level; site quantity and installed status not public** |
| New generation/transmission | **Contracted/regulatory-development stage; phased 2028–2031-era delivery** |

### Capital cost by layer

#### A–C. Land, shell/MEP, and long-lived power/connectivity

**Fact:** A Meta/Blue Owl joint venture will develop and own Hyperion. Blue Owl-managed funds own 80%; Meta owns 20%. The parties committed pro rata funding for approximately **$27B** of “buildings and long-lived power, cooling, and connectivity infrastructure.” Meta contributed land and construction-in-progress, Blue Owl contributed about $7B cash, and Meta received a one-time distribution of about $3B. [Meta JV announcement](https://investor.atmeta.com/investor-news/press-release-details/2025/Meta-Announces-Joint-Venture-with-Funds-Managed-by-Blue-Owl-Capital-to-Develop-Hyperion-Data-Center/default.aspx)

**Derivation — initial powered-campus ceiling:**

$$
\$27B / 2\text{ stated compute GW} = \$13.5B/\text{GW}
$$

**Classification:** **Strongly derived for the disclosed initial long-lived-infrastructure vehicle; medium confidence as a powered-campus comparison.** The numerator is unusually clear, but the denominator is phrased as compute capacity and the boundary between campus electrical infrastructure and utility-owned infrastructure is not fully reconciled. Because capacity is “over” 2 GW, $13.5B/GW is a ceiling, not a point estimate.

The 5 GW/$50B-plus headline produces a tempting $10B/GW ratio, but it is not usable as a financed initial cost. The numerator is a broad future commitment and the denominator is an ultimate master plan. It may also contain different layer boundaries from the $27B JV.

#### D. Accelerators and network

**Fact:** The $27B JV description explicitly covers buildings and long-lived power, cooling, and connectivity—not accelerator fleets. Meta designs and operates its infrastructure and has disclosed company-wide deployments of NVIDIA GB200 and GB300 systems, but it has not disclosed the Hyperion accelerator count, purchase price, or site-specific network cost. [Meta infrastructure engineering overview](https://engineering.fb.com/2025/09/29/data-infrastructure/metas-infrastructure-evolution-and-the-advent-of-ai/)

**Inference:** Meta or a wholly controlled affiliate, not the Blue Owl real-estate JV, is the likely economic owner of the accelerator and AI-network layer. That inference is strong because the JV's enumerated assets are long-lived infrastructure while Meta is the sole user and operator. The precise legal title to every server or financing arrangement remains undisclosed.

#### E. Financing costs

**Fact:** A portion of Blue Owl's capital is funded with private debt sold to PIMCO and other bond investors. Contemporary transaction reporting described roughly $27B of debt and a smaller equity tranche, but Meta's release does not publish the debt's coupon, maturity, amortization, debt-service coverage, or exact final capital stack. [Meta disclosure](https://investor.atmeta.com/investor-news/press-release-details/2025/Meta-Announces-Joint-Venture-with-Funds-Managed-by-Blue-Owl-Capital-to-Develop-Hyperion-Data-Center/default.aspx) and [PIMCO transaction counsel disclosure](https://www.gtlaw.com/en/news/2025/10/press-releases/greenberg-traurig-represents-pimco-in-massive-debt-financing-deal-for-hyperion-data-center-project)

**Classification:** Financing cost per GW is **unknown**. Reported debt size is not interest expense and should not be added to development cost.

### Ownership and obligations

| Layer | Legal owner / operator | Funding | Economic obligation |
|---|---|---|---|
| Land and construction in progress | Contributed by Meta to Hyperion JV | Meta contribution, then JV capital | Meta has 20% equity and manages construction/property |
| Buildings, cooling, campus connectivity | Hyperion JV; Blue Owl 80%, Meta 20% | JV equity plus private debt | Meta leases all facilities |
| Utility generation and transmission | Primarily Entergy Louisiana | Utility investment under Meta-specific agreements | Meta is to pay full cost of service and fund the buildout |
| Customer-side substations/campus electrical | Mix of JV/customer assets | JV/Meta | Dedicated to Meta campus |
| Accelerators and AI network | Not specifically disclosed; economically Meta-controlled | Likely Meta corporate capital or equipment arrangements | Meta bears technology and utilization economics |

**Fact:** Meta entered operating leases for every facility, initially four years with extension options. To make that short formal term financeable, Meta supplied a capped residual-value guarantee for the first 16 years if specified conditions follow non-renewal or termination. [Meta JV announcement](https://investor.atmeta.com/investor-news/press-release-details/2025/Meta-Announces-Joint-Venture-with-Funds-Managed-by-Blue-Owl-Capital-to-Develop-Hyperion-Data-Center/default.aspx)

### What the structure accomplishes

**Inference:** Hyperion externalizes capital for four reasons without meaningfully externalizing Meta's strategic control:

1. **Capital recycling.** Meta contributed land and work in progress, received a $3B distribution, and shifted most future long-lived-infrastructure funding to a specialist pool.
2. **Asset-life matching.** Long-duration private capital and debt fund buildings and electrical/cooling systems; Meta can reserve corporate capital for short-lived accelerators, R&D, and buybacks.
3. **Option design.** Four-year lease terms give Meta formal flexibility as AI designs evolve, while the 16-year residual guarantee makes the option bankable.
4. **Balance-sheet and execution capacity.** The JV adds a parallel funding channel for a campus too large to treat as routine annual capex, even for Meta.

This is not a clean transfer of utilization risk. Meta is the sole tenant, the construction/property manager, a 20% owner, the accelerator buyer, the party paying the dedicated utility costs, and the residual guarantor. Blue Owl and lenders hold legal asset and financing exposure, but their underwriting is substantially an exposure to Meta's credit and performance.

### If AI demand disappoints

- **Meta:** primary utilization risk; accelerator obsolescence; power minimums/full-cost obligations; construction performance; 20% equity; and capped residual guarantee.
- **Blue Owl equity:** residual value beyond the guarantee cap/conditions, financing and timing risk, plus exposure to Meta renewal behavior.
- **PIMCO and other lenders:** project/refinancing risk, strongly mitigated by Meta-linked lease and guarantee cash flows.
- **Entergy:** construction and operating performance of utility assets, with stranded-cost exposure intended to be shifted to Meta rather than other ratepayers.

### Comparison to Stargate

Hyperion **looks like Stargate in a legal-entity diagram**—SPV, infrastructure equity, private debt, tenant leases—but is economically different. Meta itself supplies equity, construction expertise, sole occupancy, residual support, utility cost support, and the compute monetization engine. Stargate more often requires Oracle and other intermediaries to stand between infrastructure capital and OpenAI demand. Hyperion is capital optimization by an investment-grade principal; Stargate is capital assembly around a customer that does not own the stack.

## 4. AWS + Anthropic Project Rainier / New Carlisle, Indiana

### Physical scale and status

**Fact:** AWS says Project Rainier is **fully operational**, was deployed in under a year, contains nearly **500,000 Trainium2 chips**, and spans multiple U.S. datacenters. St. Joseph County, Indiana, is one of the Rainier locations; the full cluster must not be assigned entirely to New Carlisle. [AWS Rainier announcement](https://www.aboutamazon.com/news/aws/aws-project-rainier-ai-trainium-chips-compute-cluster)

**Fact:** AWS originally announced an **$11B** investment in St. Joseph County over a decade. By July 2026, AWS said local investment had reached **$13.8B** and local reporting counted roughly 30 buildings, 18 operating and the balance under construction. The investment figure is cumulative program spending, not a disclosed full-stack cost for a specified IT load. [AWS Indiana announcement](https://www.aboutamazon.com/news/aws/aws-indiana-investment-11-billion) and [July 2026 site update](https://www.wndu.com/2026/07/23/amazon-web-services-investment-st-joseph-county-data-center-campus-surpasses-138-billion/)

**Fact / secondary planning synthesis:** Public planning and utility records indicate a roughly 2.2–2.25 GW ultimate utility-service envelope for the New Carlisle campus. This is a grid/facility denominator, not disclosed IT load. It should be treated as a planning estimate rather than an AWS-published Rainier IT figure. [New Carlisle planning synthesis](https://measuredai.substack.com/p/aws-new-carlisle-data-center-campus)

**Status classification:**

| Item | Status at cutoff |
|---|---|
| Rainier multi-site Trainium2 cluster | **Operational** |
| New Carlisle campus | **Partly operational, partly under construction** |
| Nearly 500,000 Rainier Trainium2 chips | **Operational across multiple U.S. sites** |
| Up to 5 GW new Amazon/Anthropic capacity | **Contracted framework; not all New Carlisle and not all built** |
| Ultimate New Carlisle ~2.2 GW utility service | **Planning/utility envelope; IT load undisclosed** |

### Capital cost: what can and cannot be derived

Two ratios are arithmetically possible and analytically unsafe:

$$
\$11B / 2.2\text{ utility GW} \approx \$5.0B/\text{utility GW}
$$

$$
\$13.8B / 2.2\text{ utility GW} \approx \$6.3B/\text{ultimate utility GW}
$$

**Classification:** **Speculative / insufficient evidence; not a cost benchmark.** The $11B was a decade-long announcement already exceeded by cumulative spending. The $13.8B is spending to date on an unfinished campus. Neither source separates land, buildings, electrical systems, Trainium servers, network, or capitalized costs. The denominator is ultimate utility capacity rather than current IT capacity. These ratios are therefore retained only to show why headline division misleads.

#### D. Custom silicon economics

**Fact:** Rainier uses 64-chip Trainium2 UltraServers, NeuronLink scale-up connections, and AWS Elastic Fabric Adapter scale-out networking. AWS states that it controls the stack from chip and software through server and datacenter design. [AWS Rainier architecture](https://www.aboutamazon.com/news/aws/aws-project-rainier-ai-trainium-chips-compute-cluster)

**Fact:** AWS has advertised Trainium2 instances as offering 30–40% better price-performance than current-generation GPU EC2 instances. That is an AWS customer-service claim; it is not a disclosed die cost, server bill of materials, or capital cost per GW. [Trainium2 general availability announcement](https://press.aboutamazon.com/2024/12/aws-trainium2-instances-now-generally-available)

**Inference:** Vertical integration can improve economics through four channels:

- avoiding a third-party accelerator vendor's gross margin;
- co-designing silicon, racks, fabric, cooling, and compiler;
- retaining both cloud-service margin and silicon-system margin;
- redeploying capacity among Anthropic, Bedrock, AWS customers, and Amazon's own models.

But Amazon also internalizes risks that Stargate distributes: design failure, yield and supply-chain exposure, generation-to-generation obsolescence, software adoption, and residual value. Public sources do not disclose enough to quantify net hardware $/GW or useful-compute/$.

### Ownership and financing

**Fact / inference:** New Carlisle is a conventional AWS corporate development: AWS controls the land/buildings, datacenter systems, Trainium servers, and network, and funds deployment through Amazon's corporate capital program. No project-level construction debt, external real-estate JV, or site sale-leaseback was found in the reviewed public documentation. Absence of public project debt is not proof that no equipment lease or vendor credit exists, but the disclosed program is materially more integrated than Stargate or Hyperion.

**Fact:** In April 2026 Anthropic committed **more than $100B over ten years** to AWS technologies for up to **5 GW** of capacity spanning Trainium2 through Trainium4 and Graviton, with nearly 1 GW of Trainium2/3 capacity expected by year-end 2026. Amazon simultaneously invested another $5B in Anthropic, adding to $8B previously invested, with up to $20B more contemplated. [Anthropic/Amazon agreement](https://www.anthropic.com/news/anthropic-amazon-compute)

**Derivation — contract envelope, not capex:**

$$
\$100B / 10\text{ years} / 5\text{ GW} = \$2B/\text{GW-year}
$$

This is a minimum average cloud-spend envelope only if the full 5 GW is delivered and used. It is not a capital cost; it includes service economics over time and may cover multiple generations and regions.

### Circularity and risk allocation

Amazon's equity investment and Anthropic's AWS commitment create a partial circular flow:

$$
\text{Amazon capital} \rightarrow \text{Anthropic} \rightarrow \text{AWS compute spend} \rightarrow \text{Amazon revenue}
$$

This does not make the revenue fictitious: Anthropic also raises outside capital and sells Claude services, while AWS delivers real infrastructure. It does mean the customer relationship cannot be evaluated independently of Amazon's strategic investment and cloud economics.

Anthropic is analogous to OpenAI as an anchor frontier-model customer, but the physical risk allocation differs:

- **Anthropic** bears contractual spend and model-demand risk.
- **Amazon** owns the whole stack, bears Trainium and datacenter residual risk, and retains material utilization risk if Anthropic's demand falls.
- **AWS's mitigation** is fungibility: capacity can serve Bedrock, other customers, and Amazon workloads. Oracle-Stargate capacity is more concentrated around a specific OpenAI demand chain.
- **Power risk** is contractually separated through the utility tariff rather than a dedicated off-grid project.

### Power model

**Fact:** Indiana Michigan Power's approved large-load framework requires long-term financial commitments and regulatory review for material load reductions, with the stated purpose of protecting other customers. [I&M tariff announcement](https://www.indianamichiganpower.com/company/news/view?releaseID=10036)

More detailed public-record synthesis reports a 12-year initial term, minimum billing around 80% of contracted demand, collateral, and large exit exposure for a 1 GW customer. Because the exact customer-specific service agreement is not public, these terms are best treated as tariff-level risk architecture, not a disclosed AWS take-or-pay invoice. [IURC tariff reporting](https://www.utilitydive.com/news/indiana-iurc-large-load-interconnection-data-center-aep-amazon-google/740452/)

**Inference:** The utility and grid legally own much of the power system, while the tariff makes AWS the economic absorber of demand shortfall. This is a separate capital system even in an otherwise vertically integrated campus.

## 5. Microsoft Fairwater / Mount Pleasant, Wisconsin

### Physical scale, architecture, and status

**Fact:** Microsoft announced an initial **$3.3B** Wisconsin cloud-and-AI investment in May 2024, followed by a second approximately **$4B** facility of similar scale, bringing the announced Mount Pleasant program above $7B through 2028. [Initial Microsoft announcement](https://news.microsoft.com/source/2024/05/08/microsoft-announces-3-3-billion-investment-in-wisconsin-to-spur-artificial-intelligence-innovation-and-economic-growth/) and [Wisconsin Economic Development Corporation expansion announcement](https://wedc.org/gov-evers-microsoft-officials-announce-new-4-billion-investment-in-mount-pleasant-datacenter/)

**Fact:** Microsoft declared the first Wisconsin facility fully operational on June 23, 2026, after bringing equipment online and beginning startup activities in April. The adjacent second facility is under construction for scheduled completion in 2028. Microsoft estimates $4.7B of local hyperscale construction spending from 2024 through 2028, a narrower construction-economy measure that should not be substituted for the broader $7B-plus infrastructure commitment. [Microsoft operational announcement](https://news.microsoft.com/source/2026/06/23/microsoft-completes-construction-on-first-datacenter-facility-in-mount-pleasant-wisconsin/)

**Fact:** Fairwater uses NVIDIA GB200 NVL72 systems, high-density liquid cooling with almost no operating water consumption, and a dedicated AI wide-area network. Wisconsin and Atlanta are nodes in a distributed “AI superfactory” rather than isolated training campuses. Microsoft says the network supports OpenAI, Microsoft AI, Copilot, and other workloads. [Microsoft Fairwater architecture](https://news.microsoft.com/source/features/ai/from-wisconsin-to-atlanta-microsoft-connects-datacenters-to-build-its-first-ai-superfactory/)

**Capacity caveat:** Microsoft has not published Wisconsin IT MW. Third-party facility estimates place the first building around **338 MW facility capacity**, while Wisconsin power-policy analysis has cited roughly **450 MW peak load** for the first phase. Neither is a verified IT-load denominator. The responsible entry in a common IT-GW table is therefore “unknown,” with 0.34–0.45 GW retained only as a secondary facility/peak range. [Facility estimate](https://cleanview.co/data-centers/wisconsin/3968/microsoft-fairwater-b1-mke03) and [Wisconsin power analysis](https://www.cleanwisconsin.org/clear-as-mud/)

**Status classification:**

| Item | Status at cutoff |
|---|---|
| First Wisconsin Fairwater facility | **Operational** |
| Second adjacent facility | **Under construction; target 2028** |
| 15-building northern expansion | **Locally approved/planned; not equivalent to financed or energized** |
| Official Wisconsin IT GW | **Not disclosed** |

### Capital cost: disclosed inputs and invalid comparisons

Using the secondary facility/peak range against the initial $3.3B announcement gives:

$$
\$3.3B / 0.45\text{ GW} = \$7.3B/\text{facility-GW}
$$

$$
\$3.3B / 0.338\text{ GW} = \$9.8B/\text{facility-GW}
$$

If the second facility is indeed similar scale, its $4B announcement would imply roughly $8.9–11.8B per facility-GW on the same unverified denominator.

**Classification:** **Estimated, low confidence, mixed scope—and not an initial full-stack $/IT-GW.** The investment announcements combine cloud/AI infrastructure and do not separate land, shell/MEP, power, GPUs, network, or capitalized software. The denominator is not official IT load. These ratios cannot establish that Fairwater costs one-fifth as much as Stargate; they mainly demonstrate missing disclosure.

Microsoft's stated $4.7B of local hyperscale construction through 2028 is also not a substitute numerator because it is a local-purchase/construction measure spanning two facilities and may exclude imported servers and networking.

### Ownership and financing

**Fact / strong inference:** Public land and planning records identify Microsoft-controlled parcels, while Microsoft describes itself as builder and operator and directly specifies the GB200, cooling, and network architecture. No Wisconsin site-level project debt, infrastructure-fund JV, or real-estate sale-leaseback was found. Fairwater Wisconsin is therefore the closest case to a **corporate-balance-sheet, vertically integrated hyperscaler build** in this benchmark.

That does not mean Microsoft never externalizes datacenter capital. Its 2026 annual report disclosed **$329.1B of uncommenced leases**, primarily for datacenters, with commencements expected across fiscal 2027–2033, in addition to already recognized operating- and finance-lease liabilities. Those are corporate-wide obligations and cannot be assigned to Wisconsin. [Microsoft 2026 Form 10-K](https://www.sec.gov/Archives/edgar/data/789019/000119312526323660/msft-20260630.htm)

**Inference:** The correct conclusion is two-level:

- **Site-specific:** Fairwater Wisconsin appears self-funded and owned by Microsoft.
- **Portfolio-wide:** Microsoft is combining owned sites with a very large future lease pipeline, so the hyperscaler model is not synonymous with universal on-balance-sheet ownership.

### Power system

**Fact:** Microsoft has said it will prepay electrical infrastructure associated with Wisconsin development. We Energies' new Very Large Customer rate applies to loads above 100 MW and was approved with a customer-protection structure intended to prevent costs from shifting to other customers or shareholders. [Reuters on Wisconsin expansion and prepayment](https://www.reuters.com/business/microsoft-boosts-wisconsin-data-center-spending-7-billion-2025-09-18/) and [We Energies rate summary](https://www.we-energies.com/payment-bill/very-large-customer-rate)

**Fact:** A separate 250 MW Portage Solar power-purchase agreement with Microsoft is expected online in 2027. The project developer/owner operates the solar asset; a PPA does not make Microsoft the generation owner. [Portage Solar PPA announcement](https://geronimopower.com/press-release/national-grid-renewables-signs-power-purchase-agreement-with-microsoft/)

**Inference:** Wisconsin follows a grid-plus-contract model:

- We Energies owns and finances regulated generation/network assets;
- Microsoft prepays or contractually supports customer-specific infrastructure;
- special tariffs shift stranded-load risk toward the large customer;
- independent power producers own some contracted generation;
- Microsoft owns the datacenter-side electrical/cooling system.

### If demand disappoints

- **Microsoft:** utilization, GPU/network residual value, campus sunk cost, power prepayment/contract risk, and the opportunity cost of corporate capital.
- **We Energies/shareholders/ratepayers:** regulated construction and operating risk, with tariff protections designed to isolate demand shortfall from ordinary customers.
- **PPA developer:** construction and generation-performance risk; Microsoft supplies offtake credit.
- **OpenAI:** demand and service-contract exposure at the workload layer, but not necessarily ownership of the Wisconsin assets.

### Comparison to Oracle in Stargate

Microsoft does not need an Oracle-like credit transformer for Fairwater. It is simultaneously land controller, campus developer, compute owner, operator, network owner, and diversified seller of Azure/Copilot/OpenAI-related capacity. Oracle in Stargate more often finances hardware and leases a third-party-owned campus to serve a concentrated outside customer. The physical hardware may look similar; the chain of claims is shorter at Fairwater.

## 6. xAI / SpaceXAI Colossus and Colossus II, Memphis–Southaven

### Physical scale and current corporate boundary

**Fact:** SpaceX acquired xAI in February 2026. SpaceX's IPO filing defines Colossus as the Paul R. Lowry Road facility in Memphis and Colossus II as the Memphis and Southaven facilities forming a coherent gigawatt-scale training cluster. The filing states that Colossus and Colossus II collectively provide approximately **1.0 GW of compute power**, with additional power capacity available. [SpaceX S-1/A](https://www.sec.gov/Archives/edgar/data/1181412/000162828026040364/spaceexplorationtechnologib.htm)

**Fact:** The Mississippi Development Authority announced a Southaven brownfield conversion called MACROHARDRR with corporate investment exceeding **$20B**, expected operations beginning in February 2026, and a target of taking the broader cluster to nearly **2 GW of compute** upon completion. The state approved a sales/use-tax exemption for computing equipment and software; city and county fee-in-lieu arrangements also support the project. [Mississippi Development Authority announcement](https://mississippi.org/news/tech-leader-xai-investing-more-than-20-billion-in-southaven/)

**Fact:** The original 785,000-square-foot former Electrolux plant was bought by Phoenix Investors in late 2023 and leased to xAI. A Phoenix affiliate sold the 217-acre Colossus I property to a SpaceX subsidiary for **$185M** in May 2026. This shows a progression from leased brownfield shell to affiliated ownership, not a single original greenfield build. [Phoenix project history](https://phoenixinvestors.com/acquisitions-updates/former-electrolux-facility-to-house-one-of-the-worlds-largest-supercomputers/) and [sale announcement](https://finance.yahoo.com/markets/stocks/articles/affiliate-phoenix-investors-sells-memphis-190000497.html)

**Status classification:**

| Item | Status at cutoff |
|---|---|
| Colossus + Colossus II current compute | **Approximately 1.0 GW operational, per SEC filing** |
| Southaven MACROHARDRR | **Brownfield purchased/retrofitted; operations begun or ramping; ultimate completion not established** |
| Nearly 2 GW cluster | **Announced completion target, not current operational capacity** |
| 900 MW Stateline prime-power system | **Contracted and substantially deployed/earning; staged power system** |

### Capital cost by layer

#### A–B. Land and shell/MEP

**Fact:** xAI repeatedly selected existing industrial buildings and a former power-plant site, then retrofitted them at high speed. The $185M Colossus I purchase price is a land/building transfer after conversion and does not measure the cost of datacenter MEP already installed. Southaven's project investment includes much more than the acquired shell.

**Inference:** Brownfield reuse reduces land-acquisition and shell schedule relative to a multi-million-square-foot greenfield campus, but it can increase retrofit complexity, constrain layout/redundancy, and obscure capital cost because building value, tenant improvements, and compute equipment arrive under different owners and dates.

#### C. Power

**Fact:** In April 2025 Solaris Energy Infrastructure formed Stateline Power, LLC with CTC Property, an affiliate of the AI customer. Solaris contributed assets and prefunded expenses valued around $86.4M for 50.1%; CTC was to contribute about $86M cash for 49.9%. The JV expanded to approximately **900 MW** of primary power under a seven-year arrangement. It closed a **$550M senior secured facility** in 2025. [Solaris Q1 2025 Form 10-Q](https://www.sec.gov/Archives/edgar/data/1697500/000169750025000026/sei-20250331x10q.htm) and [Solaris Q2 2025 results](https://ir.solaris-energy.com/news/2025/07-23-2025-233414289)

**Fact:** Solaris explicitly warns that it could struggle to find alternative lessors for generation equipment dedicated to Stateline if the rental agreement terminates. The power provider therefore retains asset remarketing risk even though the customer owns 49.9% and supports demand. [Solaris Form 10-Q](https://www.sec.gov/Archives/edgar/data/1697500/000169750025000026/sei-20250331x10q.htm)

**Fact:** Colossus also uses MLGW/TVA grid service and temporary/mobile gas generation. Environmental groups and the NAACP have challenged unpermitted turbine operation in Tennessee and Mississippi; an April 2026 suit alleged operation of 27 turbines at Colossus II without required Clean Air Act permits. These allegations are contested legal claims, not final liability findings, but they are economically relevant because permitting speed and compliance risk were part of the deployment model. [Reuters on the Mississippi lawsuit](https://www.reuters.com/sustainability/climate-energy/naacp-sues-musks-xai-alleging-illegal-operation-gas-turbines-2026-04-14/)

#### D. Accelerators and network

**Fact:** Apollo-managed funds led a **$3.5B capital solution** for Valor Compute Infrastructure to acquire and lease **$5.4B** of compute infrastructure, including NVIDIA GB200 GPUs, to an xAI subsidiary. NVIDIA invested as an anchor limited partner. The structure is a triple-net lease, and Valor investors retain ownership of the compute assets and receive cash distributions plus asset upside. [Apollo transaction announcement](https://ir.apollo.com/news-events/press-releases/detail/599/apollo-backs-5-4-billion-valor-and-xai-data-center-compute)

**Fact:** SpaceX's S-1 classifies certain AI-infrastructure arrangements as failed sale-leasebacks and financing liabilities for accounting purposes. Legal title and cash-flow form therefore do not necessarily produce off-balance-sheet accounting or genuine risk transfer. [SpaceX S-1/A](https://www.sec.gov/Archives/edgar/data/1181412/000162828026040364/spaceexplorationtechnologib.htm)

**Inference:** The GPU stack is mixed economically:

- some equipment is financed/owned through Valor vehicles;
- xAI/SpaceXAI is lessee/operator and bears the obligation to monetize the cluster;
- Valor equity and lenders retain counterparty and hardware-residual exposure;
- NVIDIA participates both as supplier and investor, aligning sales with financing capacity.

The public record does not allocate the $5.4B vehicle to an exact IT-MW denominator, so no defensible compute $/GW can be calculated from it.

#### Mixed full-stack proxy

The current SEC filing reports about 1.0 GW of compute. The Southaven program is announced to take the cluster to nearly 2 GW, implying approximately 1 incremental GW. Against a greater-than-$20B project investment:

$$
{>}\$20B / \left(\sim2\text{ GW target} - \sim1\text{ GW current}\right) \approx {>}\$20B/\text{incremental announced GW}
$$

**Classification:** **Estimated, low-to-medium confidence, mixed/full-stack proxy.** The numerator is a state economic-development figure that likely includes computing equipment eligible for tax exemption, building retrofit, and other investment. It may count assets financed by third parties. The denominator is an ultimate compute target, not independently measured energized IT load. The result is materially below Stargate's $43–52B/GW control, but it is not yet comparable enough to declare a twofold cost advantage.

### Speed: cost advantage or risk acceptance?

Colossus achieved unusual deployment speed through a bundle of choices:

- brownfield shells rather than a fully sequenced greenfield campus;
- mobile/behind-the-meter generation ahead of complete grid buildout;
- separate asset financing for GPUs and power;
- concentrated vendor architecture;
- tolerance for permitting, environmental, noise, and community-litigation risk;
- potentially less design standardization and redundancy than a long-lived hyperscaler template.

**Inference:** Speed is partly purchased by moving risks forward in time. The model creates option value—usable compute months or years before a conventional utility interconnection—but it can leave later costs in remediation, permitting, fuel exposure, refinancing, equipment integration, and community opposition. “Built faster” is not synonymous with “built cheaper on a lifecycle basis.”

### Demand risk changed after the SpaceX merger

The initial cluster was built for Grok and xAI, making xAI the concentrated self-user. By 2026, SpaceX had a profitable connectivity segment, a public capital market, and disclosed third-party compute agreements, including Anthropic and Google arrangements in its amended S-1. That creates external revenue support and lets the group monetize capacity beyond Grok. [SpaceX S-1/A](https://www.sec.gov/Archives/edgar/data/1181412/000162828026040364/spaceexplorationtechnologib.htm)

The risk chain is now:

- **SpaceX/SpaceXAI:** primary utilization, integration, operating, power-contract, regulatory, and business-model risk; GPU lease/financing obligations remain even if Grok underperforms.
- **External compute customers:** contract and workload-migration risk; their agreements can support utilization but may include termination flexibility.
- **Valor/Apollo/NVIDIA investors:** xAI/SpaceXAI counterparty risk plus GPU residual and refinancing risk.
- **Solaris/Stateline lenders:** equipment performance, fuel, contract, and remarketing risk; customer equity and contract mitigate but do not eliminate it.
- **Local utilities/communities:** grid and externality exposure, with legal disputes showing that some social/environmental cost was not fully resolved before energization.

### Comparison to Stargate

xAI is not an unfinancialized startup that simply paid cash and moved faster. It is heavily structured at the hardware and power layers, much like Stargate, but with different intermediaries and sequencing. The key differences are brownfield speed, partial customer ownership of the power JV, GPU-focused asset leasing, and—after February 2026—access to the broader SpaceX balance sheet and external compute customers.

## 7. Common comparison

The table deliberately leaves cells unknown when the public numerator and denominator do not match.

| Metric                        | Stargate control                                                                 | Meta / Hyperion                                                                              | AWS + Anthropic / Rainier                                                              | Microsoft / Fairwater WI                                                                        | xAI / Colossus                                                                                                             |
| ----------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Representative project        | Abilene plus consolidated U.S. model                                             | Richland Parish, LA                                                                          | Rainier / New Carlisle, IN                                                             | Mount Pleasant, WI                                                                              | Memphis, TN + Southaven, MS                                                                                                |
| Operational IT GW             | Exact IT basis unresolved; Abilene advertises ~1.2 GW campus capacity            | 0 disclosed; construction underway                                                           | Unknown; Rainier fully operational but multi-site                                      | Unknown officially; first facility operational; secondary 0.34–0.45 GW is facility/peak, not IT | ~1.0 GW compute across Colossus/II (SEC)                                                                                   |
| Under-construction IT GW      | Multi-site pipeline; not reduced to one comparable figure here                   | >2 GW stated compute phase                                                                   | Unknown IT; New Carlisle buildings still under construction                            | Unknown IT; second similar facility under construction                                          | Roughly 1 incremental GW implied by nearly-2-GW target                                                                     |
| Ultimate announced IT GW      | 10 GW program envelope; not a single financed campus                             | 5 GW compute master plan                                                                     | Up to 5 GW Amazon/Anthropic overall; New Carlisle ~2.2 GW is utility planning envelope | No official Wisconsin IT figure; Fairwater network described as multi-GW                        | Nearly 2 GW regional compute target                                                                                        |
| Powered-campus $/GW           | **$12.5–18.5B/GW**                                                               | **< $13.5B/stated initial compute GW** for $27B long-lived infrastructure; medium confidence | Unknown; $5.0–6.3B/ultimate utility-GW headline ratios are invalid/mixed               | Unknown; $7–12B/facility-GW ratios are mixed-scope and low confidence                           | Unknown; brownfield shell and power are financed separately                                                                |
| Compute/network $/GW          | **~$33.3B/GW** Abilene proxy                                                     | Unknown; outside $27B JV                                                                     | Unknown; internal Trainium cost and IT power undisclosed                               | Unknown                                                                                         | Unknown; $5.4B GPU vehicle lacks MW denominator                                                                            |
| Total initial $/IT-GW         | **~$43–52B/GW**; Abilene $45.8B/GW                                               | Unknown                                                                                      | Unknown                                                                                | Unknown                                                                                         | **>~$20B/incremental announced compute GW** mixed proxy; not comparable                                                    |
| Accelerator platform          | NVIDIA, including GB200-class initial stacks                                     | Meta fleet includes NVIDIA GB200/GB300; Hyperion exact mix unknown                           | Trainium2 now; contracted Trainium2–4; custom Neuron/EFA fabric                        | NVIDIA GB200 NVL72                                                                              | NVIDIA mix including GB200 in financed vehicle                                                                             |
| Land/building owner           | Developer/campus SPV by site                                                     | Hyperion JV: Blue Owl 80%, Meta 20%                                                          | AWS                                                                                    | Microsoft at Wisconsin, based on public record                                                  | Initially Phoenix landlord at Colossus I; now SpaceX subsidiary; other brownfield assets xAI affiliates                    |
| Compute owner                 | Typically Oracle/provider, not OpenAI                                            | Likely Meta/economic control; exact legal detail undisclosed                                 | AWS                                                                                    | Microsoft                                                                                       | Mix of SpaceXAI and Valor-owned leased assets                                                                              |
| Power owner                   | Utilities and energy SPVs; site-specific                                         | Entergy generation/T&D; JV/customer assets inside campus                                     | I&M/grid utility; AWS customer-side equipment                                          | We Energies/grid plus independent PPA assets and Microsoft internal equipment                   | Stateline JV, grid utilities, and xAI-owned power-site assets                                                              |
| Primary financing             | Project debt/equity + leases + provider balance sheet                            | Highly levered JV/private debt; Meta 20% equity and guarantees                               | Amazon corporate capex; long-term Anthropic cloud commitment                           | Microsoft corporate capex at site; large broader lease pipeline                                 | SpaceX/xAI capital + GPU asset finance + power-JV debt/equity                                                              |
| External lenders/investors    | Banks, infrastructure funds, developers, utilities; Oracle as credit transformer | Blue Owl, PIMCO, other private bond investors                                                | None disclosed at site; Amazon also equity investor in Anthropic                       | None disclosed at Wisconsin site; utilities/IPP fund power assets                               | Valor, Apollo, NVIDIA LP, Solaris, Stateline lenders                                                                       |
| Ultimate compute customer     | OpenAI concentrated                                                              | Meta itself                                                                                  | Anthropic anchor, plus AWS fungibility/Bedrock                                         | OpenAI, Microsoft AI, Copilot, Azure and other workloads                                        | Grok/SpaceXAI plus disclosed external compute customers                                                                    |
| Primary demand-risk bearer    | OpenAI ultimately; Oracle/provider bears intermediary contract/asset risk        | Meta                                                                                         | Anthropic contractually and Amazon residually                                          | Microsoft                                                                                       | SpaceX/SpaceXAI; increasingly offset by external customers                                                                 |
| Primary residual-value bearer | Owners/lenders by layer; Oracle on GPU economics; OpenAI through contracts       | Meta on GPUs and capped campus guarantee; Blue Owl beyond guarantee                          | Amazon                                                                                 | Microsoft                                                                                       | Valor/financiers legally on leased GPUs; SpaceXAI economically through obligations; Stateline/Solaris on power remarketing |
| Power model                   | Utility and/or dedicated generation with tariffs, collateral, contracts          | Massive regulated utility build paid by Meta                                                 | Grid utility with large-load tariff                                                    | Grid + prepayment/VLC tariff + PPA                                                              | Grid plus behind-the-meter/mobile gas generation and power JV                                                              |
| Cost-estimate confidence      | Medium; best evidence at Abilene, denominator still imperfect                    | Medium for long-lived infrastructure; no full stack                                          | Low/insufficient for cost; high for architecture/status                                | Low/insufficient for cost; high for architecture/status                                         | Low-to-medium for mixed announced proxy; high for disclosed finance structures                                             |

## 8. Cross-case cost analysis

### The evidence ladder

| Case | Usable numerator | Usable denominator | Calculation | Classification | What it proves |
|---|---|---|---|---|---|
| Stargate / Abilene | $15B powered campus; $40B compute proxy | 1.2 GW advertised campus | $12.5B/GW powered; $33.3B/GW compute; $45.8B/GW total | Strongly derived within control, medium confidence | A financed NVIDIA-heavy site can reach mid-$40B/GW initial stack |
| Hyperion initial JV | $27B buildings + long-lived power/cooling/connectivity | >2 GW stated compute | < $13.5B/GW | Strongly derived; medium confidence | A Meta-backed powered campus overlaps the low Stargate range |
| Hyperion ultimate | >$50B broad investment | 5 GW ultimate compute | ~$10B/GW naive | Insufficient | Master-plan headlines are not financed full-stack cost |
| New Carlisle | $11B announced / $13.8B spent to date | ~2.2 GW ultimate utility envelope | ~$5.0B / ~$6.3B per utility-GW | Speculative/invalid | Nothing reliable about IT-GW or layer cost |
| Fairwater first | $3.3B broad cloud/AI program | 0.338–0.45 GW secondary facility/peak | ~$7.3–9.8B/facility-GW | Estimated, low confidence, mixed | Disclosure gap; not proof of low full-stack cost |
| Colossus Southaven increment | >$20B project investment | ~1 incremental announced compute GW | >~$20B/incremental GW | Estimated, low-to-medium confidence, mixed | A brownfield/leased-asset model may be materially cheaper, but scope needs audit |

### What can be said responsibly

**Powered-campus conclusion:** Hyperion's best available comparable does **not** show Stargate to be uniquely expensive. Its < $13.5B/GW ceiling sits inside or just below the Stargate $12.5–18.5B/GW band. Large, high-density, long-lived infrastructure appears expensive even when backed by Meta.

**Compute conclusion:** The roughly $33B/GW Stargate compute proxy remains untested. Competitors do not publish matched accelerator quantity, network cost, installed IT power, and purchase price. Rainier may reduce cost per useful compute, but electrical GW is an especially poor output metric when comparing Trainium2 with GB200/GB300.

**xAI conclusion:** The Southaven proxy is the strongest signal of a potentially lower total stack. It could reflect brownfield reuse, a different redundancy standard, used/older and newer GPU mixes, separate third-party asset ownership, tax treatment, and deployment at a different point on the hardware price curve. Until the $20B investment schedule, GPU inventory, and energized IT load are reconciled, it should be modeled as a scenario, not a benchmark point.

### Useful-compute normalization is the missing layer

Electrical $/GW answers, “What capital is attached to a power envelope?” It does not answer, “What training or inference output does that capital buy?” A better cross-platform metric would be:

$$
\frac{\text{annualized capital + power + operations}}{\text{useful training tokens, accepted inference tokens, or workload-normalized FLOP}}
$$

That denominator must adjust for precision, model architecture, communication overhead, compiler maturity, utilization, failure recovery, and workload mix. None of the four programs publishes enough data for it. AWS's custom-silicon case makes this limitation impossible to ignore.

## 9. Ownership and financing comparison

The cases form a continuum rather than two categories.

| Model | Case | Capital logic | What is actually transferred? |
|---|---|---|---|
| Vertically integrated corporate build | AWS/New Carlisle; site-specific Microsoft/Fairwater | Investment-grade balance sheet owns land through compute | Little legal asset risk transfer; utility risk remains contractually separate |
| Guaranteed infrastructure JV | Meta/Hyperion | External capital owns long-lived assets; hyperscaler leases and guarantees | Funding source and some terminal value, but much economic risk stays with Meta |
| Multi-party credit transformation | Stargate | Developers, SPVs, lenders, Oracle, and utilities fund layers around OpenAI demand | Ownership and financing spread broadly; ultimate demand remains concentrated |
| Asset-lease + power-JV hybrid | xAI/Colossus | Lease GPUs, reuse shells, co-own separate generation, later fold into SpaceX | Capital and some residual risk externalized; utilization, operations, regulation stay concentrated |

### Financing is not the same as risk transfer

Three recurring structures create misleading surface impressions:

1. **Operating lease plus residual guarantee:** legal ownership leaves the tenant, but terminal-value risk partly returns through the guarantee.
2. **Triple-net equipment lease:** an investor owns the asset, but taxes, maintenance, insurance, and fixed payments sit with the user; failed-sale-leaseback accounting can confirm financing substance.
3. **Utility ownership plus large-load tariff:** the utility owns generation/transmission, while minimum bills, collateral, exit fees, or prepayment shift stranded-demand economics to the datacenter customer.

The model should therefore record four different roles for every layer:

| Role | Question |
|---|---|
| Legal owner | Whose name is on the asset? |
| Capital provider | Whose cash/debt funded it? |
| Cash-flow guarantor/offtaker | Who must pay if use is low? |
| Residual-risk bearer | Who loses if the asset cannot be reused or refinanced? |

## 10. Power comparison

| Case | Physical power system | Legal capital owner | Demand-shortfall protection | Core risk |
|---|---|---|---|---|
| Stargate | Mix of regulated grid, dedicated generation, transmission, substations | Utilities and site/energy SPVs | Leases, collateral, tariffs, minimum payments; site-specific | Interconnection timing and concentrated load |
| Hyperion | >5.2 GW new CCGT at ultimate framework; 500 kV lines, batteries, nuclear uprates, possible renewables | Entergy for regulated assets; campus JV/customer for internal assets | Meta pays full cost; long-term customer-specific agreements | Enormous build before ultimate 5 GW load is proven |
| Rainier/New Carlisle | I&M grid expansion and campus substations/backup | Utility plus AWS internal assets | Large-load tariff, long-term commitments, review of load reductions | Grid build and capacity ramp; contract terms protect ratepayers |
| Fairwater/Wisconsin | We Energies grid, customer-specific infrastructure, 250 MW solar PPA | Utility, independent generator, Microsoft internal assets | Prepayment and >100 MW VLC customer-protection rate | Utility generation expansion and portfolio load forecast |
| Colossus | TVA/MLGW grid plus mobile/on-site gas and 900 MW prime-power JV | Utility + Stateline JV + xAI affiliates | Seven-year power arrangement, customer 49.9% JV equity, secured debt | Fuel/permitting/emissions, equipment remarketing, short deployment cycle |

### Power-capital conclusion

Power has the defining properties of a separate project-finance asset class:

- a different regulatory regime from datacenter construction;
- asset lives longer than GPU generations;
- its own lenders, equity owners, tariffs, offtake agreements, and collateral;
- a separate completion schedule that can strand either GPUs or generation;
- environmental and community liabilities not captured in server capex;
- potential reuse value that depends on transmission topology and local demand.

Hyperion and Colossus show the two poles. Hyperion waits for and supports a massive regulated utility expansion. Colossus brings modular generation to the load and accepts more fuel, permitting, and externality risk to gain time. Both separate power capital from compute capital.

## 11. Risk-allocation comparison

### Who loses if frontier-compute demand disappoints?

| Risk | Stargate | Hyperion | Rainier | Fairwater | Colossus |
|---|---|---|---|---|---|
| Utilization | OpenAI ultimately; Oracle/provider contractually | Meta | Anthropic under commitment; Amazon on residual utilization | Microsoft across own/OpenAI/Azure workloads | SpaceXAI, partly offset by external customers |
| Customer credit | Oracle and project counterparties exposed to OpenAI; lenders exposed through Oracle | Blue Owl/lenders exposed mainly to Meta credit | Amazon exposed to Anthropic; mitigated by equity alignment and AWS fungibility | Microsoft primarily self-credit; external customer receivables diversified | Valor/Stateline counterparties exposed to SpaceXAI/SpaceX and external contracts |
| Stranded building | Campus owners/equity, mitigated by leases | Blue Owl/Meta JV; Meta guarantee first 16 years | Amazon | Microsoft | SpaceXAI after property acquisition; initially Phoenix landlord |
| GPU residual | Oracle/provider owners, indirectly OpenAI through price/term | Meta | Amazon | Microsoft | Valor/financiers legally; SpaceXAI economically through lease/financing obligations |
| Technology obsolescence | Oracle/provider plus OpenAI contract | Meta | Amazon takes custom-silicon and system risk | Microsoft | SpaceXAI plus Valor residual holders |
| Power contract | OpenAI/provider/site-specific counterparties | Meta | AWS | Microsoft | SpaceXAI/Stateline plus Solaris remarketing exposure |
| Refinancing | Project SPVs, Oracle, infrastructure owners | Hyperion JV/Blue Owl | Mostly Amazon corporate | Mostly Microsoft corporate at site; lease counterparties elsewhere | Valor/SpaceXAI/Stateline/Solaris |
| Regulatory/environmental | Site owners/operators/utilities | Meta/Entergy | AWS/utility | Microsoft/utility | SpaceXAI and turbine/power operators; unusually salient |

### Concentration versus fungibility

The most important risk mitigant is not nominal scale; it is **whether compute can be redirected**.

- AWS can redirect Trainium and datacenter capacity among Anthropic, Bedrock, internal models, and other AWS customers, though compiler/workload specialization limits perfect fungibility.
- Microsoft connects Fairwater nodes to a broad Azure/OpenAI/Copilot workload pool.
- Meta is a single corporate user but has multiple monetized applications and advertising cash flow.
- Stargate is more concentrated on OpenAI consumption even when Oracle is the contractual provider.
- Colossus began concentrated on Grok, then added SpaceX balance-sheet support and external compute offtake. Its risk profile changed materially without the physical assets changing.

This suggests a model variable absent from simple $/GW tables:

$$
\text{Effective stranded-risk} = \text{asset specificity} \times \text{customer concentration} \times \text{contract weakness}
$$

## 12. Evaluation of the four hypotheses

### Hypothesis 1 — Stargate is unusually expensive

**Verdict: unresolved; weakly supported only for the NVIDIA-heavy full stack.**

Evidence against the strong claim:

- Hyperion's < $13.5B/GW long-lived-infrastructure ceiling overlaps Stargate's powered-campus range.
- All programs face similar high-density electrical, cooling, and network requirements.
- Microsoft and AWS headline ratios are not matched IT/full-stack comparisons.

Evidence consistent with some Stargate premium:

- Stargate uses cutting-edge NVIDIA equipment through a multi-party chain, which can add vendor margin, provider margin, financing cost, and duplicated return requirements.
- xAI's announced incremental proxy is materially lower.
- AWS's system-level vertical integration plausibly lowers cost per useful compute, although public evidence cannot size it.

The hypothesis should be restated: **Stargate may be unusually expensive per unit of useful compute because it combines frontier NVIDIA hardware, concentrated customer demand, and several capital intermediaries. Public data do not show its powered campus to be uniquely expensive.**

### Hypothesis 2 — Stargate is unusually financialized

**Verdict: relative yes; absolute no.**

AWS and Wisconsin Fairwater are predominantly corporate builds. Yet Hyperion is a highly levered outside-capital JV; xAI finances GPUs and power in separate vehicles; utilities finance multi-gigawatt systems against special tariffs; and Microsoft's portfolio includes hundreds of billions of dollars of uncommenced leases.

What is Stargate-specific is not “using finance.” It is **the number of essential balance sheets between ultimate demand and physical assets**. Hyperion's external owners still underwrite Meta. In Stargate, campus investors may underwrite Oracle leases, Oracle underwrites OpenAI demand, and utilities underwrite site/provider contracts. The layered chain creates more basis, refinancing, and counterparty interfaces.

### Hypothesis 3 — OpenAI's position is structurally unusual

**Verdict: strongly supported.**

Meta, Amazon, and Microsoft enter these projects with diversified, recurring cash engines and can own compute even if a particular model supplier disappoints. OpenAI has sought hyperscaler-scale infrastructure before developing the same breadth of recurring cash flow or physical asset base. It therefore purchases a service while Oracle, developers, lenders, and utilities hold assets and claims.

xAI is the useful stress test. Before the SpaceX merger, it also used large equity/debt raises, GPU leases, and a power JV to build ahead of mature recurring cash flow. After acquisition, SpaceX cash flow, public capital, and external compute customers became part of the support system. That transition reinforces rather than weakens the hypothesis: startup-led infrastructure needs a larger financing bridge until a broader cash engine or third-party offtake arrives.

### Hypothesis 4 — Power is becoming a separate capital system

**Verdict: strongly supported across all cases.**

The evidence is structural, not rhetorical. Hyperion's generation/transmission plan has different ownership and regulatory approvals from the campus JV. Colossus has a 900 MW power JV with customer equity and secured debt. Indiana and Wisconsin created large-load tariffs with protections against non-materializing demand. Even vertically integrated hyperscalers do not simply “own power”; they contract with a distinct network of utilities, generators, regulators, lenders, and fuel suppliers.

## 13. What this changes about the existing model

### 13.1 Replace one $/GW number with a five-layer, two-clock model

Retain the existing stack:

$$
C_{initial}=A_{land}+B_{shell+MEP}+C_{power}+D_{compute+network}+E_{financing}
$$

Add two clocks:

- **construction clock:** announcement → finance → construction → energization → operational acceptance;
- **asset-life clock:** GPUs/network refresh in roughly 4–6 years versus shells, transmission, and generation over decades.

An economically complete model also needs the present value of refresh:

$$
PV(C)=A+B+C+E+\sum_{g=0}^{n}\frac{D_g}{(1+r)^{t_g}}
$$

This prevents a site with cheap initial shell and repeated expensive GPU refreshes from appearing permanently cheap.

### 13.2 Add a four-role ownership matrix

For every A–E layer, record:

1. legal owner;
2. capital provider;
3. operator;
4. cash-flow/residual guarantor.

The Meta JV proves that “owner” and “risk bearer” can diverge sharply. The xAI failed-sale-leaseback disclosures prove that legal form and accounting substance can diverge too.

### 13.3 Add credit quality and fungibility as first-class variables

Two nominally identical 1 GW sites can have different financing costs because one is supported by a diversified hyperscaler and the other by a concentrated model company. The model should explicitly include:

- tenant/provider credit;
- customer concentration;
- contract duration and termination rights;
- collateral/minimum-payment provisions;
- alternative users for the shell, power, and accelerators;
- portability of software/workloads across silicon.

### 13.4 Treat speed-to-power as an option with a risk premium

Colossus demonstrates that earlier energization has economic value:

$$
\text{Speed option value} \approx \text{months accelerated} \times \text{monthly contribution from usable compute}
$$

But the option has a price:

$$
\text{Net speed value} = \text{speed option} - \text{fuel premium} - \text{temporary equipment cost} - \text{regulatory/remediation risk}
$$

This framing is more useful than labeling mobile generation categorically cheap or expensive.

### 13.5 Separate three power denominators

Every site record should contain, where available:

- generation nameplate MW;
- utility/facility peak MW;
- critical IT MW.

Then record PUE assumptions rather than silently equating the figures. Hyperion's 5.2 GW generation, 5 GW compute ambition, and internal campus infrastructure are related but not identical. New Carlisle's ~2.2 GW utility envelope cannot be assigned to Rainier IT load.

### 13.6 Add useful-compute output

The existing model is strong at capital placement but should not infer accelerator economics from electrical capacity alone. Rainier makes Google/TPU and custom-silicon follow-up necessary. The next model version should pair $/IT-GW with a workload-normalized cost measure and an explicit uncertainty band for utilization.

## 14. Remaining unknowns and highest-value follow-ups

### Material unknowns

1. **Hyperion compute bill:** accelerator count, mix, network bill, rack density, depreciation policy, and exact legal owner.
2. **Hyperion debt terms:** final debt/equity amounts, coupon, maturity, amortization, covenants, and guarantee mechanics.
3. **Rainier IT power:** exact site allocation of the nearly 500,000-chip cluster and New Carlisle's current critical IT load.
4. **Trainium economics:** foundry/packaging/HBM/system cost, useful-compute utilization, and generation-to-generation residual value.
5. **Fairwater denominator:** Wisconsin critical IT MW, installed GB200 count, and whether the $3.3B/$4B announcements include all compute equipment.
6. **Microsoft site versus portfolio leases:** which Fairwater-family capacity is owned, finance-leased, or operating-leased.
7. **Colossus investment schedule:** reconciliation of the >$20B Mississippi figure with leased GPU assets, SpaceXAI capex, tax basis, and paid-to-date construction.
8. **Colossus power cost:** turbine ownership by unit, fuel contract, heat rate, capacity factor, delivered $/MWh, emissions-control capex, and permanent-grid transition.
9. **Contract durability:** termination, renewal, collateral, and cross-default terms for Anthropic–AWS, SpaceXAI external compute, Meta–Hyperion, and customer-specific utility service.
10. **Common useful-compute benchmark:** no case yet discloses enough to compare annualized cost per accepted training/inference output.

### Priority investigations

1. **Google/Broadcom TPU infrastructure should become a priority follow-up.** Anthropic signed for multiple gigawatts of next-generation TPU capacity beginning in 2027 while continuing AWS Trainium and NVIDIA use. That makes Anthropic a rare within-customer comparison across three accelerator ecosystems and could separate silicon economics from model-company demand. [Anthropic Google/Broadcom announcement](https://www.anthropic.com/news/google-broadcom-partnership-compute)
2. Obtain the Hyperion private-placement memorandum or rating materials, if available, to quantify leverage, debt service, and the residual guarantee.
3. Pull IURC and PSCW final tariff orders and customer-service exhibits, not only utility summaries, to model minimum bills and exit exposure per GW.
4. Reconstruct New Carlisle building-by-building energization from permits, substation records, backup-generator permits, and tax assessments.
5. Reconcile Microsoft Wisconsin tax basis and equipment assessments with official utility load to split shell/MEP from GPUs.
6. Build a Colossus equipment registry from air permits, turbine serials, property records, SEC lease notes, and incentive schedules.
7. Track actual energized IT MW quarterly rather than announced ultimate capacity for every case.
8. Develop one standardized “capital-at-risk by year” chart that overlays GPU refresh, debt maturity, lease expiry, and power-contract expiry.

## 15. Explicit conclusion: general, Stargate-specific, unresolved

### Conclusions that generalize to the U.S. frontier-AI buildout

- The economically relevant object is a **layered capital stack**, not a datacenter building.
- Legal ownership, financing source, operator, customer, and residual-risk bearer are frequently different parties.
- Accelerators/network are usually the largest short-lived capital layer; long-lived shell and power require different finance.
- Long-term contracts and strong counterparties are essential to financing specialized, multi-gigawatt assets.
- Power is a separate infrastructure project with its own owners, regulation, financing, and stranded-asset protections.
- Announced investment, financed investment, installed equipment, energized capacity, and operational IT capacity are different states.
- Utility GW, generation GW, facility load, and IT GW cannot be substituted.
- Even cash-rich hyperscalers externalize capital when scale, asset life, or portfolio flexibility makes it attractive.
- The party with the strongest legal title does not necessarily bear the most economic downside.

### Conclusions that appear Stargate-specific, or unusually pronounced there

- OpenAI is often the ultimate user without owning land, buildings, accelerators, network, or power assets.
- Oracle's balance sheet and contract position act as a central credit transformer between OpenAI demand and infrastructure capital.
- More independent counterparties must earn returns across the same stack, creating additional margin, interface, and refinancing layers.
- Customer concentration is unusually high relative to AWS or Microsoft, which can redirect capacity across broad cloud businesses.
- Stargate's roughly $33B/GW compute proxy may reflect a frontier-NVIDIA acquisition at scale through a provider chain; it should not be generalized to custom silicon without evidence.

### Conclusions that remain unresolved

- Whether Stargate's **total** $43–52B/IT-GW is materially above a matched Hyperion, Rainier, Fairwater, or Colossus initial full stack.
- Whether Trainium or TPU produces a durable capital-cost advantage, rather than only a customer-price or workload-specific advantage.
- The true cost per unit of useful training or inference across accelerator architectures.
- How much Hyperion risk Blue Owl genuinely retains after Meta's lease, equity participation, management role, and residual guarantee.
- Whether xAI's apparent cost advantage survives full accounting for leased GPUs, power infrastructure, lifecycle reliability, environmental compliance, and future retrofit.
- How much of Microsoft and Amazon's nominally integrated capacity is ultimately leased or financed through undisclosed equipment and supplier structures.
- The eventual residual value of first-generation gigawatt AI campuses after multiple accelerator refreshes.

## Final judgment

The Stargate investigation identified the right system—capital layers connected by contracts—but it should not be treated as the sector's only organizational form. The benchmark reveals four regimes sharing one physical problem:

- Amazon and Microsoft shorten the chain by owning and operating most layers.
- Meta externalizes long-lived capital while retaining control and much of the downside.
- xAI externalizes chips and power, reuses industrial assets, and buys speed with regulatory and integration risk.
- Stargate uses the longest credit-transformation chain because OpenAI seeks hyperscaler-scale compute without yet behaving like a traditional asset-owning hyperscaler.

The most robust generalization is therefore not a single $/GW number. It is this:

> Frontier AI infrastructure is becoming a coupled system of short-lived compute capital and long-lived power/real-estate capital. The decisive economic question is who guarantees the bridge between them when demand, technology, and energization schedules do not line up.
