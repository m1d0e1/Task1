> Authors 
- M0hamed
- Adiba
- Funbee


# Advances in Docking

## Introduction
The first step in drug discovery is to find a molecule that fits the protein responsible for the disease. This molecule should bind specifically to the protein hindering or enhancing its function and preventing the development of the disease. Molecular modeling is a common computer-based tool used to discover such molecules [1]. Docking is one of the most popular molecular modeling works by computing the binding and free energies between the protein and the ligand. Then, these energies are used to predict the most active molecules for a target protein. This review aims to describe the distinctive features of different docking programs focusing on approximations and computation methods affecting their accuracy [2]. 

## Method
All peer-reviewed articles about docking programs were included focusing mainly on the factors influencing docking accuracy. Also, a roadmap for enhancing docking accuracy is suggested in this paper, including new-generation docking programs along with new global optimization algorithms [3]. 

## Current Docking Programs
Most current docking programs use pre-calculated interaction grids to enhance ligand pose. However, these grids limit the docking accuracy [4]. AutoDock, and its faster version AutoDock Vina, use genetic algorithms to optimize the poses [5]. While ICM uses Monto Carlo simulations as an optimization method [6], DOCK uses Anchor-and-Grow, which allows the docking of flexible ligands [7]. Gold uses the same approach as AutoDisk, while Surflex-Dock utilizes the protomol method which assembles the ligand fragment b fragment [8]. Glide is featured with its speed and highly precise modes, as it uses a combination of grid-based and hierarchical filters [9].

## New trends
The new trends in the docking programs are trying to move from the pre-calculated grids and utilizing more precise molecular energy calculations, including quantum chemistry methods and implicit solvent models. As a result, increasing the docking accuracy. Additionally, the new algorithms now allow for flexible docking which estimates the docking energy of freely moving atoms in a ligand enhancing the positioning accuracy [10]. 

## Future Trends
In the future, the docking programs will focus on both accuracy and flexibility. Using more advanced optimization methods, along with more precise molecular energy calculations, and incorporating the quantum chemistry methods are expected to improve the programs from the two perspectives. In addition, better handling of the solvent effect is an area of development [11].

## Conclusion
In conclusion, many existing docking programs are utilizing global optimization methods to find the molecule that fits the target protein. However, their implementation and accuracy vary significantly. Nowadays, there is a huge need to eliminate simplified energy calculations and use more complex approaches like quantum chemistry and implicit solvent models. Hence, increasing the docking accuracy to find the best molecule fit.

## References 

1.	Chen Y-C. Beware of docking! Trends in Pharmacological Sciences 2015; 36: 78-95.
2.	Yuriev E, Holien J, Ramsland PA. Improvements, trends, and new ideas in molecular docking: 2012–2013 in review. 2015; 28: 581-604.
3.	Sulimov VB, Kutov DC, Sulimov AV. Advances in Docking. Curr Med Chem 2019; 26: 7555-7580.
4.	Klimovich PV, Shirts MR, Mobley DL. Guidelines for the analysis of free energy calculations. Journal of Computer-Aided Molecular Design 2015; 29: 397-411.
5.	Forli S, Huey R, Pique ME et al. Computational protein–ligand docking and virtual drug screening with the AutoDock suite. Nature Protocols 2016; 11: 905-919.
6.	Abagyan R, Totrov M, Kuznetsov D. ICM—A new method for protein modeling and design: Applications to docking and structure prediction from the distorted native conformation. 1994; 15: 488-506.
7.	Allen WJ, Balius TE, Mukherjee S et al. DOCK 6: Impact of new features and current docking performance. J Comput Chem 2015; 36: 1132-1156.
8.	Liebeschuetz JW, Cole JC, Korb O. Pose prediction and virtual screening performance of GOLD scoring functions in a standardized test. Journal of Computer-Aided Molecular Design 2012; 26: 737-748.
9.	Friesner RA, Banks JL, Murphy RB et al. Glide:  A New Approach for Rapid, Accurate Docking and Scoring. 1. Method and Assessment of Docking Accuracy. Journal of Medicinal Chemistry 2004; 47: 1739-1749.
10.	Chen W, Gilson MK, Webb SP, Potter MJ. Modeling Protein−Ligand Binding by Mining Minima. Journal of Chemical Theory and Computation 2010; 6: 3540-3557.
11.	Ryde U, Söderhjelm P. Ligand-Binding Affinity Estimates Supported by Quantum-Mechanical Methods. Chemical Reviews 2016; 116: 5520-5566.

