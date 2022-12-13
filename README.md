# Beryx Explorer
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


## Visit [Beryx](https://beryx.zondax.ch/)

---

This project is being built by Zondax

_Please visit our website at [zondax.ch](https://www.zondax.ch)_


---

## :warning::warning: DISCLAIMER :warning::warning:

#### This project is in beta stage. Please, feel free to report any bug you encounter with.

---


# About Beryx

The arrival of Filecoin Virtual Machine  ([FEVM / FVM roadmap](https://fvm.filecoin.io/#roadmap-4)) opens the doors to a new generation of block explorers for Filecoin. 

We aim to provide for all filecoin ecosystem participants, whether storage provider, storage client, developer, token holder or another type of user, a clear visibility and observability over the state and the activity of the network and the chain, both real-time and historical.

We want to build a fast, reliable and real-time block explorer that displays activity and interactions of native and EVM smart contracts. 

Not just another Filecoin block explorer, but the block explorer that could be also used as a reference for developers  that are building custom actors on Filecoin or dApps. 

This tool should put together dev tools for decoding actors for both EVM and native FVM, a block explorer and a mempool with real time streaming.


## Development Roadmap
### Milestone 1 - Dev tools first - The ultimate FEVM Actor decoder PoC 
#### Technical Scope and Timeline

Given the ambitious and tight roadmap for integrating the FEVM we propose to focus at the beginning of this project on what developers need and have been asking for the most: dev tools to decoding actors. 

During this short phase we will focus on creating an actor introspection tooling frontend (Dev tool). This PoC will focus initially in EVM and it will be extended to native FVM in the following milestones. 


#### Deliverables
- PoC capable of decoding  information about FEVM actors and related transactions.
- Dev Tools Tab with the PoC implementation
- Initial design mockups of the Block Explorer (Web + Mobile responsive).
- Running staging site with some UI elements implemented



### Milestone 2 -  Design finalization and Initial implementation of the block explorer 
#### Technical Scope and Timeline

This phase will focus on the finalization of the design and implementation of most of the basic features of the Block explorer in addition to the Dev-Tools PoC capability (see M1). 

This phase will put a big focus on the design and its scope will consist of representing the look and feel of the Block explorer and defining in high level of detail its features, how everything is connected and how users will interact with it. 

To retrieve the data from the Filecoin Blockchain we will use our own public Data API and indexer. 

#### Deliverables
- Functional block explorer (internal release, pw protected) hosted and maintained by us. 
   - Responsive design - Web + mobile support (browser based)
   - Real-time updates based on changes in the network
   - Fast to load
   - Good UX and visual design
-  High-fidelity design mockups 


### Milestone 3 -Block explorer additional features FVM and release 
#### Technical Scope and Timeline

During this phase we will focus on testing, documentation of the code base,  as well as the implementation of additional features. We provide a tentative list of features, however, if the needs from the FVM Core team or the community request us to prioritise others, we will do our best within our capability to adapt and bring those features alive. 

At the end of this phase will go live and make the project deliverables public and open sourced (live website, documentation,explorer codebase).

#### Deliverables
- Fully functional block explorer website, hosted/maintained/managed by our team
- Publicly accessible via a https:// site.
   - Must also work on mobile and be mobile-friendly
   - Real-time updates based on changes in the network
   - Fast to load
   - Good UX and visual design


### Milestone 4 -   Iterative improvements with native FVM updates 
#### Technical Scope and Timeline

We  will provide a tentative list of features that we would like to prioritise with the FVM core team. Future developments on FVM will highly depend on the roadmap and definition provided by the FVM core team. 

#### Deliverables
Continuous integration and Deployment

## Documentation, Education, and Community
Before official release we will invest time and effort in providing a high quality documentation of both, the code base and user facing documentation. 

We will use the FVM channels, programs like the FVM Early builders, conferences and events to promote the application and collect feedback from the community. 


