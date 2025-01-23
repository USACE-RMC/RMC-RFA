# RMC-RFA

The U.S. Army Corps of Engineers (USACE) Risk Management Center (RMC) developed the Reservoir Frequency Analysis (RMC-RFA) software to facilitate hydrologic hazard assessments within the USACE Dam Safety Program. RMC-RFA produces a reservoir stage-frequency curve with uncertainty bounds by utilizing a deterministic flood routing model while treating the inflow volume, the inflow flood hydrograph shape, the seasonal occurrence of the flood event, and the antecedent reservoir stage as uncertain variables rather than fixed values. In order to quantify both the natural variability and knowledge uncertainty in reservoir stage-frequency estimates, RMC-RFA employs a two looped, nested Monte Carlo methodology. The natural variability of the reservoir stage is simulated in the inner loop defined as a realization, which comprises many thousands of simulated flood events. Knowledge uncertainty in the inflow volume frequency distribution is simulated in the outer loop, which comprises many realizations.

RMC-RFA is designed for interactive use in a multi-tasking environment. The software features a fully integrated modeling platform, including a graphical user interface, data entry capabilities, statistical analysis components, reservoir routing models, stochastic simulation, and results reporting tools.

![RFA](https://user-images.githubusercontent.com/123974306/232250351-5aabe7fb-a25e-4657-b9ba-d2baec168382.png)

## Downloads
* [Download Version 1.1.0](https://github.com/USACE-RMC/RMC-RFA/blob/41a2cd36ddce1573ba00f1bbbcde0f57d9e1d96b/RMC-RFA%20Version%201.1.0.zip)

Version 2.0 is currently under development and expected to be released in 2024. New features will include:
* The ability to import frequency curve results from RMC-BestFit
* Unregulated-to-regulated flow transforms
* Complex reservoir operations

## Documentation
* [RMC-TR-2018-03 - An Inflow Volume-Based Approach to Estimating Stage-Frequency Curves for Dams](https://github.com/USACE-RMC/RMC-RFA/files/12743562/RMC-TR-2018-03.-.SQRA.HHA.Methodology.-.Stage-Frequency.pdf)
* [ANCOLD 2018 - A Robust and Efficient Stochastic Simulation Framework for Estimating Reservoir Stage-Frequency Curves with Uncertainty Bounds](https://github.com/USACE-RMC/RMC-RFA/files/12743566/ANCOLD.2018.-.Stochastic.simulation.framework.-.HadenSmith.-.9-12-18.pdf)

## Training
* [2021 RMC-BestFit and RMC-RFA Training Videos](https://www.youtube.com/playlist?list=PLEIlpoX-ZknTLKrNq7qeVrCIxT_QtLLSF)
* [Risk Management Center Training Center](https://www.rmc.usace.army.mil/Training/)
