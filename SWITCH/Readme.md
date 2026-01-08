# This file I am installing a swtich in cisco packet tracer and will check version and than enable switch in CLI and making time change so i can figure out same time what is working or not and 
everything will done in CLI (COMMAND LINE INTERFACE)

Switch> Show version

## The troubleshooting process are here as follows -

Switch> enable
Switch# Show clock
//It might show wrong thing here and if it does than follow the bottom steps as well
Switch# clock set ?
Switch# clock set 12:12:00 ?
Switch# clock set 12:12:00 jan 7 ?

Switch# clock set 12:12:00 jan 7 2026
//Here i Have set up the new time in clock

Switch# Show clock
// Should fix this now and show you right time and date which we set now

Part 3:  (Optional) Access a Cisco Router Using a Mini-USB Console Cable
