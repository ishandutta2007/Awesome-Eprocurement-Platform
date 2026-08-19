# Awesome-Eprocurement-Platform

## Top eProcurement Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Source-to-Pay, Procure-to-Pay, Supplier Management, Purchase Orders, Spend Control & Procurement Automation*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **eProcurement**. These tools digitize and automate the full procurement lifecycle — from intake and requisitioning through sourcing, purchase orders, approvals, invoicing, and supplier management — helping organizations control spend, enforce compliance, and improve efficiency.

**Examples** include Coupa, SAP Ariba, Procurify, Zip Procurement, Precoro, Tradogram, Proactis, Basware, Oracle Procurement Cloud, and Jaggaer ONE (the category leaders and widely adopted platforms).

**Open-source emphasis**: Full enterprise-grade open-source eProcurement suites comparable to Coupa or Ariba are limited, but mature open-source ERPs provide strong procurement modules. This section prioritizes the most capable self-hostable solutions for purchase-to-pay, supplier management, and related workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

| Platform | Description | Pricing (Starting Tier / Est.) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Coupa](https://www.coupa.com/)** | Leading business spend management platform covering procurement, invoicing, expenses, and supplier collaboration with a large supplier network and strong analytics. | Enterprise custom quote (starts at ~$2,500/month / ~$30,000/year for core packages based on spend volume and modules) | No free tier or trial for core BSM platform (demo only); 30-day free trial available for Coupa Advanced Supplier Portal. |
| **[SAP Ariba](https://www.sap.com/products/spend-management/ariba.html)** | Enterprise source-to-pay suite deeply integrated with the SAP ecosystem, offering sourcing, contracts, procurement, and one of the largest supplier networks. | Enterprise custom quote (starts at ~$80,000–$150,000/year for baseline deployments plus spend/document volume fees) | No free tier or trial for buyers (guided demo only); free standard account available for suppliers responding to RFQs/POs on Ariba Network. |
| **[Procurify](https://www.procurify.com/)** | Modern procurement platform focused on spend visibility, approvals, and purchase order management for mid-market organizations. | Custom quote based on Pro licenses and modules (starts at ~$1,000/month / ~$12,000–$15,000/year billed annually; requester/Basic users included) | No free trial; interactive on-demand product tours and personalized live demo available. |
| **[Zip](https://ziphq.com/)** | Intake-to-procure platform that acts as a front door for employee requests, routing them through governed workflows into existing procurement and ERP systems. | Enterprise custom quote (starts at ~$40,000/year for intake workflows, scaling with user count, modules, and ERP connectors) | No free trial; custom sandbox demo upon sales qualification. |
| **[Precoro](https://precoro.com/)** | Cloud procurement software for purchase orders, approvals, inventory, and spend control, popular with growing companies. | **Core Plan**: Starts at $499/month (billed annually, includes core PO, PR, and approvals); **Automation Plan**: Starts at $999/month | 14-day free trial (full access to core features, no credit card required). |
| **[Tradogram](https://www.tradogram.com/)** | Procurement and purchasing management platform offering requisitions, POs, supplier portals, and reporting. | **Premium Plan**: Starts at $15/user/month (or custom quote for 20+ seats) | **Free Forever Plan**: 1 user, up to 10 transaction documents/month (POs/requisitions), basic dashboard, unlimited supplier/item records. |
| **[Proactis](https://www.proactis.com/)** | Spend management and eProcurement solution used by public sector and commercial organizations. | Enterprise custom quote (annual subscription tailored to transaction volume, deployment scope, and modules) | No free trial; vendor-guided demo only. |
| **[Basware](https://www.basware.com/)** | Strong in procure-to-pay and e-invoicing, with global compliance capabilities and AP automation. | Enterprise custom quote (tiered based on annual e-invoice volume, P2P modules, and ERP integrations) | No free trial; interactive demo and business case assessment available. |
| **[Oracle Procurement Cloud](https://www.oracle.com/erp/procurement/)** | Part of Oracle Fusion Cloud ERP, delivering source-to-settle processes tightly integrated with finance and supply chain. | Starts at ~$400–$650/hosted named user/month for specific cloud modules (or custom enterprise license agreement) | 30-day free trial via Oracle Cloud Free Tier ($300 cloud credits, subject to infrastructure services setup) or guided interactive tour. |
| **[Jaggaer ONE](https://www.jaggaer.com/)** | Comprehensive source-to-pay platform with strengths in direct materials, complex sourcing, and enterprise procurement. | Enterprise custom quote (modular annual subscription based on direct/indirect spend scope and user seats) | No free trial; customized solution walkthrough/demo available. |
| **[Ivalua](https://www.ivalua.com/)** | Unified source-to-pay suite handling direct and indirect spend, complex services, and supplier lifecycle management. | Enterprise custom quote (tailored to enterprise scale, contract length, and module selection) | No free trial; tailored product demonstration available. |
| **[GEP SMART](https://www.gep.com/software)** | AI-driven unified procurement platform covering spend analysis, sourcing, contract management, and procure-to-pay. | Enterprise custom quote (annual contract based on spend under management and user licenses) | No free trial; tailored enterprise demo available (free supplier portal access for registered vendors). |

## Open-Source GitHub Projects
- **[ERPNext](https://github.com/frappe/erpnext)** (Buying / Procurement module)  
  Fully open-source ERP with a mature procurement suite: material requests, request for quotation (RFQ), supplier portal, purchase orders, multi-level approvals, supplier scorecards, landed costs, and automated reordering. One of the strongest complete open-source options for procure-to-pay.
- **[Odoo](https://github.com/odoo/odoo)** (Purchase / Procurement apps – Community Edition)  
  Modular open-source ERP whose Purchase application covers RFQs, purchase orders, vendor management, agreements, and integration with inventory and accounting. Highly extensible via community modules.
- **[Apache OFBiz](https://ofbiz.apache.org/)**  
  Long-standing open-source ERP and e-commerce framework with procurement, purchasing, inventory, and order management components suitable for complex operational environments.
- **OpenProcurement / Prozorro-related projects**  
  Open-source e-procurement and tendering components originally developed for public sector transparency (notably associated with Ukraine’s Prozorro system) that can be adapted for competitive sourcing and tender workflows.
- **iDempiere & metasfresh**  
  Community-driven open-source ERPs that include purchasing, procurement, inventory, and supplier management capabilities.
- **Frappe / ERPNext Procurement Extensions**  
  Custom apps and workflows built on the Frappe framework that extend ERPNext with specialized purchase approval, PAR (Purchase Approval Request), and reporting features.
- **Procuman and similar open e-procurement initiatives**  
  Emerging or niche open-source platforms aiming to combine e-procurement, e-tendering, and supplier/CRM functionality.

### Additional Strong Open-Source Options
- Supplier portal and RFQ frontends that integrate with open ERPs.
- Approval workflow engines and document management tools commonly paired with procurement systems.
- Spend analysis and classification scripts or notebooks that operate on data exported from open ERPs.
- E-invoicing and EDI connectors available in open-source communities.
- Integration patterns linking open procurement modules to accounting and inventory systems.

**Frameworks for building custom systems**: Most organizations seeking an open eProcurement foundation start with **ERPNext** or **Odoo Community** because they already include end-to-end procure-to-pay flows, supplier portals, and approval engines. These can be extended with custom workflows, supplier scorecards, and integrations to existing finance systems. Full network effects, advanced AI spend classification, and global supplier catalogs remain strengths of commercial platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- eProcurement platforms should be evaluated for process coverage (intake → PO → invoice), approval flexibility, supplier collaboration features, ERP integration depth, compliance/audit capabilities, user adoption, and total cost of ownership.
- Open-source procurement modules give full data ownership and eliminate per-user licensing fees but require implementation effort, hosting, security hardening, and often additional development for advanced sourcing, contract management, or network features.
---
**Made for procurement leaders, finance teams, and organizations that want greater control over spend processes without perpetual vendor lock-in.**
Let's make procure-to-pay and source-to-pay technology more open, transparent, and accessible.