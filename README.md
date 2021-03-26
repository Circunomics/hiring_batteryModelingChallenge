# Battery Modeling Challenge

## Goals of the Challenge

- This challenge is not decisive for your application at Circunomics. This is just an opportunity for you both to work together and get to know each other in a technical way.

- We have already put you in contact, you have the email of your challenge partner. You are free to decide how you are going to work and collaborate.

- Remember, you have to work as team wrestling with a real life problem.

- You are a multidisciplinary team, so try to support each other in your weakness. 

- The point is to understand how you combine your battery knowledge and data science approach to complete and solve this challenge.
 
- We understand you are full time employed and this challenge is time demanding, in addition, you have to interact with your partner, talk over, discuss things etc.. so please, take your time but considere that the challenge should be finished within 7 days. 
  
- If you have any issue or question during the challenge, please contact us.

Have fun!

## Dataset

A set of four Li-ion batteries were run through 3 different operational profiles (charge, discharge and impedance) at room temperature. [Dataset](https://circunomicsgmbh.sharepoint.com/:f:/s/Circunomics/Ei42j9N94xNLjYJKFY1c7AcBBmWx_SsQKK1Ek-ASvJ00Lw?e=tFBgOU)

Charging was carried out in a constant current (CC) mode at 1.5A until the battery voltage reached 4.2V and then continued in a constant voltage (CV) mode until the charge current dropped to 20mA. 

Discharge was carried out at a constant current (CC) level of 2A until the battery voltage fell to 2.7V, 2.5V, 2.2V and 2.5V for batteries 5 6 7 and 18 respectively.

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

- Only the final Jupyter notebook has to be submitted, and no formal project report is required.

- Comments or clarifications can be provided in the notebook.

- Please push your Jupyter notebook to a bitbucket private repository and grant access to the user jobs@circunomics.com.

- We don't care from which account the notebook was pushed to the repo.
