# cyber_threat_europe
Data and sources of cyber threats by volume and velocity in Europe
---------
# Cyber Threats Drifting: More Faster, More Furious
## A 2025 European Threat Review with Policy Recommendations

The panorama of cyber threats is evolving fast. AI, quantum computing, and cloud-first architectures offer a greenfield of opportunities for attackers to exploit. Meanwhile, European regulation is struggling to keep pace — 2026 alone carries two major deadlines: **August** for proving AI systems are secure and transparent (AI Act, Article 9) and **September** for actively-exploited vulnerability disclosure (Cyber Resilience Act). These maps take an intentionally simplified approach, mixing threat vectors and subjective goals, to highlight patterns that often get lost in the detail of technical reports.
---
### What the Data Is Telling Us
**The geography of DDoS is the geography of NATO solidarity.** In most countries on Europe's eastern flank — Estonia (76%), Lithuania (75%), Czech Republic (74%), Latvia (74%), Poland (73%) — DDoS and hacktivism are the dominant attack type by volume. This is not coincidence. It is the direct cyber signature of the Russia-Ukraine war, where groups like NoName057(16) (partially dismantled by a Eurojust-coordinated) systematically targeted countries based on their Ukraine support. In Western economies (UK, Germany, France, Spain, Ireland), however, ransomware overtakes DDoS as the #1 threat by volume** — attackers follow GDP, not geography.

**In most countries, the fastest-growing threat nearly doubled year-on-year.** This means attackers are continuously field-testing attacks for which defenders are often unprepared. Romania saw a +52% surge in ransomware velocity (culminating in a BitLocker attack that locked ~1,000 systems at the national water agency in December 2025). Estonia registered a +52% escalation in critical infrastructure targeting, including undersea cable sabotage. Ukraine recorded a +55% increase in ICS/OT attacks. These are not incremental changes — they are acceleration signals.

**AI has industrialized social engineering.** AI-assisted phishing campaigns now represent over 80% of all observed social engineering activity (ENISA ETL 2025, CrowdStrike ETL 2025). Groups like SCATTERED SPIDER have pivoted from technical exploitation to sophisticated AI-enhanced vishing (voice phishing), replacing zero-day exploits with convincing synthetic voice calls that bypass MFA by manipulating help desks. The Eye Security Incident Response Report (Jan 2026) found that MFA was bypassed in 62% of investigated incidents since January 2025 — almost always through social manipulation, not technical cracking.

**NIS2 is reshaping the regulatory landscape.** Countries like Romania, Bulgaria, Poland, Czech Republic, and Spain have seen a massive uptick in registered "essential entities" following the 2025 transposition of the NIS2 Directive. Over 160,000 entities across the EU now fall under NIS2 obligations — compared to roughly 10,000 under the original NIS1. Critically, over 53% of recorded EU incidents in 2025 targeted these "essential entities" as defined by NIS2, with Public Administration as the most targeted sector at 38.2% of incidents (ENISA ETL 2025).

**DDoS is becoming a smokescreen, not just an attack.** According to Link11's European Cyber Report 2025 (which recorded a +225% increase in DDoS volume in H1 2025 vs. H1 2024), DDoS attacks are increasingly serving as diversion tactics — occupying SOC teams while covering parallel malware or data exfiltration. Approximately 90% of low-level DDoS attacks are automatically mitigated, but the coordination pattern of modern DDoS-plus-intrusion campaigns requires human analyst attention that diverts from the real threat. Link11's 2026 forecast identifies AI-orchestrated "ISP-killer" DDoS variants and DDoS-as-a-Service platform proliferation as the defining trend for 2026.

**The physical-digital boundary is dissolving.** While the EU Cyber Diplomacy Toolbox attempts to deter state-nexus actors, groups like RENAISSANCE SPIDER (Russia-nexus, per CrowdStrike 2025) and the Z-Alliance are operating in the shadows of eCrime to conduct physical-digital hybrid attacks: documented physical arson against European civilian infrastructure in late 2024, compromise of Industrial Control Systems (ICS) across France, Germany, Poland, and Spain for media attention and psychological impact, and coordinated insider-recruitment campaigns. In 2025, threat actors linked to "The Com” attempted to recruit individuals to physically enter corporate headquarters in the UK — the first documented instance of vishing-funded physical access recruitment in Europe (CrowdStrike ETL 2025, NCSC UK Annual Review 2025).

**GDPR extortion has matured into a standard ransomware playbook.** Attackers now routinely threaten companies not only with data publication but with the prospect of the company itself reporting the breach (triggering GDPR fines of up to 4% of global annual turnover). This creates a perverse incentive structure where paying the ransom is financially rational. Europol's EU-SOCTA 2025 (March 2025) confirmed that cyber-enabled extortion has become the #1 priority organized crime category in Europe.

**Supply chain attacks have arrived at scale.** Gartner's 2022 prediction that 45% of global organizations would face supply chain attacks by 2025 has been confirmed (Gartner Top Cybersecurity Trends 2025, March 2025). Attackers have shifted from individual company targeting to "Critical Dependency Points” — IT service providers, managed security services, and code repositories — to maximize victim reach per attack. Ireland and Belgium are the European leading indicators, each showing +50% and +45% YoY growth respectively in supply chain attack velocity. A notable signal: 94% of manufacturing sector victims in 2025 were linked to defense and automotive supply chains (IBM X-Force Threat Intelligence Index 2025).

**Post-quantum vulnerabilities are no longer theoretical.** 2026 marks the start of the "PQ Transition”. NIST published its first post-quantum cryptography standards in 2024 (FIPS 203, 204, 205). National cybersecurity strategies across Germany, France, the UK, and the Netherlands now include formal timelines targeting quantum-resistant encryption by 2030. The window to begin migration is measured in months, not years — quantum-relevant data being harvested now for future decryption ("harvest now, decrypt later") is an active intelligence threat.

**Zero-day speed has broken the enterprise patch cycle.** Exploits account for 21% of initial intrusions (CrowdStrike ETL 2025), but the growth factor is velocity: attackers now weaponize zero-day vulnerabilities within hours of public disclosure. This is particularly damaging for Operational Technology (OT) and Industrial Control Systems — as documented in Germany and Italy in 2025 — where systems cannot be patched without taking production offline. Cyfirma's 2025 Annual Industries Report identified a parallel trend: once inside a network, sophisticated actors increasingly prefer long-term data monetization (quiet exfiltration over months) over immediate ransomware deployment, dramatically increasing dwell time before detection.

---

### 2025 and 2026 Risk Consensus

Cyber risk has been the **#1 business risk globally for the fifth consecutive year** in the Allianz Risk Barometer 2026 (January 2026, surveying 3,338 risk professionals across 106 countries). The WEF Global Cybersecurity Outlook 2026 (January 17, 2026) found that 64% of organizations now explicitly account for geopolitically motivated cyber attacks in their risk planning — up from 42% in 2023. Gartner projects global information security spending will reach $240 billion in 2026 (+15% YoY), yet only 2% of organizations describe themselves as fully cyber-resilient (PwC Global Digital Trust Insights 2025).

---

### Policy Recommendations

**Dynamic Threat Intelligence Integration.** Rather than static 2-year regulatory reviews, NIS2 should require "Essential Entities" to demonstrate active defense against current TTPs (Tactics, Techniques, and Procedures) identified by ENISA, CERT-EU, and trusted private-sector intelligence. Static compliance checklists create a false sense of security.

**Mandate MDR for Essential Entities.** Data consistently shows attackers use legitimate tools — compromised identities, not custom malware — making signature-based detection ineffective. Eye Security's 2026 report found MDR reduces dwell time from a median of 197 days to minutes. Regulations should mandate Managed Detection and Response for all NIS2 Essential Entities.

**Shift from Auditing to Threat Hunting.** Current laws favour checkbox audits. Future policy should incentivize proactive threat hunting — identifying adversaries before ransomware deployment, which CrowdStrike 2025 data shows now takes as little as 24 hours from initial access (down from 84 minutes for average breakout time).

**Cross-Border Safe Harbour for Breach Reporting.** To break the GDPR extortion cycle, the EU should create a formal safe harbor where companies that report a breach immediately to their national CSIRT receive measured protection from certain GDPR fines. This removes the financial leverage that makes paying ransoms rational, without reducing accountability.

**Counter the Physical-Digital Blur.** The ECCC and Europol's EC3 need dedicated funding for Hybrid Threat Response — attacks involving physical sabotage (arson, vishing-recruitment) that fall between traditional policing and cybersecurity mandates. Current structures leave this gap largely unfunded.

**Zero Trust as Regulatory Baseline.** With 80%+ of social engineering AI-powered, perimeter-based defenses are obsolete. Identity protection and Zero Trust architectures are the only viable baseline defense against credential-centric attacks. DORA and NIS2 should reference Zero Trust explicitly, not merely "access control."

**Harden the Supply Chain as a NIS2 Priority.** Third-party access auditing is now a core NIS2 requirement, but enforcement remains weak. The forthcoming ICT Supply Chain Framework (2026) allows the EU to designate "High-Risk Suppliers," but does not yet address Cloud Concentration risk — the systemic dependency of thousands of Essential Entities on a handful of non-EU hyperscalers. A "Cloud Diversity" mandate (no more than 60% of critical data on a single non-EU provider) merits serious consideration.

**Automate Compliance Reporting.** DORA and NIS2 made manual incident reporting obsolete. Companies should be automating their reporting workflows — the technology exists, the regulation requires speed (DORA mandates initial ICT incident notification within 4 hours), and manual processes cannot meet this timeline at scale.

**Post-Quantum Timeline Enforcement.** The 2030 deadline for quantum-resistant cryptography requires organizations to start migration now. National cybersecurity authorities should publish sector-specific migration guidance and consider CRA-linked obligations for critical infrastructure vendors.

**Adversarial AI Testing.** Specifically test defenses against AI-generated voice and video (vishing/deepfakes). Hardware-based "Out-of-Band" authentication — a second channel that cannot be compromised via voice — is currently the most effective countermeasure against AI-vishing. Consider mandating this for financial sector and critical infrastructure operators.

**Support SME Adaptation.** NIS2 compliance costs disproportionately burden SMEs newly classified as essential or important entities. EU-level financing instruments (InvestEU, ECCC funding) should be explicitly targeted at SME cybersecurity upskilling and system adaptation, with a simplified compliance track for companies under 250 employees.

---

*Sources: ENISA Threat Landscape 2025 · CrowdStrike European Threat Landscape 2025 · CERT-EU Cyber Briefs 25-01 to 26-01 · Eye Security Incident Response Report 2026 · WEF Global Cybersecurity Outlook 2026 · Allianz Risk Barometer 2026 · EU-SOCTA 2025 (Europol) · IBM X-Force 2025 · Gartner Top Cybersecurity Trends 2025/2026 · Link11 European Cyber Report 2025 · Cyfirma Annual Industries Report 2025 · PwC Global Digital Trust Insights 2025 · National CERTs: BSI, ANSSI, NCSC-UK, DNSC Romania, RIA Estonia, NKSC Lithuania, CERT Polska, NCSC-NL, NSM Norway, NCSC-SE, BTK Turkey, CERT-UA*
