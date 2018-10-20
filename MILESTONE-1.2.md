Milestone 1.2
-------------

# Roadmap

- `@eventzimmer/app`
    - [x] add a like button and store likes in local db
	- [ ] use localForage as storage engine (migrate away from localStorage)
        - [ ] add a suggestion engine with tensorflow.js which will suggest events based on likes
    - [ ] make it possible to change city in the filter
    - [ ] add full text search
- `@eventzimmer/admin`
    - [ ] brainstorm a simple dashboard where you should be able to
        - see sources, locations, entities
        - add / delete sources, locations, entities
        - see stats using telemetrics
    - [ ] use some iCalendar for moderators to add events
