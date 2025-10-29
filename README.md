# Data analysis in DAOs
This repository hosts the data and analysis code used to examine governance mechanisms across various DAOs. The analyses quantify key aspects of proposal and voting dynamics, while also delving into specific issues such as the unequal distribution of Voting Power (VP), which is assessed using metrics like the Gini coefficient.

## Repository layout
```text
├─ notebooks/
│  ├─ Snapshot Spaces Data Retrieval.ipynb 
│  ├─ DAOs At A Scale.ipynb 
│  ├─ IndieDAO.ipynb
│  └─ Decentraland.ipynb
└─ README.md
```

## Notebook overview
Although there are specific explanations in text cell comments in the notebooks, the project consists of the following three main analyses.
- [Snapshot Spaces Data Retrieval.ipynb]: Code developed to retrieve voting data from any [Snapshot space](https://snapshot.org/#/explore).
- [DAOsAtAScale.ipynb]: Code developed to perform a quantitative analysis of the whole ecosystem of DAOs.
- [IndieDAO.ipynb]: Code developed to retrieve and analyze Snapshot proposals of [IndieDAO](https://www.indie.win/).
- [Decentraland.ipynb]: Code developed to retrieve and analyze Snapshot proposals of [Decentraland](https://decentraland.org/).

  !!! The code developed to retrieve the data from all the DAO ecosystem can be found here: [DAOs Ecosystem Census](https://github.com/Grasia/dao-ecosystem-census).

## How to run the notebooks
We recommend using [JupyterLab](https://jupyter.org/) (local utility) or [GoogleColab](https://colab.google/) (cloud utility) to open and run the notebooks. Please note that if you are working in the cloud, you will need to host and connect the data files to the code via Google Drive. This can be problematic when working with large data files, such as those used in the whole ecosystem of DAOs analysis, because they need to be uploaded each time the session is restarted.

## Publications
Several publications related to this work have been developed, as indicated below:
- Andrea Peña-Calvin, Javier Arroyo, Andrew Schwartz, and Samer Hassan. "Concentration of Power and Participation in Online Governance: the Ecosystem of Decentralized Autonomous Organizations." In Companion Proceedings of the ACM Web Conference 2024 (WWW '24). Association for Computing Machinery, New York, NY, USA, 927–930. https://doi.org/10.1145/3589335.3651481
- Andrea Peña-Calvin, Jorge Saldivar, Javier Arroyo and Samer Hassan. "A Categorization of Decentralized Autonomous Organizations: The Case of the Aragon Platform." IEEE Transactions on Computational Social Systems, vol. 11, no. 6, pp. 8143-8155, Dec. 2024, doi: 10.1109/TCSS.2023.3299254.
- Andrea Peña-Calvin, David Duenas-Cid, and Junaid Ahmed. "Is DAO governance fostering democracy? Reviewing decision-making in decentraland." Proceedings of the 58th Hawaii International Conference on System Sciences. HICSS Conference Office. 2025.

## Acknowledgements
This work is funded by:
- The Universidad Complutense de Madrid - Banco Santander Grant No. CT58/21-CT59/21
- The project DAOapplications (Spanish Ministry of Science and Innovation, grant no.: PID2021-127956OB-I00)
- The Project P2P Models (https://p2pmodels.eu) through the European Research Council ERC-2017-STG under Grant 759207
- The Polish National Research Center (Grant OPUS-20 - 2020/39/B/HS5/01661) and EU H2020 MSCA Program (Grant agreement no. 101038055)

