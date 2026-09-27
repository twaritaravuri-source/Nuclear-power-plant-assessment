# Nuclear Power Plant Assessment

A simplified process-engineering assessment of a hypothetical 1 GW nuclear power plant, developed using an Excel-based energy model.

## Project Overview

This project investigates the conversion of nuclear heat into electrical power through a simplified steam-cycle process. The assessment focuses on the relationship between electrical output, thermal efficiency, waste-heat rejection and annual electricity generation.

The model uses a hypothetical electrical output of **1,000 MW**, a base-case thermal efficiency of **33%** and a capacity factor of **91%**.

## Key Analysis

The Excel model was used to:

* Calculate the thermal power required to produce the target electrical output
* Estimate the resulting waste-heat load
* Calculate annual electricity generation using the assumed capacity factor
* Investigate the effect of thermal efficiency and capacity factor through sensitivity analysis
* Compare indicative lifecycle greenhouse-gas emissions for nuclear and natural gas generation
* Consider chemical engineering aspects of nuclear power generation

### Base-Case Results

| Parameter                     |         Result |
| ----------------------------- | -------------: |
| Electrical output             |       1,000 MW |
| Thermal efficiency            |            33% |
| Required thermal power        |      ~3,030 MW |
| Estimated waste heat          |      ~2,030 MW |
| Capacity factor               |            91% |
| Annual electricity generation | ~7.97 TWh/year |

The model also estimated approximately **95,659 tonnes CO₂e/year** for nuclear generation compared with **3.19 million tonnes CO₂e/year** for equivalent natural gas generation, using assumed lifecycle emissions intensities.

## Sensitivity Analysis

The model investigated how changes in:

* **Thermal efficiency** affect required thermal input and waste-heat rejection
* **Capacity factor** affects annual electricity generation

Increasing thermal efficiency reduced both the required thermal power and estimated waste-heat load, while increasing capacity factor increased annual electricity generation.

## Chemical Engineering Considerations

The assessment considered several areas relevant to chemical and process engineering, including:

* Thermodynamics
* Heat transfer
* Fluid flow
* Process control
* Process safety
* Nuclear waste management
* Plant design and system integration

The project also considered the importance of cooling systems, high-temperature and high-pressure equipment, process monitoring and the management of radioactive materials.

## Limitations

The model is intended as a **first-level process-engineering assessment**, rather than a detailed nuclear power plant design. It does not include detailed reactor physics, individual equipment sizing, heat-exchanger design, hydraulic calculations, nuclear safety analysis or radioactive-waste facility design.

The emissions comparison is also indicative and is based on assumed lifecycle emissions intensities rather than a full lifecycle assessment.

## Project Files

* **Nuclear Power Plant Assessment.pdf** — Full project report
* **Nuclear Power Plant Assessment.xlsx** — Excel calculation model, results and sensitivity analysis

