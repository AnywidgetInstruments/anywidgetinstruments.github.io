---
hide:
  - navigation
  - toc
---

# anywidget instruments { .brand-title }

<div class="brand-banner" markdown>
![anywidget instruments: instrument panels for notebooks, dashboards and the web](brand/banner-light.svg#only-light)
![anywidget instruments: instrument panels for notebooks, dashboards and the web](brand/banner-dark.svg#only-dark)
</div>

**Instrument panels for notebooks, dashboards and the web.** Knobs, gauges,
tanks, LEDs, switches, strip charts and alarm annunciators for industrial
processes; speedometers, tachometers, tell-tales and clusters for vehicles;
airspeed, attitude,
altimeter, turn, heading and vertical speed indicators for aircraft. Built on [anywidget](https://anywidget.dev), usable
from Python, Julia and Grafana.

<div class="brand-buttons" markdown>
[![Try in the browser](brand/buttons/try-light.svg#only-light)![Try in the browser](brand/buttons/try-dark.svg#only-dark)](try/)
[![Industrial documentation](brand/buttons/docs-industrial-light.svg#only-light)![Industrial documentation](brand/buttons/docs-industrial-dark.svg#only-dark)](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/)
[![Automotive documentation](brand/buttons/docs-automotive-light.svg#only-light)![Automotive documentation](brand/buttons/docs-automotive-dark.svg#only-dark)](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/)
[![Aeronautics documentation](brand/buttons/docs-aeronautics-light.svg#only-light)![Aeronautics documentation](brand/buttons/docs-aeronautics-dark.svg#only-dark)](https://anywidgetinstruments.github.io/anywidget-instruments-aeronautics/)
[![Grafana panel documentation](brand/buttons/docs-grafana-light.svg#only-light)![Grafana panel documentation](brand/buttons/docs-grafana-dark.svg#only-dark)](https://anywidgetinstruments.github.io/afm-host-panel/)
</div>

The [demos](try/) run in the browser (Python through Pyodide): nothing to install.

## One front end, many hosts

Each widget is a TypeScript front-end module driven by a set of **traits**
described by a JSON Schema contract. Everything a widget displays, unit
conversion included, is computed in the front end; a host only sets traits.
The same widget therefore behaves alike in JupyterLab, Jupyter Notebook,
marimo, VS Code, Colab, Pluto, standalone HTML pages and Grafana dashboards.

## Instrument families

![](brand/icons/docs.svg){ width="14" } documentation &nbsp;
![](brand/icons/try.svg){ width="14" } live demos &nbsp;
![](brand/icons/code.svg){ width="14" } source code

| Family | Links | Conventions | Status |
|---|---|---|---|
| **Core**<br><code>anywidget-instruments</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/anywidget-instruments) | | base view and Python class, trait contract, themes, liveness; every library depends on it |
| **Industrial**<br><code>anywidget-instruments-industrial</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/) [![Live demos](brand/icons/try.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/try/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/anywidget-instruments-industrial) | ISA-101, IEC 60073, ISA-18.2 | pre-alpha, 52 widgets |
| **Automotive**<br><code>anywidget-instruments-automotive</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/) [![Live demos](brand/icons/try.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-automotive/try/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/anywidget-instruments-automotive) | UN R121, ISO 2575, ISO 15008 | early implementation |
| **Aeronautics**<br><code>anywidget-instruments-aeronautics</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-aeronautics/) [![Live demos](brand/icons/try.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-aeronautics/try/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/anywidget-instruments-aeronautics) | CS-23 / CS-25, AC 25-11 | early implementation: the basic six |

## Hosts

| Host | Links | |
|---|---|---|
| **Python**<br><code>anywidget-instruments-industrial</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/anywidget-instruments-industrial/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/anywidget-instruments-industrial) | Jupyter, marimo and every anywidget host |
| **Julia**<br><code>Anywidget.jl</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/Anywidget.jl/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/Anywidget.jl) | anywidget front-end modules in Julia: standalone HTML, Jupyter, Pluto, Kaimon Slate |
| **Julia**<br><code>AnywidgetInstruments.jl</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/AnywidgetInstruments.jl/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/AnywidgetInstruments.jl) | the instruments, hosted by Anywidget.jl |
| **Grafana**<br><code>afm-host-panel</code> | [![Documentation](brand/icons/docs.svg){ width="20" }](https://anywidgetinstruments.github.io/afm-host-panel/) [![Source code](brand/icons/code.svg){ width="20" }](https://github.com/AnywidgetInstruments/afm-host-panel) | a panel plugin running anywidget front-end modules, instruments built in |

## Safety

!!! danger "Not certified instruments"
    These widgets are for visualization, teaching, simulation and supervision
    dashboards. They are **not** certified instruments: they must not replace
    the safety functions of a plant, the instruments of a vehicle or those of
    an aircraft.

<small>All projects are in initial development. Contributions and feedback are
welcome in each repository. Visual identity:
[AnywidgetInstruments/.github](https://github.com/AnywidgetInstruments/.github/tree/main/brand).</small>
