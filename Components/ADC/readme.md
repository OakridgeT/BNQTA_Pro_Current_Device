# ADS131M08 Manual — README / AI Entry Point

## 1. Document Identity

**Device:** ADS131M08
**Device Type:** 8-Channel, Simultaneously-Sampling, 24-Bit, Delta-Sigma Analog-to-Digital Converter (ADC)

**Document Type:** Manufacturer Datasheet / Technical Reference Manual
**Primary Purpose:** Authoritative technical reference for the ADS131M08 device.

This directory contains the complete manufacturer documentation for the ADS131M08.

The main manual is maintained as an **immutable reference document**. Project-specific interpretations, implementation decisions, and design adaptations must not be written into the manufacturer manual.

---

## 2. Purpose of This Document

This README is the **entry point** for AI systems and engineers working with the ADS131M08 documentation.

Its purpose is to:

1. Identify the device and its documentation.
2. Explain the structure of the manual.
3. Guide navigation to relevant sections.
4. Distinguish manufacturer-provided information from project-specific decisions.
5. Provide a stable reference point for future AI-assisted hardware development.

This README does **not** replace the manufacturer manual.

The complete `.md` manual remains the authoritative source for device specifications and behavior.

---

## 3. Source of Truth

The complete ADS131M08 manual is the primary technical source.

When answering questions about:

* Electrical specifications
* Absolute maximum ratings
* ADC performance
* Timing
* SPI communication
* Registers
* Device operating modes
* Power requirements
* Pin behavior
* Application recommendations
* PCB layout
* Packaging

the AI should consult the **complete manufacturer manual** rather than relying solely on this README.

If information in this README conflicts with the manufacturer manual, **the manufacturer manual takes precedence**.

---

## 4. Document Structure

The complete manual is organized into the following major sections:

| Section | Topic                                            | Primary Use                                               |
| ------- | ------------------------------------------------ | --------------------------------------------------------- |
| 1       | Features                                         | Device capabilities and key specifications                |
| 2       | Applications                                     | Intended application areas                                |
| 3       | Description                                      | General device description                                |
| 4       | Revision History                                 | Documentation revisions                                   |
| 5       | Pin Configuration and Functions                  | Pin identification and electrical functions               |
| 6       | Specifications                                   | Electrical, timing, thermal, and operating specifications |
| 7       | Parameter Measurement Information                | Measurement methodology and noise measurements            |
| 8       | Detailed Description                             | Internal operation, programming, modes, and registers     |
| 9       | Application and Implementation                   | Application information and typical implementation        |
| 10      | Power Supply Recommendations                     | Power behavior, sequencing, and decoupling                |
| 11      | Layout                                           | PCB layout recommendations                                |
| 12      | Device and Documentation Support                 | Supporting documentation and resources                    |
| 13      | Mechanical, Packaging, and Orderable Information | Package and ordering information                          |

---

# 5. Navigation Guide

## 5.1 Device Overview

For a general understanding of the ADS131M08, consult:

* **Section 1 — Features**
* **Section 2 — Applications**
* **Section 3 — Description**
* **Section 8.1 — Overview**
* **Section 8.2 — Functional Block Diagram**
* **Section 8.3 — Feature Description**

These sections establish the fundamental capabilities and architecture of the device.

---

## 5.2 Pinout and Electrical Connections

For hardware design involving the physical device, consult:

### Section 5 — Pin Configuration and Functions

This section should be used to determine:

* Pin names
* Pin functions
* Electrical roles
* Device connections
* Required and optional connections

For actual PCB implementation, this section should be considered together with:

* Section 6 — Specifications
* Section 10 — Power Supply Recommendations
* Section 11 — Layout

---

## 5.3 Electrical Specifications

For quantitative electrical requirements and performance parameters, consult:

### Section 6 — Specifications

This section contains:

```text
6.1 Absolute Maximum Ratings
6.2 ESD Ratings
6.3 Recommended Operating Conditions
6.4 Thermal Information
6.5 Electrical Characteristics
6.6 Timing Requirements
6.7 Switching Characteristics
6.8 Timing Diagrams
6.9 Typical Characteristics
```

### Important distinction

The following subsections have different purposes:

* **Absolute Maximum Ratings** define limits that must not be exceeded.
* **Recommended Operating Conditions** define the conditions under which the device is intended to operate.
* **Electrical Characteristics** define specified electrical performance.
* **Timing Requirements** define required timing relationships.
* **Switching Characteristics** define device timing behavior.
* **Typical Characteristics** provide representative behavior and should not automatically be interpreted as guaranteed specifications.

---

# 6. ADC Performance and Measurement

For questions involving ADC performance, measurement accuracy, noise, and characterization, consult:

### Section 6 — Specifications

Especially:

* 6.5 Electrical Characteristics
* 6.9 Typical Characteristics

and:

### Section 7 — Parameter Measurement Information

Especially:

* 7.1 Noise Measurements

These sections should be consulted when evaluating:

* ADC noise
* Resolution
* Conversion performance
* Measurement conditions
* Noise characterization
* Signal quality
* Typical versus guaranteed performance

---

# 7. Device Architecture and Operation

For understanding how the ADS131M08 operates internally, consult:

### Section 8 — Detailed Description

This is one of the most important sections of the manual.

It contains:

```text
8.1 Overview
8.2 Functional Block Diagram
8.3 Feature Description
8.4 Device Functional Modes
8.5 Programming
8.6 Registers
```

Use this section for questions involving:

* ADC architecture
* Channel operation
* Simultaneous sampling
* Functional modes
* Device configuration
* Programming
* Internal behavior
* Register configuration

---

# 8. Register-Level Configuration

For firmware implementation and device configuration, prioritize:

### Section 8.5 — Programming

and:

### Section 8.6 — Registers

These sections should be treated as the primary reference for:

* Register addresses
* Register fields
* Configuration bits
* Device initialization
* Operating modes
* ADC configuration
* Data acquisition configuration
* Status configuration
* Programmable parameters

When implementing firmware, register definitions should be verified against the complete manufacturer documentation.

Do not infer register behavior solely from register names.

---

# 9. Application Implementation

For practical circuit implementation, consult:

### Section 9 — Application and Implementation

including:

```text
9.1 Application Information
9.2 Typical Application
```

This section provides manufacturer guidance for applying the device in real circuits.

It should be considered together with:

* Section 5 — Pin Configuration and Functions
* Section 6 — Specifications
* Section 10 — Power Supply Recommendations
* Section 11 — Layout

---

# 10. Power Supply Design

For power-related design decisions, consult:

### Section 10 — Power Supply Recommendations

including:

```text
10.1 CAP Pin Behavior
10.2 Power-Supply Sequencing
10.3 Power-Supply Decoupling
```

This section is particularly relevant when designing:

* Analog power rails
* Digital power rails
* Decoupling networks
* Power sequencing
* CAP-related circuitry
* Low-noise ADC power systems

Power recommendations should not be substituted with generic ADC design practices without verifying compatibility with the ADS131M08 documentation.

---

# 11. PCB Layout

For PCB implementation, consult:

### Section 11 — Layout

including:

```text
11.1 Layout Guidelines
11.2 Layout Example
```

This section should be considered when determining:

* Component placement
* Grounding
* Signal routing
* Power routing
* Decoupling placement
* Analog/digital separation
* PCB layout constraints

For precision ADC applications, layout recommendations can directly affect measured performance. Therefore, manufacturer layout guidance should be treated as a primary design reference.

---

# 12. Mechanical and Packaging Information

For physical package information, consult:

### Section 13 — Mechanical, Packaging, and Orderable Information

This section is relevant for:

* Package dimensions
* Mechanical constraints
* PCB footprint development
* Package identification
* Ordering information

The package information should be verified against the exact device/package variant being used in the project.

---

# 13. Documentation Support

For supporting manufacturer resources, consult:

### Section 12 — Device and Documentation Support

including:

```text
12.1 Documentation Support
12.2 Receiving Notification of Documentation Updates
12.3 Support Resources
12.4 Trademarks
12.5 Electrostatic Discharge Caution
12.6 Glossary
```

This section may be useful when additional manufacturer documentation or terminology clarification is required.

---

# 14. Recommended AI Navigation Strategy

When answering a question about the ADS131M08, the AI should first classify the question according to its technical domain.

### Hardware / Pinout

Start with:

```text
Section 5
Section 6
Section 10
Section 11
```

### Electrical Characteristics

Start with:

```text
Section 6
Section 7
```

### ADC Operation

Start with:

```text
Section 8.1
Section 8.2
Section 8.3
Section 8.4
```

### Firmware / Configuration

Start with:

```text
Section 8.5
Section 8.6
```

### SPI / Digital Communication

Consult the relevant portions of:

```text
Section 6
Section 8
```

with particular attention to timing requirements, switching characteristics, programming, and registers.

### Power Supply

Start with:

```text
Section 6.3
Section 6.5
Section 10
```

### PCB Design

Start with:

```text
Section 5
Section 10
Section 11
```

### Noise / Measurement Quality

Start with:

```text
Section 6.5
Section 6.9
Section 7.1
```

### Package / Footprint

Start with:

```text
Section 5
Section 13
```

---

# 15. Manufacturer Data vs. BNQTA Design Decisions

This manual describes the **ADS131M08 as specified by its manufacturer**.

It does not define the BNQTA hardware architecture.

Therefore, the following types of information should be maintained separately from this manual:

* BNQTA-specific component selection
* BNQTA schematic decisions
* ESP32-S3 pin assignments
* ADC interface implementation
* Power architecture selected for BNQTA
* Sensor interface
* Signal conditioning designed for BNQTA
* PCB implementation decisions
* Firmware architecture
* Sampling strategy selected for BNQTA
* Project-specific tolerances
* Project-specific validation results

These decisions should be documented in BNQTA project documentation and referenced against this manufacturer manual where appropriate.

---

# 16. Relationship to BNQTA Documentation

The ADS131M08 manual is a **source document**.

BNQTA project documentation should reference this manual rather than modifying it.

Conceptually:

```text
Manufacturer Documentation
        │
        ▼
   ADS131M08.md
   (Immutable Source)
        │
        ├───────────────┐
        ▼               ▼
 Hardware Design    Firmware Design
        │               │
        ▼               ▼
 BNQTA-specific     BNQTA-specific
 decisions          configuration
```

The manufacturer document should remain unchanged even when the BNQTA implementation evolves.

---

# 17. Document Integrity

The complete ADS131M08 manual should be treated as an **immutable technical reference**.

Do not add:

* Project notes
* Personal interpretations
* BNQTA decisions
* Corrections based on assumptions
* Firmware-specific instructions
* Hardware-specific modifications

directly into the manufacturer manual.

If additional interpretation is required, create a separate BNQTA document.

---

# 18. Important Interpretation Rule

When using information from this manual, distinguish between:

1. **Guaranteed specifications**
2. **Recommended operating conditions**
3. **Absolute limits**
4. **Typical characteristics**
5. **Application recommendations**
6. **Design examples**

These categories must not be treated as interchangeable.

In particular, typical performance data should not automatically be interpreted as guaranteed device specifications.

---

# 19. Manual Table of Contents

The complete source manual contains the following structure:

```text
1  Features

2  Applications

3  Description

4  Revision History

5  Pin Configuration and Functions

6  Specifications
   6.1 Absolute Maximum Ratings
   6.2 ESD Ratings
   6.3 Recommended Operating Conditions
   6.4 Thermal Information
   6.5 Electrical Characteristics
   6.6 Timing Requirements
   6.7 Switching Characteristics
   6.8 Timing Diagrams
   6.9 Typical Characteristics

7  Parameter Measurement Information
   7.1 Noise Measurements

8  Detailed Description
   8.1 Overview
   8.2 Functional Block Diagram
   8.3 Feature Description
   8.4 Device Functional Modes
   8.5 Programming
   8.6 Registers

9  Application and Implementation
   9.1 Application Information
   9.2 Typical Application

10 Power Supply Recommendations
   10.1 CAP Pin Behavior
   10.2 Power-Supply Sequencing
   10.3 Power-Supply Decoupling

11 Layout
   11.1 Layout Guidelines
   11.2 Layout Example

12 Device and Documentation Support
   12.1 Documentation Support
   12.2 Receiving Notification of Documentation Updates
   12.3 Support Resources
   12.4 Trademarks
   12.5 Electrostatic Discharge Caution
   12.6 Glossary

13 Mechanical, Packaging, and Orderable Information
```

---

# 20. AI Entry Rule

When an AI system enters this documentation directory, it should:

1. Read this README first.
2. Identify the user's technical question.
3. Determine which section(s) of the complete ADS131M08 manual are relevant.
4. Consult the complete manufacturer manual.
5. Base device-specific technical claims on the manufacturer documentation.
6. Clearly distinguish manufacturer specifications from BNQTA-specific implementation decisions.
7. Avoid modifying the immutable manufacturer manual.

This README is therefore a **navigation and interpretation layer**, not a replacement for the ADS131M08 manual.

