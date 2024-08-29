# Energy-Profile-Analysis-of-India
This project analyzes India's energy profile from 1985 to 2019 using a dataset provided in Energy Profile of India 1985 to 2019.csv. The analysis focuses on various aspects of energy consumption and generation, including trends, modes, and environmental impacts.

Overview
The notebook contains Python code to visualize and analyze different aspects of India's energy profile. Key visualizations include total energy consumption, modes of energy consumption, CO2 emissions per unit energy, and electricity generation.

Features
Total Energy Consumption: Plot total energy consumption over the years.
Modes of Energy Consumption: Visualize energy consumption by different modes such as oil, gas, coal, solar, hydro, nuclear, and biomass.
CO2 Emissions per Unit Energy: Plot annual CO2 emissions per unit of energy generated.
Total Electricity Generation: Analyze total electricity generation over time.
Modes of Electricity Generation: Visualize electricity generation by different sources such as coal, gas, hydro, nuclear, solar, oil, wind, and other renewables.
Access to Electricity: Plot the percentage of the population with access to electricity.
Green Electricity Generation: Visualize electricity generation from green sources such as solar and wind.
Dependencies
pandas
matplotlib
numpy
Usage
Load and Preprocess Data: The dataset is loaded and column names are cleaned for consistency.
Generate Plots: The following functions are defined to generate plots:
plot_total_energy_consumption()
plot_energy_consumption_modes()
plot_co2_emission_per_unit_energy()
plot_total_electricity_generation()
plot_electricity_generation_modes()
plot_access_to_electricity()
plot_green_electricity_generation()
Execution: Call the functions to generate the plots. All functions are executed sequentially to visualize different aspects of the energy profile.
