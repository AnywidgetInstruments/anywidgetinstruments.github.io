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
objects, from [anywidget-instruments-industrial](anywidget-instruments-industrial/).

| Demo | What it shows |
|---|---|
| [**Batch reactor R-101**](anywidget-instruments-industrial/marimo/batch_reactor/) | A complete operator station: PackML state machine, recipe, PID faceplate, alarms, trend, event log |
| [**Gallery**](anywidget-instruments-industrial/marimo/gallery/) | Every widget family: knobs and indicators, Boolean controls, charts, alarms, styles |
| [**PID tuning**](anywidget-instruments-industrial/marimo/pid_tuning/) | Closed-loop step response; overshoot and settling time follow the Kp, Ti, Td knobs |
| [**Operator station**](anywidget-instruments-industrial/marimo/operator_station/) | A filling line with stack light, PID faceplate, annunciator and alarm list |
| [**Virtual instrument bench**](anywidget-instruments-industrial/marimo/virtual_instrument/) | Function generator, oscilloscope and multimeter front panels |

[All the industrial demos, also in JupyterLite](anywidget-instruments-industrial/try/){ .md-button }

## Automotive

Speedometers, tachometers, tell-tales, trip computers and clusters, from
[anywidget-instruments-automotive](anywidget-instruments-automotive/).

| Demo | What it shows |
|---|---|
| [**Instrument cluster**](anywidget-instruments-automotive/marimo/cluster_preview/) | A cluster with a combustion, hybrid or electric drivetrain |
| [**Electric and hybrid**](anywidget-instruments-automotive/marimo/electric/) | Power meters, battery gauges, power flows and the electric tell-tales |
| [**Dials**](anywidget-instruments-automotive/marimo/dials/) | Speedometers, tachometers, fuel and temperature gauges in every unit system |
| [**Digital displays**](anywidget-instruments-automotive/marimo/digital/) | Trip computers, odometer and gear indicators |
| [**Tell-tales**](anywidget-instruments-automotive/marimo/telltales/) | Every tell-tale, by colour and meaning |

[All the automotive examples](anywidget-instruments-automotive/examples/){ .md-button }

## Aeronautics

[anywidget-instruments-aeronautics](anywidget-instruments-aeronautics/) is at
the design stage: its demos will come with its first widgets.
