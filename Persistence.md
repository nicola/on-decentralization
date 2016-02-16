# Persistence on the web

- Building on top of knowledge far in the future
- New discoveries -> finding the sources
- more on the vision

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
