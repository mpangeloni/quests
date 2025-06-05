# QUESTS

This repository provides the source codes and outcomes presented in the paper _QUESTS: Quality in Use Evaluation of Smart environment Technologies by agent-based Simulations_.
As the apk file for ParkinsonCom is larger than 25MB, it is not possible to upload it to GitHub. It will be provided upon demand.

- the **abms** directory provides the agent-based model and simulation coded in NetLogo;
- the **abms-observer** directory provides the abms observer, supposed to launch both the abms and the software application under evaluation (in this case, **ParkinsonCom**);
- the **process-mining** directory provides the source code for the data mining technique that finds patterns between the motion sensors turning on and off (and for how long) and informing the abms;
- the **auxiliary** directory provides Python scripts that auxiliate in the data extraction from the SQLite database;
- the **interaction-log-data** directory provides the outcome from the interaction between the abms and the software application under evaluation;
- the **simulation-log-data** directory provides the outcome from the simulation executed in the abms in NetLogo;
- the **qinu-measures** directory provides the outcome of the measurements for the selected QinU characteristics.

## How to execute the methodology
- First, install the APK file of ParkinsonCom in an Android emulator and set it up as described (register the primary contact and set up the medicine alarm);
- To initiate the process, launch the **abms-observer**;
- This will then launch both the **abms** and the **ParkinsonCom**;
- Follow the coded sequence;
- **ATTENTION:** for the recreation of the study, you need to adapt the script to open your emulator of choice (our experiment executed it in Nox) and the coordinates of your computer screen as provided by the AutoIt software.
