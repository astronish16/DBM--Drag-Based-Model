# DBM-Drag Based Model
[![DOI](https://zenodo.org/badge/351071066.svg)](https://zenodo.org/badge/latestdoi/351071066)
\
This repository provides the python based program for Coronal Mass Ejection(CME) arrival forecast at 1 AU using Drag Based Model(DBM) [Vrˇsnak et al. (2013)](https://link.springer.com/article/10.1007/s11207-012-0035-4).\
\
`DBM_Forecast.ipynb` file provides a program for the ICME arrival forecast at 1 AU using DBM. `ADBM_SelfSimilar_Cone.ipynb` consider self-similar expansion during CME propagation in heliosphere and provides CME arrival time. In `ADBM_Flattening_Cone.ipynb` flattening cone evolution is assumed during CME propagation. ALL the files here provides **V-R plot**,**V-R-t plot** for CME propagation along with **CME arrival date and time** and **Impact speedd at 1AU** as output. In case of ADBM **CME geometry** is also provided in output.  

The folder `Model_code` consist of python notebooks for geometrical relation and different kinetmatic approach considered for CME propagation. File `Geometrical Parameters.ipynb` provides a insight of cone geometry for advance DBM. `Advance DBM.ipynb` provides a forecast of CME arrival at 1 AU with the cone geometry visuals. `kinematics-1.ipynb` and `kinematics-2.ipynb` file provides two different kinetic approach for CME propagation (Those two kinetic approach are self-similar cone expansion and flatteing cone expansion) \
\
A more detailed description of Drag Based Model, this python implementation and its validation is given in [my M.Sc. thesis](https://www.overleaf.com/read/tprsqfwsmgkh).
