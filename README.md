Two-Way Relaying with Hardware Impairments
==================

This is a code package is related to the follow scientific article:

Michail Matthaiou, Agisilaos Papadogiannis, Emil Björnson, Mérouane Debbah, “[Two-way Relaying under the Presence of Relay Transceiver Hardware Impairments](http://arxiv.org/pdf/1307.2923),” IEEE Communications Letters, vol. 17, no. 6, pp. 1136-1139, June 2013.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


##Abstract of Article

Hardware impairments in physical transceivers are known to have a deleterious effect on communication systems;
however, very few contributions have investigated their impact on relaying. This paper quantifies the impact of transceiver impairments in a two-way amplify-and-forward configuration. More specifically, the effective signal-to-noise-and-distortion ratios at both transmitter nodes are obtained. These are used to deduce exact and asymptotic closed-form expressions for the outage probabilities (OPs), as well as tractable formulations for the symbol error rates (SERs). It is explicitly shown that non-zero lower bounds on the OP and SER exist in the highpower regime—this stands in contrast to the special case of ideal hardware, where the OP and SER go asymptotically to zero.


##Content of Code Package

The article contains 2 simulation figures, numbered from 2 to 3. These are generated by the Matlab scripts simulationFigure2.m and simulationFigure3.m. The package contains one additional script, functionSERintegrand.m, which is called by the other scripts.

See each file for further documentation. 


##Acknowledgements

E. Björnson is funded by the International Postdoc Grant 2012-228 from the Swedish Research Council.


##License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
