## DoD Continuous ATO memorandum

[cATO memorandum](https://dodcio.defense.gov/Portals/0/Documents/Library/20220204-cATO-memo.PDF)

## Services Provided for Continuous ATO

#### Iron Bank: Approved hardened containers
#### Big Bang: Hardened kubernetes architecture
#### Party Bus: Hosted CI/CD pipeline built on Iron Bank and Big Bang
#### CNAP: Cloud Native Access Point - Reference architecture for cloud access

## Iron Bank

[General Description of Iron Bank](https://ironbank.dso.mil/about)

Iron Bank includes hardened baseline containers to build on top of, detailed instructions on how to harden your container, a pipeline that runs various scans and artifacts that can be used as part of an ATO. You need to register with repo1 to gain access, but you do not need a CAC.

[Vulnerability Asset Tracker](https://vat.dso.mil/)

Once your container is hardened following their guide, you can view results in the VAT (Vulnerability Asset Tracker). I believe you need to request access to the VAT.
![image](https://github.com/actiac-ato-as-code/aac-techdata/assets/65776483/48d19f18-73cd-4167-9e65-a900704a47dc)

- Findings Verified Percentage: How many vulnerabilities were found and how many have been addressed or have justification.
- Acceptance Baseline Criteria: Whether you are compliant or non-compliant along with a scorecard.
- Overall Risk Assessment Score: Percentage based on risk assumed by user of the container if not 100%.

Once a vendor is ready to submit for a continuous ATO (cATO), they merge their dev branch into main and the Iron Bank team reviews their submission. Once reviewed, Iron Bank can post it to the repository as compliant or non-compliant with a risk assessment score. DoD customers can still use the container, but now they know what type of risk they must accept in doing so.

Continuous ATO: As new vulnerabilities are found; containers are rescanned, and vendors have 48 hours to address vulnerabilities to remain compliant. Note: As a vendor, this has been very helpful in pushing our business units to patch software faster.

## Big Bang

You may need to register with Platform One to gain access to Repo1 and view the Big Bang repository. You do not need a CAC or Government email address.

[Big Bang Repo](https://repo1.dso.mil/big-bang/bigbang)

[Big Bang General Documentation](https://docs-bigbang.dso.mil/latest/bigbang-training/docs/Intro-To-Big-Bang/#What-does-Big-Bang-provide)

How Big Bang aligns to the ATO and cATO process:

[Big Bang Security](https://docs-bigbang.dso.mil/latest/bigbang-training/docs/1_bigbang-101/p1-security/?h=ato%2F#Core-Tenets)

This TerraForm template and guide can be followed to automate the deployment of Kubernetes according to the DoD approved hardened Kubernetes architecture:

[Big Bang Hardened Kubernetes IaC](https://repo1.dso.mil/big-bang/customers/template)

The IaC provided deploys Kubernetes according to this reference architecture:

[DoD DevSecOps Reference Architecture - Kubernetes](https://dodcio.defense.gov/Portals/0/Documents/Library/DoD%20Enterprise%20DevSecOps%20Reference%20Design%20-%20CNCF%20Kubernetes%20w-DD1910_cleared_20211022.pdf)

> •	“To achieve a cATO, a system must embrace the DoD Enterprise DevSecOps Strategy, aligning to an approved DevSecOps Reference Design.” - [DoD cATO Memo](https://dodcio.defense.gov/Portals/0/Documents/Library/20220204-cATO-memo.PDF)

Big Bang includes an oscal documentation component:
[Big Bang OSCAL](https://repo1.dso.mil/big-bang/bigbang/-/blob/master/oscal-component.yaml)

## Environment

For an ATO, you can use Iron Bank contains on your chosen flavor of Big Bang and deploy everything into an approved cloud, but to provide access to users the software must be behind CNAP (Cloud Native Access Point) or an equivalent security stack. The value of CNAP is that it’s all virtualized and meant to run inside of the CSP.

[CNAP Reference Architecture](https://software.af.mil/wp-content/uploads/2021/08/CNAP-RefDesign_ver-1.0-Approved-for-Public-Release.pdf)

# Guides for bringing it all together

[AWS Managed Service](https://dodcio.defense.gov/Portals/0/Documents/Library/DoD%20Enterprise%20DevSecOps%20Reference%20Design%20-%20AWS%20Managed%20Services_DoD-CIO_20211019.pdf)

[Azure, GitHub Architecture](https://dodcio.defense.gov/Portals/0/Documents/Library/DoDRefDesignCloudGithub.pdf?ver=zXJ_uO5LfouVaysHo5Ejsw%3d%3d)

All IaC and Pipelines are meant to align with the DoD DevSecOps reference architecture guides, which align with NIST controls, which should be used to achieve ATOs faster. If you follow their guides or use their automation, here is the mapping to NIST controls:

[DevSecOps NIST Control Mapping](https://dodcio.defense.gov/Portals/0/Documents/Library/DevSecOpsActivitesToolsGuidebookTables.pdf?ver=_Sylg1WJB9K0Jxb2XTvzDQ%3d%3d)

