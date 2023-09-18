# Overview

OSCAL can help streamline the generation and maintenance of A&A artifacts through automation. Currently, these activities are time-consuming and labor-intensive. Steps for the adoption of OSCAL to realize ATO-as-Code are: 
1. define a strategy
2. make a plan
3. ready your organization
4. adopt OSCAL either through a tool or through a developer approach.
5. tweak your success trajectory through good governance and continuous improvement.

Note that i) and ii) may not be combined and labeled a strategic plan because there is no “strategic plan.” The strategy is an integrative set of choices that positions the organization on a playing field of your choice in the most successful way. That strategy must be coherent, doable, and actionable. Planning does not have to have any such coherence and is just a list of actionable activities required to deliver on that strategy.

Legislation (EO 14028, FISMA 2022) continues to be published, mandating advances in risk-based cybersecurity, modernization, and the adoption of next-generation security principles. This efficiency in process automation, advanced data processing, and expanded analytics capabilities is self-evident and creates a “data fabric” that allows agencies to achieve deeper insights and make evidence-based decisions. While data fabrics improve transparency, enable automation, and can provide more comprehensive governance and security controls, making it easier to comply with data privacy and compliance regulations, they are not to be confused with the data decentralization, autonomy, and productization of a federated or distributed GRC model that constitutes a “data mesh.” Data mesh is API-driven for developers, focuses on organizational change, and emphasizes the significance of people and processes. This results in greater collaboration between people and technology through a socio-technical approach of having domain experts own the data they create. Data fabric requires writing code for the APIs to interface, is technology-centric, and is an architectural approach that effectively manages the intricacies of data and metadata in a cohesive manner focusing on using technology and automation to connect and manage data. OSCAL enables the idea of a data fabric existing virtually in a data mesh environment by assembling a data record through the inheritance of the OSCAL artifact. Consequently, figure 1b illustrates a potential ‘strategy’ for automating an activity-centric process where a data record does not need to exist in one repository of a single platform.

# Literature Review

This is a collection of resources.

Table 1. Literature Review and Artifacts
| Source | Overview | Audience | Relevant | Current |
| ------ | -------- | -------- | -------- | ------- |
| [Air Force Office of the Chief Software Officer Training Page](https://software.af.mil/training/) | Recommended books, videos, and DAU resources for DevSecOps. Nothing specific to OSCAL. | Developers | No | No date |
| [Awesome OSCAL Github Repo](https://github.com/oscal-club/awesome-oscal) and [OSCAL Club Site](https://oscal.club/) | A list of tools, blog posts, and other resources that further the use and adoption of OSCAL standards. A community project to leverage OSCAL to create tools and work through challenges using OSCAL. | General Audience, but more Developers | Yes | Last update June 2023(?). |
| [GO OSCAL SDK Github Repo](https://github.com/GoComply/oscalkit) | Barebones GO SDK for working with OSCAL. | Developers | Yes | Oct 2023 |
| [FedRAMP Automation OSCAL Guides and Templates](https://github.com/GSA/fedramp-automation) | Various tools and guides to use and automate OSCAL for the FEDRAMP process. | Developers | Yes | Sep 2023 |

# Current Status

https://pages.nist.gov/OSCAL/

NIST Walkthrough tutorials: https://pages.nist.gov/OSCAL/learn/tutorials/

NISTS walkthrough tutorials seem like some of the best and most extensive documentation for developers to review; they detail how to create various OSCAL content, and when visiting the OSCAL GitHub, there are many examples of the data to review. ( https://github.com/usnistgov/OSCAL )

Gocomply FEDRAMP Github: https://github.com/GoComply/fedramp Tool for manipulating official fed ramp assets

CIS controls in OSCAL: https://www.cisecurity.org/insights/blog/introducing-the-cis-controls-oscal-repository CIS has created a version of their controls in OSCAL format

OSCAL Layers and Models: https://pages.nist.gov/OSCAL/concepts/layer/ Nists page on the layers and Models of OSCAL provides an excellent view of how each piece works together; additionally this can be very helpful for understanding the interconnection between components for automating the ATO process.

Easy Dynamics OSCAL Whitepaper: https://www.easydynamics.com/wp-content/uploads/2022/05/OSCAL-WP-1.pdf Easy Dynamics has a little white paper that summarizes what OSCAL is and what it can do in addition to an overview of a framework for OSCAL adoption consisting of a 6 step process for use in the SDLC process. Here are those steps:

Identify Target System
Educate Stakeholders
Select Target OSCAL artifacts
Define Responsibility
Develop Ongoing monitor approach
Implement OSCAL artifacts

Balisage Paper: The Model Made Me Do It! A Cautionary Tale from a Security Control Baseline Tool Developer : https://www.balisage.net/Proceedings/vol26/html/Lubell01/BalisageVol26-Lubell01.html

This was an interesting read from a security control tool developer. I wasn’t sure whether to include it, but I wanted to share for the larger group to read. The abstract is for reference: "Even the best written specifications can be complicated documents to read and understand. Normative prose is often supported by tables and diagrams intended to clarify the specification. What happens when a tool developer interprets those clarifying features as a different model than the prose intends? What does this say about relying on derived data models in tools that support the specification? A cautionary tale involving security control baselines from National Institute of Standards and Technology Special Publication 800-53 provides some answers — and insights."
