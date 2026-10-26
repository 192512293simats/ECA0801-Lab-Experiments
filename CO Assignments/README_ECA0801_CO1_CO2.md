# ECA0801 -- Analog and Digital Communication

## CO1 and CO2 Engineering Case Study Assignments

This repository contains the completed **CO1 and CO2 assignment
reports** for the course **ECA0801 -- Analog and Digital
Communication**, submitted as part of the **B.E. Electronics and
Communication Engineering (ECE)** programme at SIMATS.

The reports present engineering analysis, calculations, system
architectures, comparison tables, diagrams, design decisions, and
technical references relevant to analog communication systems.

------------------------------------------------------------------------

## Student Details

-   **Name:** Lokesh A
-   **Register Number:** 192512293
-   **Programme:** B.E. Electronics and Communication Engineering (ECE)
-   **Institution:** SIMATS Engineering
-   **Course Code:** ECA0801
-   **Course:** Analog and Digital Communication

------------------------------------------------------------------------

## Assignment Reports

### 1. CO1 -- AM-Based Communication Link Design

**Report title:** *AM-Based Communication Link Design: From Modulation
Selection to Receiver Deployment*

The CO1 report studies a conventional amplitude-modulation (AM) voice
communication link and evaluates its transmitter, channel allocation,
receiver design, and deployment considerations.

**Main topics covered:** - Communication-system requirements and block
diagram - Need for modulation and transmission-bandwidth calculations -
Comparison of conventional AM, DSB-SC, SSB-SC, and VSB-SC - AM
modulation index, carrier power, sideband power, and total transmitted
power - Illustrative RF channel allocation and guard-band discussion -
AM transmitter architecture - TRF versus superheterodyne receiver
comparison - Intermediate-frequency and image-frequency calculations -
AWGN effects, receiver performance, and design verification - Final
engineering decision and specification-verification table - Relevant
IEEE standards and ITU-R references

**Key illustrative design values used in the report:** - Message
bandwidth: 0--4 kHz - Candidate carrier frequency: 1 MHz - Nominal
channel spacing: 20 kHz - AM modulation index: 0.7 - Carrier power used
for theoretical calculations: 10 W - Calculated single-tone AM total
power: 12.45 W - Theoretical AM bandwidth: 8 kHz - Illustrative receiver
IF: 455 kHz

> The channel frequencies and power values are engineering-study
> assumptions. They do not constitute authorization to transmit; real
> operation must comply with applicable spectrum, licensing, equipment,
> and power regulations.

### 2. CO2 -- FM Broadcast System

**Report title:** *FM Broadcast System: From Angle-Modulation Selection
to Noise-Performance Deployment*

The CO2 report evaluates an FM broadcast-system design, compares
frequency modulation (FM) with phase modulation (PM), analyzes FM
bandwidth and sidebands, and considers receiver noise performance and
pre-emphasis/de-emphasis.

**Main topics covered:** - Case-study requirements, assumptions, and
communication-system block diagrams - FM versus PM equations and
modulation-index calculation - Wideband-FM classification -
Bessel-function sideband analysis - Carson's rule and FM bandwidth
estimation - FM transmitter and superheterodyne receiver architectures -
Receiver IF, sensitivity, selectivity, stability, limiter, and
discriminator considerations - Conventional AM versus coherent DSB-SC
noise-performance comparison - FM noise, threshold behaviour, and
pre-emphasis/de-emphasis - MATLAB verification script for waveforms,
spectra, noise tests, and response comparisons - Final engineering
decision, specification verification, and technical references

**Key illustrative design values used in the report:** - Maximum message
frequency: 15 kHz - Candidate carrier frequency: 100 MHz - Initial peak
frequency deviation: 75 kHz - FM modulation index at 15 kHz: 5 -
Carson-rule bandwidth estimate: 180 kHz - Separate Bessel-line screening
span: approximately 240 kHz under the report's stated 1% amplitude
criterion

> The bandwidth values are theoretical/model-based calculations. The
> report does not claim measured MATLAB results or regulatory approval
> for the candidate carrier frequency.

------------------------------------------------------------------------

## Purpose of This Repository

This repository keeps the CO1 and CO2 engineering assignment reports
together for academic reference and submission tracking. It documents
the assumptions, theoretical calculations, communication-system
architectures, and design decisions developed for the two case studies.

## Tools and Technical Methods

-   Microsoft Word-compatible `.docx` report format
-   Communication-system block diagrams and comparison tables
-   Analytical calculations and engineering equations
-   MATLAB script included in the CO2 report for simulation and
    verification
-   Technical references from relevant standards and recommendations, as
    cited in each report

## Academic and Technical Note

These reports are prepared for educational purposes. Illustrative
frequencies, transmitter powers, bandwidth estimates, and model-based
results should not be interpreted as permission to operate a radio
transmitter. Any practical implementation must be tested appropriately
and comply with the applicable regulations and institutional laboratory
rules.

------------------------------------------------------------------------

**Course:** ECA0801 -- Analog and Digital Communication\
**Programme:** B.E. Electronics and Communication Engineering (ECE)\
**Institution:** SIMATS Engineering
