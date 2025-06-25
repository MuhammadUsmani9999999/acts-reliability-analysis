# acts-reliability-analysis
Reliability analysis of an Aircraft Cannon Targeting System (ACTS). Calculates system reliability for series, parallel (active redundancy), &amp; standby (passive redundancy) servo configurations. Includes MTBF considerations &amp; basic Fault Tree Analysis..
# Reliability Analysis of Aircraft Cannon Targeting System (ACTS)

## Project Overview
This repository contains an academic analysis focusing on the reliability of a conceptual Aircraft Cannon Targeting System (ACTS). The project explores different system configurations and the impact of component reliability and redundancy on overall system performance. This was undertaken as part of my Aerospace Engineering studies at the University of Hertfordshire.

## Key Analyses Performed:
*   **Component Reliability:** Calculation of individual component reliability (R(t) = e^-λt) at 10 hours and 400 hours based on given failure rates (failures per million hours).
*   **System Reliability for Different Configurations:**
    *   **Mod 1 (Baseline Series System):** Calculation of overall system reliability.
    *   **Mod 2 (Parallel Servo - Active Redundancy):** Analysis of the reliability improvement due to dual parallel servo controllers.
    *   **Mod 3 (Standby Servo - Passive Redundancy):** Analysis of reliability with a standby servo controller.
*   **Impact of Improved Component MTBF:** Assessment of how an 80% improvement in servo controller MTBF affects the baseline series system reliability.
*   **Discussion on MTBF for Parallel Systems:** Explanation of why a single MTBF value is not appropriate for systems with active parallel redundancy.
*   **Fault Tree Analysis (FTA):** Basic FTA for the Mod 2 parallel servo configuration.
*   **Trade-off Discussion:** Advantages and drawbacks of eliminating redundancy vs. enhancing component reliability in the context of a combat aircraft system.

## Key Concepts & Skills Demonstrated:
*   Reliability Theory (Exponential Failure Distribution)
*   Series, Parallel (Active), and Standby (Passive) Redundancy Calculations
*   Mean Time Between Failures (MTBF) and Failure Rate (λ) Relationship
*   Fault Tree Analysis (FTA) - Basic Application
*   Analytical Problem Solving
*   Technical Reporting

## Repository Contents:
*   `[Report_Name_Reliability_ACTS].pdf`: The full analysis report detailing calculations, discussions, and conclusions.
*   *(Optional: If you have spreadsheets for calculations, you can add an `Calculations/` folder)*

---
This project provided insights into fundamental reliability engineering principles and their application in assessing and improving the dependability of complex aerospace/defence systems.
