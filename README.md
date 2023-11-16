# Release notes - inxware-Lucid - 2.1.7

### Bug

[II-82](https://inxiot.atlassian.net/browse/II-82) Fill in the details for the Application Server doc \(System/Remote/Application Server\)

[II-277](https://inxiot.atlassian.net/browse/II-277) Tags are sometimes created in a wrong position, which gets corrected when FBs are moved

[II-331](https://inxiot.atlassian.net/browse/II-331) The EHS is unable to get the IP Address of WiFi network devices

[II-427](https://inxiot.atlassian.net/browse/II-427) The hit boxes of the lines and FBs don't seem to line up with what's rendered

[II-492](https://inxiot.atlassian.net/browse/II-492) eRT -Issue to solve: scanf fails if some outputs are not connected. e.g. if out a is not connected \(cos we want to ignore it\) then result 2 doesn't happen either.

[II-502](https://inxiot.atlassian.net/browse/II-502) Pathspec for tutorials directory required

[II-517](https://inxiot.atlassian.net/browse/II-517) Windows Workspace scrolls when draging a line

[II-525](https://inxiot.atlassian.net/browse/II-525) Sometimes there is a small offset on mouse and screen \(seen on Windows with external HD monitor\).

[II-544](https://inxiot.atlassian.net/browse/II-544) Crash running the home app with LVGL build

[II-547](https://inxiot.atlassian.net/browse/II-547) Tools show all sort of errors e.g. nsl, when opening tutorial app e.g. hello world

[II-590](https://inxiot.atlassian.net/browse/II-590) Zoom in-out can create a mouse click offset which make connecting of ports very difficult

[II-601](https://inxiot.atlassian.net/browse/II-601) LVGL : keyboard function block do not work in TSA app

[II-619](https://inxiot.atlassian.net/browse/II-619) inxwaere is installed as BRIX on windows. 

[II-621](https://inxiot.atlassian.net/browse/II-621) When FBs are dragged beyond the limits of the canvas, it can offshoot quickly, expanding the view unnecessarily

[II-625](https://inxiot.atlassian.net/browse/II-625) Instance Properties should be called Parameters in the top right box

[II-627](https://inxiot.atlassian.net/browse/II-627) Still gettnig strange SODL parsing \(and crashing EHS\)

[II-630](https://inxiot.atlassian.net/browse/II-630) hello world project window is small and doesn't fill work space when opened for the first time

[II-631](https://inxiot.atlassian.net/browse/II-631) zoom out goes too far and is easy to lose projects, either put a cap on zooming out or a way to find your project easily

[II-632](https://inxiot.atlassian.net/browse/II-632) when zoomed out and trying to highlight blocks the pan is too sensitive and can move very quickly

[II-647](https://inxiot.atlassian.net/browse/II-647) curser not lined up when in tilt view

[II-650](https://inxiot.atlassian.net/browse/II-650) Graph Widget doesn't change the number of points displayed when values are set in the paramters. 

[II-654](https://inxiot.atlassian.net/browse/II-654) crashyness on windows

[II-655](https://inxiot.atlassian.net/browse/II-655) disable app send icons in iGB - Would be nice if save could refocus Lucid \(iAB\) to prompt user to send that way.

[II-657](https://inxiot.atlassian.net/browse/II-657) Output event from example html hasn't been removed

[II-658](https://inxiot.atlassian.net/browse/II-658) Change the "line spacing" label in iGB to "Font Size" or add a speific font size paramter in .gui files

[II-661](https://inxiot.atlassian.net/browse/II-661) List Widget does seem to appear as a widget to edit in LGB

[II-663](https://inxiot.atlassian.net/browse/II-663) LogicAnd3 HTML file exists but isnt linked in Lucid

[II-666](https://inxiot.atlassian.net/browse/II-666) Chart and spinner files not linked to lucid

[II-670](https://inxiot.atlassian.net/browse/II-670) ADC paramter validiors are crazy

[II-674](https://inxiot.atlassian.net/browse/II-674) Random crash on Windows when opening project. Seems to be ftgl related.

[II-675](https://inxiot.atlassian.net/browse/II-675) Graphical bug in ADC component

[II-681](https://inxiot.atlassian.net/browse/II-681) typo on the digit display component

### Task

[II-241](https://inxiot.atlassian.net/browse/II-241) Run Project on ESP32 target

[II-506](https://inxiot.atlassian.net/browse/II-506) We also need to change the user directory for eRT from ~/.brix/ to ~/inxware/

[II-507](https://inxiot.atlassian.net/browse/II-507) Tutorials should be in the app installation directory? \(This directory is usually hidden\) Move it to Documents

[II-509](https://inxiot.atlassian.net/browse/II-509) cosh FB has an old format/outdated help file

[II-514](https://inxiot.atlassian.net/browse/II-514) abs block block type i LogReal instead of Abs

[II-539](https://inxiot.atlassian.net/browse/II-539) Tidy-up inxware-tools installer

[II-553](https://inxiot.atlassian.net/browse/II-553) Review and update UI Widget HTML

[II-557](https://inxiot.atlassian.net/browse/II-557) Large PNGs make EHS crash. Possibly off-screen possibly just too large.

[II-629](https://inxiot.atlassian.net/browse/II-629) Terms "off.x" and "off.y" are confusing at first as it seems like you're turning them off. 

[II-635](https://inxiot.atlassian.net/browse/II-635) The warning about needing to drag components to the  workspace  can easily be triggered when  inspecting components. Maybe add "do not show again" button

[II-638](https://inxiot.atlassian.net/browse/II-638) timer/clock inconsistency, it is called 2 different things

[II-645](https://inxiot.atlassian.net/browse/II-645) missing example in the manual

[II-653](https://inxiot.atlassian.net/browse/II-653) BLOCK\_LOOKS:Simpe Counter FB is too large and  ports are spaces badly.

[II-667](https://inxiot.atlassian.net/browse/II-667) create a RNG FB.

### Sub-task

[II-617](https://inxiot.atlassian.net/browse/II-617) LVGL : Keyboard events aren't always working
