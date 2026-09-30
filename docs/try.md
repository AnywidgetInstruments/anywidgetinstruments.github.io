---
hide:
  - navigation
---

# Try in the browser

The demos run in your browser: Python runs through Pyodide, so there is
nothing to install. The first load downloads the Python runtime and takes a
few seconds. They are [marimo](https://marimo.io) reactive apps; the
industrial ones are also notebooks in [JupyterLite](https://jupyterlite.readthedocs.io).

!!! note
    The demos simulate processes, machines and vehicles. They are for
    visualization, teaching and simulation, never to control real equipment
    or to be used while driving.

## Industrial

Knobs, gauges, tanks, LEDs, switches, strip charts, alarms and supervisory
objects, from [anywidget-instruments-industrial](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/).

| Demo | What it shows |
|---|---|
| [**Batch reactor R-101**](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/marimo/batch_reactor/) | A complete operator station: PackML state machine, recipe, PID faceplate, alarms, trend, event log |
| [**Gallery**](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/marimo/gallery/) | Every widget family: knobs and indicators, Boolean controls, charts, alarms, styles |
| [**PID tuning**](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/marimo/pid_tuning/) | Closed-loop step response; overshoot and settling time follow the Kp, Ti, Td knobs |
| [**Operator station**](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/marimo/operator_station/) | A filling line with stack light, PID faceplate, annunciator and alarm list |
| [**Virtual instrument bench**](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/marimo/virtual_instrument/) | Function generator, oscilloscope and multimeter front panels |

[All the industrial demos, also in JupyterLite](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/try/){ .md-button }

## Automotive

Speedometers, tachometers, tell-tales, trip computers and clusters, from
[anywidget-instruments-automotive](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/).

| Demo | What it shows |
|---|---|
| [**Instrument cluster**](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/marimo/cluster_preview/) | A cluster with a combustion, hybrid or electric drivetrain |
| [**Electric and hybrid**](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/marimo/electric/) | Power meters, battery gauges, power flows and the electric tell-tales |
| [**Dials**](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/marimo/dials/) | Speedometers, tachometers, fuel and temperature gauges in every unit system |
| [**Digital displays**](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/marimo/digital/) | Trip computers, odometer and gear indicators |
| [**Tell-tales**](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/marimo/telltales/) | Every tell-tale, by colour and meaning |

[All the automotive demos](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/try/){ .md-button }

## Aeronautics

Airspeed, attitude, altimeter, turn coordinator, heading and vertical speed, from
[anywidget-instruments-aeronautics](https://anywidgetinstruments.github.io/anywidget-instruments-aeronautics/). Not certified
avionics, never to fly an aircraft.

| Demo | What it shows |
|---|---|
| [**Flight instruments**](https://anywidgetinstruments.github.io/anywidget-instruments-aeronautics/marimo/flight/) | The basic six in the basic T, driven by sliders; the turn coordinator follows the rate of turn the bank gives at the airspeed |
