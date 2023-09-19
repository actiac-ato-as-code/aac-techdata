# Overview

Continuous ATO (C-ATO) is an organizational initiative to automate security compliance activity. In collaboration with industry, NIST is developing the Open Security Controls Assessment Language (OSCAL), a set of formats expressed in XML, JSON, and YAML. These formats provide machine-readable representations of control catalogs, control baselines, system security plans, and assessment plans and results. A security team will likely only work with OSCAL indirectly but through a tool. The purpose of OSCAL is a standardized, machine-readable format to share artifacts between Governance, Risk, and Compliance (GRC) and software automation tools or programs.

---

<div class="usa-alert usa-alert--info">
  <div class="usa-alert__body">
    <h4 class="usa-alert__heading">Use Case 1: Leverage Security Artifacts Between Agencies</h4>
    <p class="usa-alert__text">
      Agency A uses C-ATO to authorize a new platform. Agency B wants to authorize the same platform and leverage the machine-readable artifacts of Agency A to shorten their authorization process from months to days.
    </p>
  </div>
</div>

---

C-ATO can help streamline the generation and maintenance of A&A artifacts through automation. Currently, these activities are time-consuming and labor-intensive. Steps for C-ATO adoption:
1. define a strategy
2. make a plan
3. ready your organization
4. adopt C-ATO either through a tool or developer approach.
5. tweak your success trajectory through good governance and continuous improvement.

Note that i) and ii) may not be combined and labeled a strategic plan because there is no “strategic plan.” The strategy is an integrative set of choices that positions the organization on a playing field of your choice in the most successful way. That strategy must be coherent, doable, and actionable. Planning does not have to have any such coherence and is just a list of actionable activities required to deliver on that strategy.

Legislation (EO 14028, FISMA 2022) continues to be published, mandating advances in risk-based cybersecurity, modernization, and the adoption of next-generation security principles. This efficiency in process automation, advanced data processing, and expanded analytics capabilities is self-evident and creates a “data fabric” that allows agencies to achieve deeper insights and make evidence-based decisions. While data fabrics improve transparency, enable automation, and can provide more comprehensive governance and security controls, making it easier to comply with data privacy and compliance regulations, they are not to be confused with the data decentralization, autonomy, and productization of a federated or distributed GRC model that constitutes a “data mesh.” Data mesh is API-driven for developers, focuses on organizational change, and emphasizes the significance of people and processes. This results in greater collaboration between people and technology through a socio-technical approach of having domain experts own the data they create. Data fabric requires writing code for the APIs to interface, is technology-centric, and is an architectural approach that effectively manages the intricacies of data and metadata in a cohesive manner focusing on using technology and automation to connect and manage data. OSCAL enables the idea of a data fabric existing virtually in a data mesh environment by assembling a data record through the inheritance of the OSCAL artifact. Consequently, figure 1b illustrates a potential ‘strategy’ for automating an activity-centric process where a data record does not need to exist in one repository of a single platform.

# Literature Review

This is a collection of resources.

Table 1. Literature Review and Artifacts
| Source | Overview | Audience | Federal Relevant | Last Update |
| ------ | -------- | -------- | -------- | ------- |
| [Air Force Office of the Chief Software Officer Training Page](https://software.af.mil/training/) | Recommended books, videos, and DAU resources for DevSecOps. Nothing specific to OSCAL. | Developers | No | No date |
| [Awesome OSCAL Github Repo](https://github.com/oscal-club/awesome-oscal) and [OSCAL Club Site](https://oscal.club/) | A list of tools, blog posts, and other resources that further the use and adoption of OSCAL standards. A community project to leverage OSCAL to create tools and work through challenges using OSCAL. | General Audience, but more Developers | Yes | June 2023(?) |
| [GO OSCAL SDK Github Repo](https://github.com/GoComply/oscalkit) | Barebones GO SDK for working with OSCAL. | Developers | Yes | Oct 2023 |
| [FedRAMP Automation OSCAL Guides and Templates](https://github.com/GSA/fedramp-automation) | Various tools and guides to use and automate OSCAL for the FEDRAMP process. | Developers | Yes | Sep 2023 |
| [NIST OSCAL Tutorials](https://pages.nist.gov/OSCAL/learn/tutorials/) and [Github Repo](https://pages.nist.gov/OSCAL/learn/tutorials/) | NIST page providing step-by-step walk-throughs explaining how to create OSCAL content of various types. | Developers | Yes | 2023 |
| [Gocomply FedRAMP/OSCAL Converter](https://github.com/GoComply/fedramp) | Take a FedRAMP/OSCAL formatted System Security Plan and output FedRAMP documents. Take OpenControl repository and produce FedRAMP/OSCAL formatted System Security Plans. | Developers | Yes | June 2023 |
| [CIS Controls in OSCAL](https://www.cisecurity.org/insights/blog/introducing-the-cis-controls-oscal-repository) | OSCAL-formatted version of CIS Controls | Developers | Maybe | Oct 2022 |
| [Paper - A Cautionary Tale from a Security Control Baseline Tool](https://www.balisage.net/Proceedings/vol26/html/Lubell01/BalisageVol26-Lubell01.html) | Even the best written specifications can be complicated documents to read and understand. Normative prose is often supported by tables and diagrams that clarify the specification. What happens when a tool developer interprets those clarifying features as a different model than the prose intends? | Developers | Maybe | Aug 2021 |

# Current Status

The following government-wide programs or agencies have adopted C-ATO and are leveraging OSCAL.

1) FedRAMP - Adopting and moving all FedRAMP-authorized services to C-ATO through OSCAL.
2) ?
