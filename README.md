# Release notes - inxware-Lucid - 2.1.6

### Bug

[II-516](https://inxiot.atlassian.net/browse/II-516) Tools Installer: When you run eRT from the installed tools, it fails to launch

[II-538](https://inxiot.atlassian.net/browse/II-538) GPIO Simulator widgets are too large and overlaps all normal UI widgets.

[II-544](https://inxiot.atlassian.net/browse/II-544) Crash running the home app with LVGL build

[II-548](https://inxiot.atlassian.net/browse/II-548) iAB and iGB don't seem to be backwards compatible when it comes to gui files

[II-567](https://inxiot.atlassian.net/browse/II-567) blink timer is sometimes causing crashes

[II-568](https://inxiot.atlassian.net/browse/II-568) state machine manager still blinks when connected

[II-569](https://inxiot.atlassian.net/browse/II-569) output tag disappears when its input tag is removed, even when there are still some other input tags

[II-582](https://inxiot.atlassian.net/browse/II-582) Add GUI widget titles and widgetnames \(as displayed paramter\) on Functions blocks 

[II-583](https://inxiot.atlassian.net/browse/II-583) Gauge/dial widgets should use the background and foreground colours \(and the label should be placed at the bottom so it doesn't overlap the legends\).

[II-587](https://inxiot.atlassian.net/browse/II-587) When clicking on "Tutorial Apps" in Help menu, the file dialog points to a wrong place

[II-588](https://inxiot.atlassian.net/browse/II-588) Moving the LVGl gauge dynamically makes it change shape.

[II-595](https://inxiot.atlassian.net/browse/II-595) LVGL : Stability issue on Windows \(Linux too?\) eRT

[II-606](https://inxiot.atlassian.net/browse/II-606)  putting "..." in a paramter breaks SODL parser \(duplicated\)

### Task

[II-241](https://inxiot.atlassian.net/browse/II-241) Run Project on ESP32 target

[II-536](https://inxiot.atlassian.net/browse/II-536) Create a manual switch to disable font transfer

[II-540](https://inxiot.atlassian.net/browse/II-540) iCB : make sure c-code generator create consistent format of the function code

[II-546](https://inxiot.atlassian.net/browse/II-546) Creating gui widget and renaming them before save and open iGB removes them from gui files.

[II-551](https://inxiot.atlassian.net/browse/II-551) ESP32 Initial WiFi configuration.

[II-552](https://inxiot.atlassian.net/browse/II-552) WIdget function blocks need better labelling

[II-556](https://inxiot.atlassian.net/browse/II-556) add some further paramters to LVGL

[II-558](https://inxiot.atlassian.net/browse/II-558) Ensure failed gui config or runtime problems don't affect other functionality \(i.e. fail parsing or crash later\)

[II-560](https://inxiot.atlassian.net/browse/II-560) Make sure the gui object from Mode A are working and merge lvgl dev branch to the master

[II-561](https://inxiot.atlassian.net/browse/II-561) Upgrading legacy applications function blocks

[II-597](https://inxiot.atlassian.net/browse/II-597) Get TSL to work for MQTT Greengrass on both Linux and Windows

### Sub-task

[II-526](https://inxiot.atlassian.net/browse/II-526) Check if MQTT green grass works on Linux

[II-562](https://inxiot.atlassian.net/browse/II-562) Update TSA app to work with new function blocks

[II-563](https://inxiot.atlassian.net/browse/II-563) Update Player app to work with new function blocks

[II-564](https://inxiot.atlassian.net/browse/II-564) Update Home app to work with new function blocks

[II-565](https://inxiot.atlassian.net/browse/II-565) Update tutorial apps to work with new function blocks part 1

[II-566](https://inxiot.atlassian.net/browse/II-566) Update tutorial apps to work with new function blocks part 2

[II-571](https://inxiot.atlassian.net/browse/II-571) iGB : Add rounded corners parameter widgets

[II-572](https://inxiot.atlassian.net/browse/II-572) iGB :  Add 1-10 style enumeration in the widget prop parameter

[II-573](https://inxiot.atlassian.net/browse/II-573) iGB : Add label on iGB widget object, which indicates widget type e.g. Button, Slider etc. 

[II-574](https://inxiot.atlassian.net/browse/II-574) eRT : Update gui parser, so that it handles the new parameters

[II-575](https://inxiot.atlassian.net/browse/II-575) eRT : Make a use of foreground/background colors for gauge and other lvgl ui

[II-576](https://inxiot.atlassian.net/browse/II-576) eRT : Hookup lvgl widgets with new style and parameters

[II-577](https://inxiot.atlassian.net/browse/II-577) Check if fixing widget rectangle colors is possible

[II-578](https://inxiot.atlassian.net/browse/II-578) iGB : Add placeholder for widget parent parameter

[II-579](https://inxiot.atlassian.net/browse/II-579) Update apps repo with new gui file format

[II-580](https://inxiot.atlassian.net/browse/II-580) Hide toolbar/menubar items that are used for uploading to device

[II-603](https://inxiot.atlassian.net/browse/II-603) TSL for MQTT Linux

[II-604](https://inxiot.atlassian.net/browse/II-604) TSL for MQTT Windows

[II-607](https://inxiot.atlassian.net/browse/II-607) Add default 'clientID' string for MQTT in order to prevent Linux lib from asserting when port isn't connected \(duplicated\)

[II-612](https://inxiot.atlassian.net/browse/II-612) Investigate why we get Error: Unexpected EOF in SODL file

### Story

[II-245](https://inxiot.atlassian.net/browse/II-245) Can we get greengrass running on windows for MQTT?
