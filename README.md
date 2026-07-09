# NextNet Media Security & Compliance Disclosure: SEC Rule 21F-17(a) Violations & SOC2 Failures

Mirrored on: [GitLab](https://gitlab.com/tony.s.celentano/nextnet-media-compliance-dossier) | [Codeberg](https://codeberg.org/TonyCelentano_ComplianceOps/NextNet-Media-Compliance-Dossier)

While working as an Engineer & Data Coordinator at **NextNet Media**, I discovered over 100 plaintext API keys for payment gateways, cloud infrastructure, and SaaS platforms that could leak sensitive data of both clients and employees. This represents a complete and utter failure of **SOC2, GDPR, CCPA, and SOX** security controls. The full list includes: Tipalti, Stripe, PayPal, AWS, ECS, MongoDB, Xero, SendGrid, ZenRows, and more.

<img width="845" height="269" alt="Plaintext API key exposure in NextNet Media production environment including Tipalti, Stripe, and AWS" src="https://github.com/user-attachments/assets/62f5e400-04eb-402b-85c2-74344f53e659" />

Even basic GitHub security scanning was disabled. Because the company employs both domestic and offshore developers, and utilizes **Tipalti** as an internal payroll mechanism, I feared for the financial well-being of coworkers who could become victims of private data theft.

I compiled a report of the security violations and sent it to the proper internal channel. In good faith, I offered to be part of the cleanup crew - within 48 hours, I was terminated without notice or cause. I also immediately lost access to my work emails and Tipalti portal, leaving me unable to download my payout records or 1099 forms.

<img width="1345" height="610" alt="Evidence of retaliatory access revocation to NextNet Media work email and Tipalti payroll portal" src="https://github.com/user-attachments/assets/b06f84fe-4b1c-4810-bffa-5704f423f93e" />
<img width="1773" height="599" alt="Account lockout notice for NextNet Media contractor following internal security vulnerability report" src="https://github.com/user-attachments/assets/f6d5396b-0801-408f-8690-2c7e5f5c4f65" />

I was told I'd receive a week's pay - when I pointed out my contract had a 30-day termination notice clause, I received radio silence. When I provided NextNet's legal counsel, **Koley Jessen**, with constructive knowledge - I was Mimecast blocked.

I filed **SEC, FinCEN, and OSHA** whistleblower reports, and sent a physical letter to NextNet LLC's address. In return, I received a settlement offer - $3,214 if I dismissed my whistleblower complaints with those federal bodies, released only upon "written receipt of closure and dismissal of any and all Complaints".

<img width="1175" height="927" alt="NextNet Media settlement offer violating SEC Rule 21F-17(a) whistleblower protections with illegal gag clause" src="https://github.com/user-attachments/assets/f9bd7348-db50-4e0b-b2cb-9a306d0cf2fa" />

This settlement offer, being a clear violation of **SEC Rule 21F-17(a)**, was added to my whistleblower reports. The SEC wrote this rule exactly because of the chilling effect that gag clauses have on whistleblowers.

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

<br>

## Document Exhibit: State of Florida Division of Corporations (Sunbiz) official registry for NextNet Media, LLC, renewed in 2026.
<img width="920" height="745" alt="State of Florida Sunbiz corporate registration and executive map for NextNet Media LLC" src="https://github.com/user-attachments/assets/2ffaa225-6de0-4d48-82e6-4295c9d1b4c8" />

Two members of Clearview Capital, a private equity firm in Stamford, CT, are registered as MANA partners on the NextNet LLC. This extends liability for NextNet's technical negligence and questionable tax filing practices to the fund itself - a fund [valued at $550m USD](https://pitchbook.com/profiles/fund/16376-50F).

## Document Exhibit: Redacted API keys for fintech and cloud infrastructure platforms hardcoded into Git repos.
<img width="1145" height="702" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/8ade5063-62fd-4f75-b665-b1889909c73f" />
<img width="1264" height="261" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/35c39c3e-7601-4022-b123-4fc32778ee84" />
<img width="1181" height="699" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/ce8790b9-c622-4cff-9ed9-869249662946" />
<img width="1583" height="482" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/abedafc2-5dcc-4318-8c8f-cfba7a2b1adb" />
<img width="1497" height="189" alt="{Plaintext API keys in GitHub, NextNet Media}" src="https://github.com/user-attachments/assets/d670ac22-09f4-498a-a44b-bba2a7fb05d0" />
