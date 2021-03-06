# Persistence on the web

#### Introduction

Through history we always attempted to pass information across generations using different media: oral communication, hand-writing, printing and digital form. The challenge of persistence - preserving information through time - is ensuring its survivability, integrity and availability. This challenge applies to the modern digital world when archiving documents and data that are meant to be persistent (e.g. public domain documents, encyclopedic entries, law cases, academic papers)

> Ensuring persistence can be often obstacled by natural factors (e.g. natural disaster), human interaction (e.g. censorship).

> Digital persistence. Multiple copies

> New opportunities. Multiple copiesp
Great new things that we will be able to do:
- Building on top of knowledge far in the future
- New discoveries -> finding the sources
- more on the vision

> This essay aims at understanding the importance of persistence of digital information analyzing the technological challenges and modern techniques for archival. The focus of this paper is on how we can achieve this using web technologies.

Persistance: the action of keeping of making something permanent through time
Permanence: remaining unchanged indefinitely
Archival: the act of mantaining an archive
Preservation: 

Defining the terms
- Persistance
  - Survivability: ability to survive obstacles
  - Integrity: ability of proving correctness throught tim
  - Availability: ability to be used at any time

survivability on the web
- personal data archival
- distributed storage

Problems of centralized archival
- Self-archival is difficult
- The maintainer and their responsibilities
  - Self-hosted require mantainance (not accessible to those with no technical knowledge)
  - Third-party depend on the persistence of the service (it may have a cost)
- URLs could be unreacheable and Web pages may disappear
  - downtime
  - censorship
  - under attack [find case]
  - expiration
- Expiration
  - Domain name can expire
  - Running services may disappear
- Accessibility: Not everyone has a domain name and storage
=> Finally, self-archival is a single point of failure for persistance

There is a need of distributing the content
- Distributed: Replicating the content
  - There is a need to make the content easy to distribute.
  - Hosted in multiple places
  - LOCKSS (Lot of copies keep stuff safe) - used by many libraries and projects: e.g. Perma.cc
  - Having the ability to retrieve it, point to it in case one of the place is down
- the open problem of naming
  - current system using centralized naming
  - distribute naming (that everyone agrees upon)
    - hashing (DHT, see IPFS)
    - consensus (mostly built by offloading blockchains see BlockStore)
  - who has the data? trusty uris can come handy
