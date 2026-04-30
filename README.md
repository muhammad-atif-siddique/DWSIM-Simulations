# Flash Separation of Methanol and Water

## Project Overview
This repository contains a DWSIM process simulation modeling the Vapor-Liquid Equilibrium (VLE) and physical separation of a binary Methanol-Water mixture. This serves as a foundational thermodynamic model for downstream purification in sustainable syngas-to-methanol production facilities.

## Technical Specifications
* **Process Name / Unit Operation:** Gas-Liquid Flash Separation with Pre-Heating
* **Objective:** To evaluate the single-stage phase split and component distribution of a 50/50 mass-fraction binary mixture under thermal stress.
* **Thermodynamic Package Used:** NRTL (Non-Random Two-Liquid). Selected specifically to account for the highly non-ideal, polar hydrogen-bonding interactions between methanol and water.
* **Key Components / Feedstock:** Methanol, Water
* **Operating Conditions:** 
  * Feed: 25°C at 1 atm, 1000 kg/h
  * Flash Temperature: 85°C (Isobaric heating)

## Main Results & Commercial Findings
* The simulation successfully demonstrates the enrichment of Methanol in the vapor phase due to its higher volatility.
* **Key Finding:** A single-stage equilibrium flash at 85°C is insufficient for generating commercial AA-grade methanol, validating the engineering requirement for multi-stage fractional distillation in subsequent plant scaling. 
* Energy duty for the pre-heater is calculated and conserved across the mass-energy balance.

## How to Use
1. Download the `Methanol_Water_Flash.dwxmzp` file.
2. Open using DWSIM Open-Source Process Simulator (v8.0 or higher).
3. Press F5 to resolve the flowsheet and view the master property table.
