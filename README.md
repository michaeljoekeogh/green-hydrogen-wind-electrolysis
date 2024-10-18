# green-hydrogen-wind-electrolysis
This repository contains a comprehensive collection of MATLAB Simulink models developed for simulating green hydrogen production through wind-electrolysis. The repository is structured to reflect the various stages of the project, from initial design iterations to final optimized simulations. The files are organized into different sections, focusing on specific aspects of the wind-electrolysis system and its components.

Repository Structure:
Wind Energy Generation: This section contains models that simulate wind speed, wind turbine behavior, and energy capture. The files provide insights into the wind energy generation process, which serves as the primary energy input to the system.

Generator Control: Here, you will find models focused on controlling the generator, including field-oriented control (FOC) and other strategies to ensure stable energy output. These models are critical for ensuring the energy supplied to the electrolyzer is regulated and matches the system's demands.

Electrolyzer Revisions: This section contains multiple iterations of the PEM electrolyzer model, capturing its chemical and electrical characteristics. Each file progressively builds towards an accurate simulation of the electrolyzer's real-world performance, accounting for over-potentials, component aging, and energy losses.

Final System Simulations: The final section merges all individual models (wind energy generation, generator control, and the optimized electrolyzer) into a fully integrated wind-electrolysis system. These models simulate the full process, from renewable energy generation to hydrogen production, and include detailed analysis of system performance and efficiency under different load conditions

NB: rev1_wind taken from: Dr. Siva Malla (2024). PMSG based Wind Power Generation System (https://www.mathworks.com/matlabcentral/fileexchange/36116-pmsg-based-wind-power-generation-system), MATLAB Central File Exchange. Retrieved October 18, 2024.
