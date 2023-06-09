# OA-TechOversight
Repository for the Overall Architecture and Technical Oversight focus group. In this repository we provide information and documentation about the work of this group.

## EJP-RD Virtual Platform information
Production environment - Resources that went through the onboarding process and the metadata have been checked for its accuracy:
- VP Index: https://index.vp.ejprarediseases.org
- Shared FDP[^1].: https://fdp.vp.ejprarediseases.org

Testbed environment - Development and testing environment. The content should only be used for these purposes and may not reflect reality:
- VP Index: http://fdps.ejprd.semlab-leiden.nl
- FDP: https://wp13.fdps.ejprd.semlab-leiden.nl

## EJP-RD Virtual Platform connection levels
The EJP-RD resource connection levels define options for resource providers to participate in the Virtual Platform in increasing degrees of interoperability. These levels represent different engagement requirements. The levels are:

| Level | Description | Contributes To | Technology Requirement(s) | Access Conditions Options |
| ----- | ----------- | -------------- | ------------------------- | ------------------------- |
| 1 - Resource discovery | At this level, the provider commits to make descriptive metadata of the offered resource available to the Virtual Platform via the VP Index. | Resource discoverability | FAIR Data Point specification, EJP-RD metadata schema| Open access |
| 2 - Content discovery | At this level, the provider answers questions regarding the presence (yes/no) and the amount (counting) of information in the resource based on selected filters. | Content discoverability | | Open access, authentication |
|   2.a - Individual record discovery | At this sub-level, the questions are answered against individual records of the resource's data. | Individual record discoverability | Beacon API - Individual endpoint, CDE | Open access, authentication |
|   2.b - Catalog discovery | At this sub-level, the questions are answered against the content of catalogues and their metadata. | Catalog and catalog content discoverability | Beacon API - Catalog endpoint, CDE | Open access, authentication |
| 3 - Data analysis | At this level, the provider commits to support analysis on its resource's content. | Data reuse and analysis | TBD | Open access, authentication, authorisation |

[^1]: This shared FDP URL is still being created.
