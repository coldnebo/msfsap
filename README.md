This is an investigation into the issue described here:

* https://community.justflight.com/topic/5743/autopilot-after-sim-update-14/36?lang=en-US

Because I don't like copy pasting from web, I'm putting the actual change into source control so we can comment and see on what is changing.

as described:

...\Official\OneStore\workingtitle-instruments-garmin-gns\html_ui\Pages\VCockpit\Instruments\NavSystems\GPS\WT530\WT530B.js (and WT430B.js)


## setup

based on my MS store install: D:\games\msfs\Official

```
cd github\msfsap

cp D:\games\msfs\Official\OneStore\workingtitle-instruments-garmin-gns\html_ui\Pages\VCockpit\Instruments\NavSystems\GPS\WT530\WT530B.js .

cp D:\games\msfs\Official\OneStore\workingtitle-instruments-garmin-gns\html_ui\Pages\VCockpit\Instruments\NavSystems\GPS\WT430\WT430B.js .

```