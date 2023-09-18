# Executive Summary

This is not OSCAL-as-Code, this is ATO-as-Code. OSCAL is a secondary support technology that is disruptive to the activity-centric model pervasive across government. Adopting OSCAL models EDI (electronic data interchange) that is data-centric to streamline the ATO lifecycle.

To take full advantage of OSCAL, organizations will have to divide compliance activities into specialties, perform a value-chain analysis to drive cost-efficient automation, and promote an outcome-based work-performance philosophy with greater autonomy for primary actors to optimize their respective activities by incorporating emerging and assistive technologies.

OSCAL is not about sharing data, OSCAL is about reusing compliance artifacts towards greater automation and evolving ATO-as-Code. Data sharing falls under the Open Cybersecurity Schema Framework (OCSF) and the concept of security data lakes that are an amalgam of agnostic unstructured data from disparate data repositories. Agencies may apply machine learning and perform analytics from data in security lakes to drive artificial intelligence. This intelligence of identifying-to-mitigate real-time vulnerabilities and emerging threats go well beyond the level of compliance required, however compliance automation and security intelligence are the two pillars to “Smart Cybersecurity Systems & Services”.

Successful adoption of OSCAL will result in a data-centric model for the organization to automate and mature towards ATO-as-Code. As a workforce multiplier, individuals will have more time to invest in security intelligence to apply next generation security practices that will be driven by machine learning and artificial intelligence. The challenge is overcoming the inertia of the prevailing culture and a degree of ignorance that is proving to be very resistant to this magnitude of change. 

## Key Terms

Reference the NIST Glossary if possible. https://csrc.nist.gov/glossary/term/oscal

## Audience

Primary: Leadership plays a role in an organization to engender and encourage the employees to change for the organization, to exude confidence in being able to sustain and adapt to the business environment, and to promote the merits of innovation through empowerment. Successful change management demands effective communication from leadership to keep employees aware and involved in change process that they must themselves understand. This reduces tension and conflicts caused by not knowing what's going on and ensures that everyone is heading the same way during the change process.

Secondary: Management is responsible for identifying idea champions, finding ideas that contribute to successful change, and establishing a coalition to guide change. The coalition, or change management team, is tasked with making sure the organization’s end-user stakeholders—or everyone impacted by the change—are ready to transition when the change comes. The two teams must work together from one playbook, as readiness for change hinges on consistent messaging to maintain a high level of engagement from stakeholders and concerted commitment from the masses toward the project or change initiative.

## Disclaimer

This playbook is not an official policy, mandates agency action, nor does it provide authoritative information technology terms. It includes best practices to supplement existing federal policies and builds upon Executive Orders 13859 (2019), 14028 (2021), the 2019 Federal Cloud Migration Strategy (Cloud Smart), the President’s Management Agenda (July, 2020), and existing NIST guidance and playbooks such as the Security Authorization Process Guide (v11.1 2015) published by the DHS CISO. Subject areas with intersecting scopes, such as the Open Cybersecurity Scheme Framework (OCSF) and Zero Trust Architecture, are considered only to the extent they relate to identifying and implementing OSCAL towards ATO-as-Code.

# First 100 Days

Explain in plain language the key information for everyone to understand. Include known challenges, lessons learned, graphics, or risks before starting on a pilot.

**Figure 1.**
![Each OSCAL file imports information from the one before it.](https://github.com/actiac-ato-as-code/aac-techdata/blob/playbook/f1-oscal.png)

1)	Implement a Work Management Platform (WMP) (not project management) (perpetual tasks – not one task) to drive out-come based performance that supports division of labor and aligns with the OSCAL-based versions of file content (see below).
2)	Initiate division of compliance activities (labor) – to enable automation, for greater autonomy and empower grass-roots process optimization.
3)	Value chain analysis - self-explanatory and accountability for work performance and business process management (automation) to deliver metrics to identify candidates for automation.
4)	Pursue an “information maturity” model (not a process maturity model which perpetuates the antiquated activity-centric process) as a roadmap (see below) to shift from activity-centric to data-centric practices with a new lifecycle and information models (the video I shared and Greg spoke about).
5)	Contemplate abandoning monolithic GRC architectures in favor of a more-agile modular model that OSCAL enables - in anticipation of accelerated and imminent change with the adoption of next-generation security practices, exploring niche commercial solutions that provide an annual subscription cloud-based solutions that introduce the OSCAL capability: For example, a system security plan (SSP) authoring tool delivers the OSCAL capability for immediate adoption until migration of an agencies applications to the cloud is complete (Cloud Smart 2019). This transfers the onus of producing and maintaining SSPs from agencies to the cloud service providers, and preliminary security assessments will be performed by the FedRAMP PMO.

**Figure 2.**
![Stages of expansion.](https://github.com/actiac-ato-as-code/aac-techdata/blob/playbook/f2-stage.png)

7)	UUIDs are integral in adopting OSCAL with version control, resource identification, and security protocol. This is an enterprise architecture unto itself that is necessary to successfully adopt OSCAL and beyond my complete understanding right now.
8)	This is where the data schema experts can source or publish a ‘glossary’ or how to apply a ‘standard’ for tags to jump-start XML developers in the digitization of SSPs. Focus on XML, as NIST offers a tool to convert XML to JSON. The means and techniques to digitize SSPs will vary across agencies and it will be a hand-mash exercise as there is no ‘tool’ in existence that can perform this given the ‘uniqueness’ of how SSPs are constructed.

**Figure 3.**
![OSCAL Stakeholders.](https://github.com/actiac-ato-as-code/aac-techdata/blob/playbook/f3-stakeholders.png)

8)
    1)	Begin the adoption of OSCAL by marking up existing SSPs in XML (digitization) for digestion into an application as a living document. This may be an opportunity to revert the ISSO-centric practice that has evolved back to the Security Authorization Team model as drafted by the DHS CISO in the Security Authorization Process Guide (v11.1, 2015) under section 2.5 as modeled in figure 1 and shown on the right. This step should not precede an application to maintain the digitized SSP as a living document. Verify the integrity of the digitized OSCAL SSP with digestion into the Government Book of Record.
    2)	Begin testing the receipt of FedRAMP security assessments that are formatted in OSCAL. Fine-tune the receipt to automate preliminary assessment similar to the practice of the FedRAMP PMO in an automated preliminary assessment of SSPs presented by Cloud Service Providers. Submit a non-cloud OSCAL SSP created by the agency for a security assessment to hone process automation.
    3)	With a view to submitting POA&Ms in OSCAL format, begin converging POA&M administration into the vulnerability management program.
9)  Begin collecting business process metrics from the WMP to improve the value proposition of compliance activities, identify candidates for automation, and empower participants to optimize the respective process by applying assistive technologies.
10)	Expand the controls implemented in the SSP to emerging threats as discovered in real-time through security intelligence. The optimal result is a continuum of real-time updates in security assessment documentation, governed by human intervention at the assessment stage and ingestion of trigger events to update the policy engine in Zero Trust Architecture for immediate enforcement. 

# <Topic> Playbook

What is the 3-5 step plan for an organization to get started. Include prerequisites, stakeholders, or anything else. Keep to 3-5 steps. Not meant to be a technical approach, but to help a program manager develop a pilot or maybe implementation.

## First steps

1.	Magnitude of disruption – maturing information management
2.	Emergent strategy and planning – no such thing as strategic planning
3.	Satisfying prerequisites for success
4.	Taking small steps in the right direction
5.	Addressing unsolved opportunities

# References

List of references used in the playbook.
