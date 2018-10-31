Milestone 1.1
-------------

# Roadmap
Below is the roadmap for eventzimmer 1.1

- `@eventzimmer/api`
    - [ ] implement a source prediction (when to fetch source next)
    - [ ] implement a transactional source system so sources will be pulled less frequently
- `@eventzimmer/aggregator`
    - [x] implement a _"force_source_fetch"_ where you can force an individual source to be pulled again
      - [x] implement local locations list as a fallback
    - [x] make the whole thing more robust
    - [ ] support proxies (we do, but test them)
    - [ ] use the new transaction system to add events
- `@eventzimmer/app`
    - [ ] refactor store, add more tests
