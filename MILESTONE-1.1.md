Milestone 1.1
-------------

# Roadmap
Below is the roadmap for eventzimmer 1.1

- `@eventzimmer/api`
    - [ ] implement a default location that is used if no location is provided on event creation
        - [ ] make location optional
    - [ ] implement a source prediction (when to fetch source next)
    - [ ] implement a transactional source system so sources will be pulled less frequently
- `@eventzimmer/aggregator`
    - [ ] use the new transaction system to add events
