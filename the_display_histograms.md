# The display histograms

App Analyser displays 9 histograms.
The description of each follows.

Let us consider two physics processes to understand which variables are important and why.


## top pair production

In the SM, the top-quark decays into a W-boson and a
b-quark with a branching ratio close to 100%.

W-bosons can decay either
* leptonically: into an electron or muon and neutrino. 
* hadronically: into an up-type quark and a down-type quark.

If a W-boson decays leptonically, the final state is characterised by the presence of a highly energetic isolated lepton and large missing transverse momentum due to the neutrino(s) escaping detection. 

If a W-boson decays hadronically, the final state is characterised by the presence of two jets due to the two quarks.

The two b-quarks from the top-quark decays will be seen as jets in the final state.   

In the App Analyser we have chosen datasets where both W-bosons decay leptonically.  So top pair production is accompanied by multiple jets.

## NJets

![](pictures/Njets.jpg)


Number of jets found in the event.

ttbar is accompanied by 2 or more jets. 
HWW is most prominent with 0 or 1 jet.  


## Channel

If both W-bosons decay leptonically we have either a di-electron (ee) , electron-muon (em) or muon-muon (mm) channel. Decays to taus or hadrons are not considered in this case.

## MET

In the LHC, the initial momentum of the colliding particles along the beam axis is not known because the energy of each proton is split, and constantly exchanged, between its constituents.  So the amount of total missing energy cannot be determined. 
However, the initial energy of particles travelling transverse to the beam axis is zero, so any net momentum in the transverse direction indicates missing transverse energy (MET).

Missing energy is commonly used to infer the presence of non-detectable particles such as the standard model neutrino and is expected to be a signature of many predicted physics events that contain particles that do not interact with the detector, for example the lightest supersymmetric particle.

Requiring MET removes Z+jets as it is does not have any neutrinos in the final state while the other processes do.


## BTag

This is a boolean whether there have been b-tagged jets or not in the event. This is actually something for the 1 jet bin and to get rid of ttbar as it is the one background where we expect to see btags


## ZWindow

This gives the deviation of the dilepton mass from the Z peak. For Z events this is obviously peaks at 0 but for HWW it peaks away from 0.


## SumLepPt

This is the vectorial sum of the transverse momenta of the charged leptons observed. For Z it peaks at 0 as the two leptons from the Z decay are relatively balanced against each other. For HWW you see that this distribution peaks at around 50.


## DeltaPhiLL

This is the opening angle in phi between the two leptons. Due to the Higgs being a scalar the distribution seen here peaks at rather low values in contrast to all other backgrounds.



## Fiducial cross section


One can use it as an indicator of the purity of the selection. In the beginning we have all processes as they were preselected. Because of its large cross section Z is quite pure.
If we select four jets, MET > 40 GeV, require a b-tag and only take the em channel we have a very pure sample of ttbar
If we select zero jets, MET < 20 GeV, no btag, ZWindow > 60, only the em channel and SumLepPt < 20 GeV we get a quite clean sample of WW
Getting a clean HWW sample is not possible but you can get around a qarter of HWW and three quarters of WW in your selection

## Raw number of events


