Massive MIMO Systems with Non-Ideal Hardware: Energy Efficiency, Estimation, and Capacity Limits
==================

This is a code package is related to the follow scientific article:

Emil Björnson, Jakob Hoydis, Marios Kountouris, Mérouane Debbah, “[Massive MIMO Systems with Non-Ideal Hardware: Energy Efficiency, Estimation, and Capacity Limits](http://arxiv.org/pdf/1307.2584),” IEEE Transactions on Information Theory, vol. 60, no. 11, pp. 7112-7139, November 2014.


The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


## Abstract of Article

The use of large-scale antenna arrays can bring substantial improvements in energy and/or spectral efficiency to wireless systems due to the greatly improved spatial resolution and array gain. Recent works in the field of massive multiple-input multiple-output (MIMO) show that the user channels decorrelate when the number of antennas at the base stations (BSs) increases, thus strong signal gains are achievable with little inter-user interference. Since these results rely on asymptotics, it is important to investigate whether the conventional system models are reasonable in this asymptotic regime. This paper considers a new system model that incorporates general transceiver hardware impairments at both the BSs (equipped with large antenna arrays) and the single-antenna user equipments (UEs). As opposed to the conventional case of ideal hardware, we show that hardware impairments create finite ceilings on the channel estimation accuracy and on the downlink/uplink capacity of each UE. Surprisingly, the capacity is mainly limited by the hardware at the UE, while the impact of impairments in the large-scale arrays vanishes asymptotically and inter-user interference (in particular, pilot contamination) becomes negligible. Furthermore, we prove that the huge degrees of freedom offered by massive MIMO can be used to reduce the transmit power and/or to tolerate larger hardware impairments, which allows for the use of inexpensive and energy-efficient antenna elements.


## Content of Code Package

The article contains 11 simulation figures. These figures are generated by a number of different Matlab-scripts: simulationFigure3.m, simulationFigure4.m, simulationFigure5.m, simulationFigure6.m, simulationFigure7.m, simulationFigure8.m, simulationFigure9and10.m, simulationFigure11.m, simulationFigure12.m, simulationFigure14.m

The package contains 2 additional Matlab functions: functionEnergyEfficiency.m and functionOneRingModel.m. These functions are called by the Matlab scripts.

See each file for further documentation. 


##Acknowledgements

The work of E. Björnson was funded by the International Postdoc Grant 2012-228 from The Swedish Research Council. This research has been supported by the ERC Starting Grant 305123 MORE (Advanced Mathematical Tools for Complex Network Engineering). Parts of this work have been performed in the framework of the FP7 project ICT-317669 METIS. This work was supported by the Future and Emerging Technologies (FET) project HIATUS within the Seventh Framework Programme for Research of the European Commission under FET-Open grant number 265578.


## License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
