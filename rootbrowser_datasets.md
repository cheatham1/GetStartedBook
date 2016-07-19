# ROOTbrowser datasets

There are two real datasets for you to look at
* data_Egamma.root : electrons and photons
* data_Muons.root : muons

Then there are a range of simulated datasets from 
* DY: Drell-Yan processes
* ggH: gluon+gluon->Higgs boson
* stop: superpartner of the top quark as predicted by supersymmetry.
* ttbar: top pair production
* VBF: Vector Boson Fusion
* W+jets: W boson decay to various final states
* WW: W boson pair
* WZ: W+Z boson
* Zee: Z boson decay to two electrons
* Zmumu: Z boson decay to two muons
* Zprime: superpartner of the Z boson as predicted by supersymmetry.
* Ztautau: Z decay to two taus
* ZZ: Z boson pair


## Simulated data
Simulated events are a key feature for the LHC
experiments, commonly named Monte Carlo or Monte Carlo simulated data to be precise. 
These events are simulated using current theoretical models and are used to compare theory with real data.

The full simulation requires the following steps
* Event generation: Final states using the
proton-proton collisions are generated using programs relying  on  theoretical  calculations,  phenomenological
models and experimental inputs.

* Detector Simulation: Interaction of the generated
particles inside the ATLAS detector is simulated.

* Digitisation: The detector response is derived from
the particle interactions and it is written in a format
compatible with the real output of the detector. In addition,
because of the high rate of collisions in the LHC, digitised
signals from several simulated events can be piled-up to
create samples with a realistic experimental background.

* Reconstruction:  particle trajectories and energies
from the detector are reconstructed. Such final samples
are used by the physicists.

## Comparing data and simulated data

Data and simulated data do not always agree.  This can be due to various reasons, such as

* the conditions not being exactly the same e.g. Energy, pile-up etc.

* not all background processes are included in the simulated data. 

* the physics has not been exactly modeled by the theory.

If the data and simulated data does not agree, it is important that physicists understand why.