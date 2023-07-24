
***************************************************************
Bijan Bahari - Distortion Tech:
There is a limited amount of resources targeted towards implementation for developers; however, I did find a few good resources to look at, and I did see many various tools to review.
 
NIST Walkthrough tutorials: https://pages.nist.gov/OSCAL/learn/tutorials/
 
NISTS walkthrough tutorials seem like some of the best and most extensive documentation for developers to review; they detail how to create various OSCAL content, and when visiting the OSCAL GitHub, there are many examples of the data to review. ( https://github.com/usnistgov/OSCAL )
 
GSA Fedramp Automation Github: https://github.com/GSA/fedramp-automation/tree/master
The GSA fed ramp automation Git Hub includes various tools and guides to use and automate OSCAL for the FEDRAMP process. The guides are targeted at developers looking to implement solutions for leveraging OSCAL. Directions included cover SSPs, POAMS, SAPs, and SARs.
 
OSCAL.Club: https://oscal.club/
The OSCAL club is a community project to leverage OSCAL to create tools and work through challenges in using OSCAL. They maintain the awesome OSCAL GitHub with various projects and links. There is a litany of tools listed but below; I will be pulling out my thoughts on what would be the most pertinent ones:
•	OSCAL GUI - https://github.com/brian-ruf/OSCAL-GUI - this is a GUI for interacting with OSCAL. The tool looks like it is mainly for viewing OSCAL data now and doing format conversion. However, the following is either in progress or will be implemented in the future:
o	Metadata Management (all OSCAL layers)
o	Profile Creation/Manipulation
o	Catalog Creation/Manipulation
o	Back-Matter Management (all OSCAL layers)
o	OSCAL Format Conversion (XML/JSON to/from YAML)
o	SSP Creation/Manipulation
o	SSP FedRAMP Validation
o	Identity management
o	Access control (on a project-by-project basis) Functionality related to the assessment layers will be planned and developed as the syntax for those OSCAL layers is defined.
•	SSP toolkit: https://github.com/CivicActions/ssp-toolkit - This is for generating an SSP from OSCAL content
•	OSCAL REST API proposed standard: https://github.com/EasyDynamics/oscal-rest - this is a proposed REST API definition from easy dynamics. There will need to be interoperability between various tools with various functions, and a standardized REST API is essential in my opinion. 
 
OSCAL kit: https://github.com/GoComply/oscalkit
OSCAL kit is a barebones GO SDK for working with OSCAL. The SDK includes a CLI tool for processing OSCAL documents, converting between OSCAL-formatted XML, JSON, and YAML.
 
Gocomply FEDRAMP Github: https://github.com/GoComply/fedramp
Tool for manipulating official fed ramp assets
 
CIS controls in OSCAL: https://www.cisecurity.org/insights/blog/introducing-the-cis-controls-oscal-repository
 CIS has created a version of their controls in OSCAL format
***************************************************************

