eventzimmer
-----------

This is the main repository of the eventzimmer event service.
It is used to track issues and coordinate development.

## Roadmap

Below is the roadmap for eventzimmer 1.0
- [x] buy `eventzimmer.de`
- [x] prepare data privacy page
- [x] develop `@eventzimmer/api`
    - [x] use [neo4j](https://neo4j.com) to store events
    - [x] offer a GraphQL endpoint to search events
        - [x] include metadata (location, tags, date)
    - [x] offer a GraphQL endpoint to add new events
        - [x] add JWT for machine-to-machine communication to the endpoint
- [ ] develop `@eventzimmer/aggregator`
    - [ ] add Facebook
    - [ ] add iCal import
    - [ ] look into [festivalticker](https://www.festivalticker.de/) and [goabase](https://www.goabase.net/)
    - [ ] set up a machine-to-machine token for the add event endpoint
- [ ] develop a progressive web app
    - [ ] make it possible to filter events by
        - [ ] location
        - [ ] tags
        - [ ] full text
        - [ ] date
- [ ] deploy
    - [ ] main website to Netlify pages
    - [ ] the wpa to the app store(s) (maybe this can be done automagically too)
    - [ ] `@eventzimmer/api` and `@eventzimmer/aggregator` to Hetzner Cloud
- [ ] check if [coinhive](https://coinhive.com/) can be used
- [ ] check if we can get free piwik or if Google Analytics is feasible
- [ ] hooray because that's the `1.0` release

