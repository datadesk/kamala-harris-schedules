An open-source archive of Vice President Kamala Harris' public calendar

Drawn from the Los Angeles Times article "What’s on Kamala Harris’ calendar? Tracking the vice president’s public events." Updates continually.

## Data dictionary

field|type|description
:----|:---|:----------
`order`|string|The chronological order of events
`time_zone`|string|The abbreviation of the time zone of the event
`timestamp`|datetime|The date and time of the event
`event_list`|string|The items planned for the event
`press_event`|boolean|Was the press allowed access?
`press_category`|string|What type of press access was allowed?
`involves_biden`|boolean|Was President Biden present?
`involves_world_leader`|boolean|Was the vice president meeting with a world leader?
`involves_flight`|boolean|Did the event involve air travel?
`involves_covid`|boolean|Did the event involve COVID-19?
`involves_voting`|boolean|Did the event involve voting rights?
`involves_immigration`|boolean|Did the event involve immigration policy?
`involves_afghanistan`|boolean|Did the event involve Afghanistan?
