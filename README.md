# Seebeck Coefficient Calculator

This application, titled "calculate_seebeck," is a scientific utility program designed to calculate and visualize the Seebeck coefficients for various thermocouple types. The source is available as a project in LV 2023, it requires JKI State Machine. An installer for Windows 11 is available, see below.

## Description

The program is built using LabVIEW and relies on data from the **NIST monograph 175**. It allows users to explore the properties of thermocouples over a specified temperature range.

### Key Features:

* **Thermocouple Selection:** Users can select the desired thermocouple type (e.g., 'S', T, K,...).
* **Temperature Range:** The user can define a `start temp` and `end temp` in Kelvin (K) to generate the data plots.
* **Data Points:** The number of points for the calculation and plotting can be specified.
* **Graphical Display:** The application plots the Seebeck coefficients against temperature.
    * **X-Axis:** Temperature in Kelvin (K).
    * **Y-Axes:**
        * The left Y-axis shows the Seebeck coefficients of the individual positive (`S+`) and negative (`S-`) legs of the thermocouple in microvolts per Kelvin (µV/K).
        * The right Y-axis shows the total Seebeck coefficient of the thermocouple couple (`S_couple`) in µV/K.
* **Point-Specific Calculation:** Users can input a specific temperature (`Select temp`) to get precise values. For the selected temperature, the program displays:
    * The Seebeck coefficient of the positive wire (`S, +wire /uV`).
    * The Seebeck coefficient of the negative wire (`S, -wire /uV`).
    * The total resulting signal (`Signal (in uV/K)`), which is the difference between the positive and negative wire coefficients.
* **Controls:** The program includes a `save` button for data export in a Tab separated ASCII file.

The software was developed initially in May 2005. This version was compiled on June 28, 2025 and an installer can be downloaded from **Releases** page.
