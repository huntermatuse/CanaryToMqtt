# CanaryToMqtt

so the idea is to use the live data api endpoint to get tag data from canary, parse it and send it to mqtt where the tags are topics in mqtt and not sent all at once

will only support version 25 for now

v1 goals
- single canary subscriber 
- single mqtt publisher

v2 goals
- hanlde multiple canary live data subscriptions
- hand multiple mqtt publishers

v3 goals
- run forever

v4 goals
- have gui to set this up