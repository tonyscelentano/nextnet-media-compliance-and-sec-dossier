# NextNet Media Security & Compliance Disclosure: SEC Rule 21F-17(a) Violations & SOC2 Failures

Mirrored on: [GitLab](https://gitlab.com/tony.s.celentano/nextnet-media-compliance-dossier) | [Codeberg](https://codeberg.org/TonyCelentano_ComplianceOps/NextNet-Media-Compliance-Dossier) | [Medium](https://medium.com/@tony.s.celentano/a-massive-failure-in-soc2-pci-dss-ccpa-and-gdpr-compliance-controls-how-i-discovered-over-100-c2f51ce91a04)

While working as an Engineer & Data Coordinator at [**NextNet Media**](https://nextnet.ai), I discovered over 100 plaintext API keys for payment gateways, cloud infrastructure, and SaaS platforms that could leak sensitive data of both clients and employees. This represents a complete and utter failure of **SOC2, GDPR, CCPA, and SOX** security controls. The full list includes: Tipalti, Stripe, PayPal, AWS, ECS, MongoDB, Xero, SendGrid, ZenRows, and more.

<img width="845" height="269" alt="Plaintext API key exposure in NextNet Media production environment including Tipalti, Stripe, and AWS" src="https://github.com/user-attachments/assets/62f5e400-04eb-402b-85c2-74344f53e659" />

Even basic GitHub security scanning was disabled. Because the company employs both domestic and offshore developers, and utilizes **Tipalti** as an internal payroll mechanism, I feared for the financial well-being of coworkers who could become victims of private data theft.

I compiled a report of the security violations and sent it to the proper internal channel. In good faith, I offered to be part of the cleanup crew - within 48 hours, I was terminated without notice or cause. I also immediately lost access to my work emails and Tipalti portal, leaving me unable to download my payout records or 1099 forms.

<img width="1345" height="610" alt="Evidence of retaliatory access revocation to NextNet Media work email and Tipalti payroll portal" src="https://github.com/user-attachments/assets/b06f84fe-4b1c-4810-bffa-5704f423f93e" />
<img width="1773" height="599" alt="Account lockout notice for NextNet Media contractor following internal security vulnerability report" src="https://github.com/user-attachments/assets/f6d5396b-0801-408f-8690-2c7e5f5c4f65" />

I was told I'd receive a week's pay - when I pointed out my contract had a 30-day termination notice clause, I was informed that my termination was covered by a contract clause which cites a material breach of contract. I asked to know which contract clause I had breached, and received no response.

When I provided NextNet's legal counsel, **Koley Jessen**, with constructive knowledge - I was Mimecast blocked. Apparently, general counsel does not like being informed of their client's regulatory compliance violations.

I filed **SEC, FinCEN, and OSHA** whistleblower reports, and sent a physical letter to NextNet LLC's address. In return, I received a settlement offer - $3,214 if I dismissed my whistleblower complaints with those federal bodies, released only upon "written receipt of closure and dismissal of any and all Complaints".

<img width="1175" height="927" alt="NextNet Media settlement offer violating SEC Rule 21F-17(a) whistleblower protections with illegal gag clause" src="https://github.com/user-attachments/assets/f9bd7348-db50-4e0b-b2cb-9a306d0cf2fa" />


This settlement offer, being a clear violation of [**SEC Rule 21F-17(a)**](https://www.sec.gov/enforcement-litigation/whistleblower-program/whistleblower-protections), was added to my whistleblower reports. The SEC wrote this rule exactly because of the chilling effect that gag clauses have on whistleblowers.


<img width="941" height="478" alt="SEC TCR ticket update to include SEC Rule 21F-17(a) violation" src="https://github.com/user-attachments/assets/702948c1-f3ab-4fb8-9443-aa2d1fb3f8d2" />

I also provided the financial lending and private equity partners of NextNet with constructive knowledge, as I believed that NextNet would not remediate their security issues unless forced. I received radio silence from those channels as well.

Since then, other contractors have come forward to me, highlighting their willingness to give testimony. I've received additional documents and data - such as U.S. contractors receiving zeroed-out 1099-NEC tax forms, despite receiving tens of thousands of dollars in documented, processed payments - a discrepancy pointing directly to **federal tax reporting failures**.

Because the contractors are not C-Corp or S-Corp entities, and they performed real work with real pay - there is absolutely zero reason to send them "corrected" $0 1099-NEC forms.

<img width="1926" height="2711" alt="Corrected zeroed-out IRS Form 1099-NEC issued by NextNet Media demonstrating tax reporting discrepancies and spoliation" src="https://github.com/user-attachments/assets/4fa625f5-970b-4bd9-8779-9d477fbdc63b" />

Why am I going public with this information? Because NextNet recapitalized in 2021, and are looking for an **EBITDA exit** within the year. They would be passing the compliance bag to the next buyer.

I realize going public with this information carries significant professional risks, but I've been left with no ethical alternative. I operate in the interest of full transparent disclosure to affected parties.

This includes current and potential future clients of NextNet Media, prospective strategic acquirers, private equity sponsors, and the institutional investors, as well as internal contractors and employees who may not be aware of the negligence with which NextNet handles their personal data.

## NextNet Media Portfolio Brands
NextNet Media owns and operates the following brands in its portfolio:
* The HOTH
* Authority Builders
* LinkBuilder.io
* FreeUp
* CopyMatic.ai
* SEOJet

## NextNet's Blue-Chip Clients

The prior agency I worked for, LinkBuilder.io, had a large roster of blue-chip (publicly traded) companies including:

* Shopify Inc. (NASDAQ: SHOP)
* Sofi Technologies (NASDAQ: SOFI)
* Wayfair Inc. (NYSE: W)
* SolarWinds (NYSE: SWI)
* HelloFresh SE (ETR: HFG)
* EverCommerce Inc. (NASDAQ: EVCM)
* Sonic Automotive Inc. (NYSE: SAH)
* News Corp (NASDAQ: NWSA)

At the moment of acquisition, NextNet Media inherited those client relationships. Why does this matter? LinkBuilder.io did not just deal in PBN link exchanges - they explicitly engineer high-value digital acquisition pipelines, as outlined in this [case study](https://linkbuilder.io/case-studies/fintech-service/), which specifically involved SoFi Technologies. For clients like SoFi, LinkBuilder.io engaged in highly regulated "Your Money or Your Life" (YMYL) financial marketing, generating millions in lead-acquisition value.

This was owing to the honest work of LinkBuilder.io's previous owner, who had a strong ethical commitment to legitimate B2B practices. Unfortunately, when he sold LinkBuilder.io to NextNet Media, private equity interests took over.

When NextNet inherited these blue-chip clients, they also put publicly traded companies at severe risk for data exposure. NextNet didn't just fail to secure their own internal API keys; they left the digital acquisition history of NASDAQ-listed companies exposed to the open internet via privaty equity roll-up and unmitigated technical debt. This may expose NextNet Media to liabilities under under the Supreme Court precedent set by Lawson v. FMR LLC.

## Document Exhibit: State of Florida Division of Corporations (Sunbiz) official registry for NextNet Media, LLC, renewed in 2026.
<img width="920" height="745" alt="State of Florida Sunbiz corporate registration and executive map for NextNet Media LLC" src="https://github.com/user-attachments/assets/2ffaa225-6de0-4d48-82e6-4295c9d1b4c8" />

Two members of Clearview Capital, a private equity firm in Stamford, CT, are registered as MANA partners on the NextNet LLC.

This potentially extends liability for NextNet's technical negligence and questionable tax filing practices to the managers of the fund - a fund [valued at $550M](https://pitchbook.com/profiles/fund/16376-50F). Abacus Finance Group [served as Senior Secured Credit Facilities Administrative Agent and Lead Arranger](https://abacusfinance.com/news/abacus-finance-provides-senior-debt-financing-to-support-the-recapitalization-of-next-net-media-llc-a-clearview-capital-portfolio-company/) for the recapitalization and made an equity co-investment in the same transaction.

To put it plainly, NextNet Media's technical negligence has exposed their own private equity partners to the same federal scrutiny, as liability travels up the chain.

<img width="983" height="573" alt="Abacus Finance Group press release on NextNet Media funding." src="https://github.com/user-attachments/assets/25b72198-7b2c-418b-adc5-489abaa5fa50" />

Representatives from both entities (Abacus Finance Group, Clearview Capital) were provided with constructive knowledge and documentation, including the settlement offer that violates SEC Rule 21F-17(a). If NextNet Media or its sponsors delete or fail to preserve anything after receiving those emails, that's an independent basis for an adverse inference instruction at trial or sanctions.


## Document Exhibit: Redacted API keys for fintech and cloud infrastructure platforms hardcoded into Git repos.
<img width="1145" height="702" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/8ade5063-62fd-4f75-b665-b1889909c73f" />
<img width="1264" height="261" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/35c39c3e-7601-4022-b123-4fc32778ee84" />
<img width="1181" height="699" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/ce8790b9-c622-4cff-9ed9-869249662946" />
<img width="1583" height="482" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/abedafc2-5dcc-4318-8c8f-cfba7a2b1adb" />
<img width="1497" height="189" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/d670ac22-09f4-498a-a44b-bba2a7fb05d0" />

## Document Exhibit: Work-authorized AI lists SOC2 violations.
Because I was granted full, unrestricted access to all NextNet Media repos inside GitHub, every commit was in plain sight. No hacking or unauthorized access - the front page of GitHub just shows you the most recent commits.

Some of the commits were from older legacy repos, while others were committed only days prior. Company policy allowed the usage of AI tools in a hybrid / remote environment, including for GitHub. The AI tool only parsed what was already visible on my screen - in the eyes of compliance frameworks, the foundational security failure is the act of hardcoding the secret in plaintext:

<img width="1554" height="790" alt="{NextNet Media SOC2 compliance violations.}" src="https://github.com/user-attachments/assets/ddf376db-bef8-45c4-bb19-24154370db76" />
<img width="1834" height="582" alt="{NextNet Media SOC2 compliance violations}" src="https://github.com/user-attachments/assets/3e090576-2e11-4446-86da-530afafa4041" />

## Frequently Asked Questions (FAQ)

#### Q: Is SOC2 a relevant compliance metric for NextNet Media?
A: NextNet Media is a B2B marketing entity that processes large transactions volumes, including from blue-chip clients, via fintech gateways - the answer is a resounding **yes**. That's like looking at a hospital and asking if HIPAA is relevant.

#### Q: Aren't you disclosing those API keys to Google / Gemini by doing this?
A: Company policy allowed the usage of AI tools in a hybrid / remote environment, including for GitHub. Google Gemini parsed the DOMs of what was already on my screen. Imagine you're wearing an authorized body-cam and someone runs butt-naked past the viewfinder. You don't blame the person wearing the body-cam, you ask why corporate security let a butt-naked person into the building.

#### Q: How do you still retain company documents after being terminated? Isn't that illegal or a form of CFAA?
A: Unfortunately for NextNet Media, their security protocols for many files amounts to "Anyone with Link" permissions. There are countless files and spreadsheets still shared with me or sitting under public access links, including entire databases of clients, B2B vendors, and operational expenses. There appears to be no offboarding procedure in place, as I've never received any sort of demands for return of company property - though they'd really just need to toggle a few permissions switches on their own end.

#### Q: Isn't this defamation? You're naming real people and companies.
A: Truth is an absolute defense to defamation in essentially every U.S. jurisdiction. You cannot defame someone with a screenshot of their own settlement offer. Every substantive claim in this dossier is backed by a document, a press release, or a public filing.

#### Q: Did you sign an NDA? Aren't you violating it by posting this?
A: 21F-17(a) analysis has repeatedly held that gag/confidentiality provisions don't survive scrutiny when they function to suppress regulatory disclosure.

#### Q: Why should Clearview Capital or Abacus Finance care about a contractor dispute at one portfolio company?
A: Because both received direct, documented notice with attached evidence, and continued inaction after actual knowledge is its own legal exposure. This isn't a portfolio company's internal HR matter anymore; it's a question of what the fund and lender knew, and when.

#### Q: At any point did you threaten or extort NextNet Media with your information for financial gain?
A: No. My settlement demand was strictly scoped to recovery of documented lost wages and fair value for the exclusive assignment of proprietary technical work product from my own repositories. These are both quantifiable, both independent of any regulatory activity. My whistleblower filings with the SEC, FinCEN, the Florida Attorney General, and other regulatory bodies were already in motion, and remain non-negotiable regardless of any commercial resolution. NextNet's own settlement offer, which conditioning payment on dismissal of federal complaints, is the only document in this dossier that actually ties money to regulatory silence, and it isn't mine.
