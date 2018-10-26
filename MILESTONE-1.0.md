Milestone 1.0
-------------

# Roadmap

Below is the roadmap for eventzimmer 1.0
- [x] buy `eventzimmer.de`
- [x] prepare data privacy page
- [x] develop `@eventzimmer/api`
    - [x] use [neo4j](https://neo4j.com) to store events
    - [x] offer a GraphQL endpoint to search events
        - [x] include metadata (location, tags, date)
    - [x] offer a GraphQL endpoint to add new events
        - [x] add JWT for machine-to-machine communication to the endpoint
- [x] develop `@eventzimmer/aggregator`
    - [x] add Facebook
    - [x] add iCal import
    - [x] set up a machine-to-machine token for the add event endpoint
- [x] develop a progressive web app
    - [x] make it possible to filter events by
        - [x] location
        - [x] tags
        - ~~full text~~
        - [x] date
- [x] deploy
    - [x] main website to Netlify pages
    - [x] `@eventzimmer/api` to Hetzner Cloud
    - [x] `@eventzimmer/aggregator` to Raspberry Pi
- [x] check if [coinhive](https://coinhive.com/) can be used
- ~~use AWstats~~
- [x] hooray because that's the `1.0` release

