<div align="center">

# Susan Shepard

### *Cyber risk, quantified into decisions leaders can defend.*

**Staff · Trust, Risk & Compliance Analyst, Information Security @ Rapid7**

Boston, MA · USAF Veteran · President & Founder, GRC Engineering Club — Boston Chapter

[![Portfolio](https://img.shields.io/badge/Portfolio-8D5860?style=flat-square&logo=github&logoColor=white)](https://xnasusx.github.io/portfolio/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-3A3336?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/xnasusx/) [![Medium](https://img.shields.io/badge/Medium-4C7359?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@xnasusx) [![Email](https://img.shields.io/badge/Email-9A6A24?style=flat-square&logo=protonmail&logoColor=white)](mailto:HireSusanShepard@pm.me)

</div>

---

## 🔍 About

Over a decade across enterprise SaaS, biotechnology, healthcare, and public-company security work — now building **FAIR-based risk quantification**, **compliance-as-code**, and **AI-assisted GRC systems** that replace the audit spreadsheet with something a board can actually read.

I architect and engineer the platforms myself: React/Vite front ends, Node.js/Express services, PostgreSQL data models, and evidence pipelines that pull continuous control evidence out of cloud infrastructure, IdPs, EDRs, and ticketing systems instead of asking a human to screenshot it.

<div align="center">

![FAIR](https://img.shields.io/badge/FAIR_Risk_Quantification-8D5860?style=flat-square) ![Compliance as Code](https://img.shields.io/badge/Compliance--as--Code-9A6A24?style=flat-square) ![AI-assisted GRC](https://img.shields.io/badge/AI--assisted_GRC_Engineering-4C7359?style=flat-square) ![SEC Materiality](https://img.shields.io/badge/SEC_Cyber_Materiality-8D5860?style=flat-square) ![Control Mapping](https://img.shields.io/badge/Multi--framework_Control_Mapping-9A6A24?style=flat-square)

</div>

---

## 🎯 What I Build

| | What it means | Where it shows up |
|---|---|---|
| **01 · Quantify** | Turn cyber risk from a heat-map color into a defensible loss-exposure range. FAIR-based scenarios, LLM-assisted scoring, and P50 / P90 narratives that let leadership decide instead of react. | `FAIR` · `Monte Carlo` · `LLM scoring` · `Executive narrative` |
| **02 · Engineer** | Make controls, evidence, and frameworks one operating system — not five parallel spreadsheets. OSCAL-shaped data, compliance-as-code checks, and evidence pipelines that arrive with the work. | `OSCAL` · `Compliance-as-code` · `Evidence automation` · `Control platform` |
| **03 · Translate** | Move technical exposure into materiality decisions leaders can defend. OWASP + EO-14028 severity, SEC 8-K disclosure workflows, and calculators that keep the reasoning legible after the incident. | `SEC 8-K` · `EO-14028` · `Materiality` · `Incident severity` |

---

## 🧠 How I Think About GRC

> **Controls are the foundation. Everything else pulls from the controls.**
> Build controls out properly and audit evidence, risk, policy, and compliance automatically compose. Miss the layer a control sits at — product, platform, customer, enterprise — or what it costs to own, and you'll never calculate risk, mature controls, set realistic KRIs/KPIs, or run continuous monitoring. Bad control data is the path to a failing GRC program.

> **Financial quantification in GRC is non-negotiable.**
> Heatmaps are dead. Red is a color, not a unit of risk measurement. You cannot tell leadership "how risky" something is by calling it red. FAIR gives you defensible loss exposure ranges a CFO can budget against.

> **Risk is not a point in time. Risk is scenarios.**
> Static risk registers are legacy. We run scenarios, Monte Carlo simulations, and loss exceedance curves to show where threats actually live. When risk is forward-looking instead of reactionary, you have a mature program.

> **GRC engineering and automation take programs to the next level.**
> Manual workload eventually takes its toll and fatigue causes error. Automate the workflows and engineer the solutions — AI for risk scoring, questionnaire response, vendor assessment, and threat modeling. AI and engineering take already-mature programs to the next level, and give struggling teams a shortcut to the top.

---

## 📌 Featured Work

| Project | What it does |
|---|---|
| **[proofplane](https://github.com/xnasusx/proofplane)** `TypeScript · Python · Go` | An AI governance control plane where a control is satisfied **only when an executed adversarial attack failed** — never because a document says it exists. Twelve controls, each naming the MITRE ATLAS and OWASP Agentic technique it defends against, the probe that proves it, and a crosswalk to ISO/IEC 42001, NIST AI RMF, AIUC-1, the EU AI Act and the UK AI Cyber Code — every mapping carrying its own confidence and a written basis for what was *not* verified. Two checks make the green worth believing: `verify` requires each probe to breach against an unguarded target and hold against a guarded one, and `matrix` disables one guardrail at a time across 144 runs, so no probe can pass because an unrelated control happened to mask its attack. A `limits` command **executes** the weaknesses the documentation admits to instead of asserting them — a paraphrased injection defeats the content filter with it enabled, and the authorisation gate stops the loss anyway, which is the whole architectural argument. Evidence is hash-chained, breach rates carry a Wilson interval because zero-of-three is consistent with a 56% true failure rate, and the OSCAL output validates against the NIST 1.1.2 schema. A Go scanner emits a CycloneDX ML-BOM of the AI surface with file-and-line provenance for every component. **[Live](https://xnasusx.github.io/proofplane/)** |
| **[u-dont-grc-me](https://github.com/xnasusx/u-dont-grc-me)** `TypeScript` | Control-centric GRC platform prototype — controls are the source of truth, with assets, frameworks, evidence, risks, integrations, and AI agent decisions mapped around each one. Command center, audit package assembly, and a 10,000-trial FAIR Monte Carlo engine. React/Vite UI over a SQLite/Lambda API. **[Live](https://xnasusx.github.io/u-dont-grc-me/)** |
| **[proofscan](https://github.com/xnasusx/proofscan)** `TypeScript` | Layered, target-agnostic application flaw scanner that **proves** the bug it finds. Layer 1: deterministic static analysis (AST rules modelling the Express route inventory, plus Semgrep/Gitleaks/Trivy) with per-scanner coverage reporting, because a scanner that never ran looks exactly like a clean result. Layer 2: AI reasoning over a scoped rubric, then a **sandboxed exploit** — a finding is `verified-exploitable` only once a generated attack changed another user's data. Layer 3: a dynamic BOLA/IDOR fuzzer that rediscovers the same bug against a running instance with no source access, gated on an authorisation record. Layer 4: a remediation loop that files the ticket and re-runs the real exploit against the fix, flipping to `fixed-verified` only when it no longer reproduces — the merge gate. The exploit plan is inferred from each target, not hardcoded, so it scans anything Express-shaped, not one reference app; the verdict is always the victim's state, never the attacker's 404. Command-line tool, so nothing deployed. |
| **[ai-risk-register](https://github.com/xnasusx/ai-risk-register)** `HTML` | An AI risk register that returns loss exposure ranges instead of heat-map colours. Twelve seeded AI scenarios, three-point estimates through a 10,000-iteration Monte Carlo, and live coverage against NIST AI RMF 1.0 and ISO/IEC 42001 Annex A. **[Live](https://xnasusx.github.io/ai-risk-register/)** |
| **[cyber-materiality-workbench](https://github.com/xnasusx/cyber-materiality-workbench)** `HTML` | Work an incident through an SEC Item 1.05 materiality determination — the quantitative screen, the SAB 99 total mix, the four-business-day clock counted against federal holidays, and the contemporaneous memo. Either leg can carry the call, which is the whole point. **[Live](https://xnasusx.github.io/cyber-materiality-workbench/)** |
| **[incident-severity-calculator](https://github.com/xnasusx/incident-severity-calculator)** `HTML` | Sixteen OWASP Risk Rating factors, likelihood and impact kept separate, severity read from the OWASP matrix with the active cell shown live. One rubric, so the argument becomes "you scored detection at 9 and I scored it at 3." **[Live](https://xnasusx.github.io/incident-severity-calculator/)** |
| **[risk-quantifier](https://github.com/xnasusx/risk-quantifier)** `HTML` | Place risks on a 5×5 heat map, give each a frequency and loss range, then run 10,000 Monte Carlo iterations and watch the matrix become a distribution. Built to show exactly how much information a qualitative matrix throws away. Each risk can start from a source-backed benchmark instead of an invented range, rendering that shard's six citations and their stated limits beside the inputs — and because shards are priced in four currencies, a mixed-currency portfolio is refused rather than silently summed. **[Live](https://xnasusx.github.io/risk-quantifier/)** |
| **[risk-benchmarks-integration](https://github.com/xnasusx/risk-benchmarks-integration)** `Write-up` | An engineering account of replacing invented numbers with sourced ones across eleven repositories — and of how little that data covers. A published loss study fills two nodes of the FAIR decomposition out of thirteen, because frequency and magnitude are the only factors anyone measures across a population; the other eleven are the analysis. Records what each integration does differently and why one tool deliberately gets no data at all, the nine defects found and the method that caught each — three of them by composing a README screenshot rather than by testing — and the three claims that had to be corrected mid-flight when the tool's own output contradicted the prose. |
| **[risk-benchmarks](https://github.com/xnasusx/risk-benchmarks)** `JSON · Python · HTML` | The numbers behind the risk lab, as one file every tool loads directly. Eleven governed shards across eight countries and three threats, where all 66 parameters resolve to a named public source and each carries its publication date, confidence level, and the limitation on its use — including which frequencies are bridged from another country because no local per-firm rate is published. Every shard states what it is *not* good for, and unsourced demo scenarios sit in a separate array so a consumer cannot render an invented figure as a sourced one. Derived from RiskShard, regenerated by a build script that resolves scenarios, calibrations, and evidence through manifest references rather than filenames. **[Live](https://xnasusx.github.io/risk-benchmarks/)** |
| **[loss-exceedance-curve](https://github.com/xnasusx/loss-exceedance-curve)** `HTML` | Interactive LEC guide. Overlay risk tolerance, loss reserves, and materiality to read the odds of crossing each one — the answer to "what are the chances we lose more than $X?" **[Live](https://xnasusx.github.io/loss-exceedance-curve/)** |
| **[fair-model-study](https://github.com/xnasusx/fair-model-study)** `HTML` | Interactive FAIR taxonomy trainer: build the decomposition tree from memory, assign units, match 22 definitions. Placement and unit accuracy scored separately. **[Live](https://xnasusx.github.io/fair-model-study/)** |
| **[monte-carlo-demo](https://github.com/xnasusx/monte-carlo-demo)** `HTML` | Watch the law of large numbers converge on a fair coin, with the binomial standard-error band drawn in. Ten flips land anywhere; ten thousand settle down. **[Live](https://xnasusx.github.io/monte-carlo-demo/)** |
| **[portfolio](https://github.com/xnasusx/portfolio)** `HTML` | [xnasusx.github.io/portfolio](https://xnasusx.github.io/portfolio/) — the full body of work: programs, builds, and the risk lab. |

---

## 🧰 Toolbox

**Risk & Quantification**

![FAIR](https://img.shields.io/badge/FAIR-8D5860?style=flat-square) ![Monte Carlo](https://img.shields.io/badge/Monte_Carlo-8D5860?style=flat-square) ![Loss Exceedance](https://img.shields.io/badge/Loss_Exceedance_Curves-8D5860?style=flat-square) ![CVSS](https://img.shields.io/badge/CVSS-8D5860?style=flat-square) ![OWASP](https://img.shields.io/badge/OWASP-8D5860?style=flat-square&logo=owasp&logoColor=white) ![EO-14028](https://img.shields.io/badge/EO--14028_Materiality-8D5860?style=flat-square)

**Frameworks & Standards**

![NIST 800-53](https://img.shields.io/badge/NIST_SP_800--53_r5-9A6A24?style=flat-square) ![NIST CSF](https://img.shields.io/badge/NIST_CSF-9A6A24?style=flat-square) ![ISO 27001](https://img.shields.io/badge/ISO_27001%2F27017-9A6A24?style=flat-square) ![SOC 2](https://img.shields.io/badge/SOC_2%2F3-9A6A24?style=flat-square) ![PCI DSS](https://img.shields.io/badge/PCI_DSS-9A6A24?style=flat-square) ![FedRAMP](https://img.shields.io/badge/FedRAMP-9A6A24?style=flat-square) ![GovRAMP](https://img.shields.io/badge/GovRAMP_%7C_TxRAMP-9A6A24?style=flat-square) ![HIPAA](https://img.shields.io/badge/HIPAA_%7C_HITRUST-9A6A24?style=flat-square) ![GDPR](https://img.shields.io/badge/GDPR-9A6A24?style=flat-square) ![DORA](https://img.shields.io/badge/DORA_%7C_NIS2-9A6A24?style=flat-square) ![CSA CCM](https://img.shields.io/badge/CSA_CCM%2FCAIQ-9A6A24?style=flat-square) ![OSCAL](https://img.shields.io/badge/OSCAL-9A6A24?style=flat-square) ![NIST AI RMF](https://img.shields.io/badge/NIST_AI_RMF_1.0-9A6A24?style=flat-square) ![ISO 42001](https://img.shields.io/badge/ISO%2FIEC_42001-9A6A24?style=flat-square)

**Build**

![TypeScript](https://img.shields.io/badge/TypeScript-3A3336?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-3A3336?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-3A3336?style=flat-square&logo=vite&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-3A3336?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-3A3336?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-3A3336?style=flat-square&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3A3336?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-3A3336?style=flat-square&logo=docker&logoColor=white) ![Slack Bolt](https://img.shields.io/badge/Slack_Bolt-3A3336?style=flat-square&logo=slack&logoColor=white) ![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions_MV3-3A3336?style=flat-square&logo=googlechrome&logoColor=white)

**Cloud & AI**

![AWS](https://img.shields.io/badge/AWS-4C7359?style=flat-square&logo=amazonwebservices&logoColor=white) ![GCP](https://img.shields.io/badge/Google_Cloud-4C7359?style=flat-square&logo=googlecloud&logoColor=white) ![LLM Integration](https://img.shields.io/badge/LLM_Integration-4C7359?style=flat-square) ![RAG](https://img.shields.io/badge/RAG_GRC_Tooling-4C7359?style=flat-square) ![Agentic Workflows](https://img.shields.io/badge/Agentic_Workflows-4C7359?style=flat-square)

**GRC Platforms**

![OneTrust](https://img.shields.io/badge/OneTrust-6B6266?style=flat-square) ![Archer](https://img.shields.io/badge/Archer-6B6266?style=flat-square) ![ServiceNow GRC](https://img.shields.io/badge/ServiceNow_GRC-6B6266?style=flat-square&logo=servicenow&logoColor=white) ![AuditBoard](https://img.shields.io/badge/AuditBoard-6B6266?style=flat-square)

**GRC Engineering Credentials**

![CGE-P](https://img.shields.io/badge/CGE--P-Certified_GRC_Engineer_%C2%B7_Practitioner-4C7359?style=flat-square) ![CGE-AUD](https://img.shields.io/badge/CGE--AUD-Certified_GRC_Engineer_%C2%B7_Auditor_Specialty-4C7359?style=flat-square)

---

## 🎓 Certifications & Education

| Credential | Issuer |
|---|---|
| Certified Information Security Manager (CISM) | ISACA |
| Certified in Risk and Information Systems Control (CRISC) | ISACA |
| Advanced in AI Security Management (AAISM) | ISACA |
| Advanced in AI Risk (AAIR) | ISACA |
| Certified in Cybersecurity (CC) | ISC2 |
| AWS Certified Cloud Practitioner (CLF-C02) | AWS |
| Certified GRC Engineer — Practitioner (CGE-P) | GRC Engineering Club |
| Certified GRC Engineer — Auditor Specialty (CGE-AUD) | GRC Engineering Club |

- **M.S. Computer Information Systems**, Concentration: Security — Boston University
- **B.S. Information Technology**, *magna cum laude* — UMass Lowell

---

## ✍️ Recent Writing

<!-- MEDIUM-RECENT-ARTICLES:START -->
<table cellpadding="10" cellspacing="0">
<tr>
<td width="180" valign="top"><a href="https://xnasusx.medium.com/you-dont-build-a-garden-around-the-blight-f844da2e8f4c"><img src="https://cdn-images-1.medium.com/v2/resize:fill:180:120/1*pXzp4db9Qjtc4t499BPZkw.png" width="180" height="120" alt="" /></a></td>
<td valign="top">
<a href="https://xnasusx.medium.com/you-dont-build-a-garden-around-the-blight-f844da2e8f4c"><b>You Don’t Build a Garden Around the Blight</b></a><br/>
<sub>Jul 31, 2026</sub><br/>
Why Controls Should Be the Soil a GRC Program Grows From — Not the Harvest It Inspects Most GRC programs are built backward. They start with...
</td>
</tr>
</table>

<table cellpadding="10" cellspacing="0">
<tr>
<td width="180" valign="top"><a href="https://xnasusx.medium.com/hari-seldon-wouldve-made-a-great-ciso-ccc5b165821b"><img src="https://cdn-images-1.medium.com/v2/resize:fill:180:120/1*enyvm4cGQ3dA5vkYmyK6XQ.png" width="180" height="120" alt="" /></a></td>
<td valign="top">
<a href="https://xnasusx.medium.com/hari-seldon-wouldve-made-a-great-ciso-ccc5b165821b"><b>Hari Seldon Would’ve Made a Great CISO</b></a><br/>
<sub>Jul 13, 2026</sub><br/>
What Cyber Risk Analysts Can Learn From Asimov’s Foundation In Isaac Asimov’s Foundation series, mathematician Hari Seldon develops “psychoh...
</td>
</tr>
</table>
<!-- MEDIUM-RECENT-ARTICLES:END -->

[All posts on Medium →](https://medium.com/@xnasusx)

---

## 🌱 Community & Contributions

- **President & Founder** — [GRC Engineering Club, Boston Chapter](https://grcengclub.com/chapters/boston#join). Building the local practice around systems, automation, and modern controls work.
- **ISACA AAISM** beta tester and Exam Writing Development Group writer.
- **ISC2** technical guidance paper co-author and subject matter expert.
- Mentoring through ISACA, Big Brothers Big Sisters, and Boston University Admissions.

---

<div align="center">

### 📬 Let's talk

Quantitative risk programs, GRC engineering, or turning a control library into a platform.

[![Portfolio](https://img.shields.io/badge/xnasusx.github.io%2Fportfolio-8D5860?style=for-the-badge&logo=github&logoColor=white)](https://xnasusx.github.io/portfolio/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-3A3336?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/xnasusx/) [![Email](https://img.shields.io/badge/HireSusanShepard@pm.me-9A6A24?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:HireSusanShepard@pm.me)

<br/>

*"Red is a color, not a unit of risk measurement."*

</div>
