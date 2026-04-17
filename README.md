# Overview
This site provides an overview of the artifacts associated with the ePublication platform.

> [!NOTE]
> This page provides an overview of the various topics related to ePublication. 
>
> Information about the API can be found in [this repository](https://github.com/epublication/epublication-api).

## Harmonization of Swiss Official Publications
To gain a deeper understanding of the idea behind the efforts to harmonize official publications, it is important to understand the responsibilities of the respective parties. The primary objective is to ensure that each editor maintains control over its own data. In keeping with Switzerland’s federal system, this should also take into account cantonal and municipal specificities.

### Responsibilities
The State Secretariat for Economic Affairs SECO is responsible for operating the platform. Editors use it for publication of their gazettes, in which announcements are published by publishing entities. These three main players have different roles:

**The provider** provides the technical infrastructure (the core system) and defines the announcement standard.

**The editor** uses this standard in the form of predefined announcement types. They ensure that these announcement types comply with legal requirements.

**The publishing entity** creates the actual announcements based on these types and publishes them in the official gazette on schedule. They are responsible for the content of the published announcements.

Each announcement is therefore based on an announcement type from the respective gazette. Consumers have no responsibility—they obtain the announcements via the gazettes.

<img width="1412" height="896" alt="image" src="https://github.com/user-attachments/assets/7ea2a3ea-267a-4939-8b59-a460dd605825" />



### Why harmonization is important
Harmonization and standardization allows announcements to be found using uniform filters across geographical and federal levels. It also facilitates the automated processing of announcements and the connection of upstream and downstream processes. This also simplifies the creation of new gazettes.
The provider standardizes a complete catalog of all announcement elements (announcement element catalog) and uses it to model all possible announcement types (announcement type catalog). Editors select the announcement types that are suitable for their gazette and can configure them individually as needed. Publishing entities use the configured announcement types as the basis for their announcements. Announcement types are the publication templates for the announcements.


<img width="1086" height="817" alt="Standard_EN (002)" src="https://github.com/user-attachments/assets/f7a70a64-0f80-4d16-acbe-dfaa486801c2" />



## Glossary ##
It is important to clarify a few terms. These individual terms are briefly described below.

**Announcement type**
- Is the publication template for an announcement and thus determines its structure
- Combines announcements that are similar in structure and content
- Exists for announcements that are published repeatedly in the same form in a certain volume.
- Provides specifications for publication modalities and search parameters.
- Are made available in a central catalog for all gazettes.
- Can be used and adapted (e.g., renamed) by editors for their gazette.
- Editors can determine which organisation types (e.g., “court”) are allowed to access which announcement types.

**Business case**
- Divides the announcement types into different categories or describes them in more detail.
- Always displayed first in the title.
- Has the same content elements within an announcement type.
- Editors can use the business case to specify default values for legal notices and deadlines.
- The name of the business case can be changed by the editor.

**Topics**
- Is a fixed set of thematic terms that can be applied to announcements.
- A topic may already be predefined by the announcement type.
- Possible topics are predefined by the announcement type and cannot be configured by the editor.
- May/must be added to the announcement by the publishing entity, depending on the announcement type.
- The names of the topic terms cannot be customized by the editor.
- Each announcement has at least one topic.
- Announcements can be filtered by topic on the platform.


