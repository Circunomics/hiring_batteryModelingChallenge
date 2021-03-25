## Battery Modeling Challenge

A set of four Li-ion batteries were run through 3 different operational profiles (charge, discharge and impedance) at room temperature. [Dataset](https://circunomicsgmbh.sharepoint.com/:f:/s/Circunomics/Ei42j9N94xNLjYJKFY1c7AcBBmWx_SsQKK1Ek-ASvJ00Lw?e=tFBgOU)

Charging was carried out in a constant current (CC) mode at 1.5A until the battery voltage reached 4.2V and then continued in a constant voltage (CV) mode until the charge current dropped to 20mA. Discharge was carried out at a constant current (CC) level of 2A until the battery voltage fell to 2.7V, 2.5V, 2.2V and 2.5V for batteries 5 6 7 and 18 respectively.

Impedance measurement was carried out through an electrochemical impedance spectroscopy (EIS) frequency sweep from 0.1Hz to 5kHz.

Repeated charge and discharge cycles result in accelerated aging of the batteries while impedance measurements provide insight into the internal battery parameters that change as aging progresses.

The experiments were stopped when the batteries reached end-of-life (EOL) criteria, which was a 30% fade in rated capacity (from 2Ahr to 1.4Ahr).

## Tasks

### Visualization
- How do Re and Rct change over cycling under the different conditions? Are they correlated?
- Use bokeh to create an interactive visualization for searching through the large amounts of data or enable the comparison between cells.

### Tool building
- Write a function to integrate the current during charge/discharge to make a plot of state-of-health/capacity vs cycle number

### Machine learning
- Use the cycling/impedance data to predict the capacity of the cells.
- Predict the end of life for the cells

## How to submit the Challenge

- The time allowed for completing this coding assignment is 7 days.
- We understand you are working, and you have to interact, discuss etc.. so please let us know how long it took you.

- Only the final Jupyter notebook has to be submitted, and no formal project report is required.

- Comments or clarifications can be provided in the notebook.

- Please push you Jupyter notebook to a bitbucket private repository and grant access to the user jobs@circunomics.com.

## Thinks to keep in mind:

Please understand that this challenge is not decisive if you are applying to work at Circunomics.

This is just an opportunity for you both to work together and get to know each other in a more technical way.

The point is to understand how you both working as a team combine your battery knowledge and data science approach to complete the tasks.

Have fun!
