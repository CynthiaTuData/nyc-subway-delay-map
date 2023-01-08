# NYC Subway Delay Map

__For the final map, go to **https://xinyitu.github.io/nyc-subway-delay-map/**__

This is a class project mapping NYC subway delays on each train using mapbox. The map, much like a traffic map, shows delays by category on each subway line. Please note that the map does represent the real-time delays, but rather the overview of all delays in one month (November 2022).

### Steps taken 

- I scraped subway delay alerts in November, 2022 from ***https://mymtaalerts.com/archive*** using Playwright. 
- From the alerts, I developed a dataset of all delays that happened on each line in the month of November.
- All delays were then classfied into 14 types of delays using a self-developed taxtonomy. 
- Finally, I used mapbox to map the subway line based on count of delays in each categories.

For codes and processes, see .ipynb notebooks (there are four of them!)


### List of categories

|category name|meaning|
|---|---|
|Brake Malfunction|delays caused by brake being activated|
|Track Maintenance|delays caused by track work, rails replacement, and removing low-hanging wires over tracks, cleaning off stuff on the tracks|
|Disruptive Passenger|delays caused by disruptive passenger on trains/platforms, unauthorize person on the tracks, customer altercation, and people riding on the train|
|Mechanical Problem|delays caused by "mechnical problem" and door malfunction|
|Medical Emergency|delays caused by people needing medical help, EMS activity, person struck by train|
|Signal Malfunction|delays caused by signal malfunction|
|Power Outage|train power outages caused by power outages|
|Switch Malfunction|delays caused by "switch problem"|
|Cleaning trains|delays caused by the crew removing trains in need of cleaning, removing vandalizied cars|
|Police Activity|delays caused by NYPD conducting investigations on the train/in the station|
|Fire or Flooding|delays caused by FDNY, track on fire, smoke in trains, water on tracks|
|Other|rare events such as removing dog on track, making way for garbage trains to run on tracks, communications issues|
|Unknown Cause|delays with unspecified cause|




