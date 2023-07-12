<style>
body {
    background-image: url("./nde.jpg");
}
</style>

# Project ErfgoedPod

Start: July 1, 2020

Einde: June 30, 2023

The [Team Infrastructure of the Dutch Digital Heritage Network (NDE)](https://netwerkdigitaalerfgoed.nl/bruikbaar/#groep-bruikbaar) aims to redesign the way cultural heritage institutions and applications (eg. service portals that allow users to search for specific heritage data) exchange data. The current landscape shows a cascade of tightly coupled data aggregators, which has shown to be inflexible and lead to brittle integrations. As a result, both the data providing institutions and the aggregators have high maintenance costs, which are funds better spend elsewhere. Moreover, it leads to data duplication, with a subsequent loss of control for the cultural heritage institutions.

NDE's infrastructure envisions a discovery infrastructure that guides applications to the relevant original data sources, rather than aggregate and republish their data. The design integrates applications with institutions’s collection data in a more loosely-coupled manner, enabling institutions to reorientate their developed service integrations more easily to other vendors. To this end, NDE-Usable provides implementation guidelines, interoperability requirements and essential discovery services, ie. a register for dataset descriptions and a search index for shared terminology sources (Network of Terms).

The principles of Decentralized Web and Solid resonate strongly with NDE-Usable’s network design. Therefore, the ErfgoedPod project explores what a possible implementation of the NDE vision could look like when applying the Solid ecosystem. The project outputs a possible design of a decentralized exchange network for digital heritage data. ErfgoedPod shares the goals of the current NDE infrastructure, but is considered a research effort, and is therefore developed independently with a lower technology readiness level. In essence, the project tests whether the principles of a decentralized social network - actors announcing, sharing & following information - are a sustainable basis for exchanging digital heritage data.

The main project outcomes are protocols and components for creating generic decentralized exchange networks for various types of metadata pertaining artefacts, which is joint work with the ResearcherPod project. Additionally, ErfgoedPod provides a small background study, an architectural design and a descriptions of relevant use cases to apply these generic protocols and components in the digital heritage domain. This document captures the use cases that originate from the Team Infrastucture and the high-level design of a decentralized network for digital heritage artefacts. To that end, it identifies a list of representative roles and services in the Dutch Digital Heritage Network and the business processes that they should be able to execute. These business processes then serve as a basis for a proof-of-concept implementation of such network, as further outlined in the architecture specification.


## Concept


## Relationship to ResearcherPod


## Deliverables

### Documents

| Deliverable | Description | 
| ------- | ----------|
| [Use cases](https://erfgoedpod.github.io/usecases/) | Inventory of all digital heritage use cases developed in the project.   |
| [Infrastructure](https://erfgoedpod.github.io/common-setups/) |  |
| [Event Notifications](https://www.eventnotifications.net/) |  |
| [Architecture](https://erfgoedpod.github.io/architecture/) |  |
| [Terminology and specification overview](https://mellonscholarlycommunication.github.io/spec-overview/) |  |

### Software

| Deliverable | Description | 
| ------- | ----------|
| [evno](https://github.com/ErfgoedPod/evno) |  |
| [bashlib](https://github.com/SolidLabResearch/Bashlib) |  |
| [prototype](https://github.com/ErfgoedPod/prototype) |  |

## Dissemination

- June 3, 2021 - Seminar Digital CH (NL/VL) - STLab
- June 11, 2022 - Bootcamp open culturele data
- June 6, 2022 - Solid Amsterdam Meetup
- 

