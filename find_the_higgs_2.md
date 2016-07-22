# Find the Higgs

Follow the steps of a real ATLAS analysis using Histogram Analyser

**H→WW→ℓνℓν** (ℓ = electron, muon)

We are looking for a Higgs boson which decays into 2 W bosons which subsequently decay into leptons and neutrinos. 

The major background contributions to the search in this decay mode are top (top quark pair and W+top quark), WW and W+jet events.

**Use the cursor to implement the following cuts, one by one.
As you apply the cuts, you should see the distributions changing.**  

Try to understand why each of the distributions change.  Think of the physics motivating the cuts.

**To clear your selection on a specific histogram click on the white background within the histogram area. **

**To clear all your selections click on "Histogram Analyser" under Get Started in the main top menu.**


Now let's try to separate the signal from the background using Histogram Analyser

## Higgs boson + 0 jet
We want to select events which contain two leptons, high missing transverse momentum and no jets.  

Select: 

* Reconstructed Dilepton Mass < 75 GeV
* Number of Jets = 0  
* Total Lepton Transverse Momentum > 30 GeV
* Missing Transverse Momentum > 40 GeV
* Opening Angle between Leptons < 80


The dominant background after all these cuts in the
Higgs boson + 0 jet channel comes from ttbar.

4 Higgs events are identified, with a significance of 0.265


Adding an extra cut, opening angle between MET and leptons > 140, reduces the signal to 3 events and increases the significnace to 0.276

## Higgs boson + 1 jet

Select: 

* electron-muon channel only
* Reconstructed Dilepton Mass < 70 GeV
* Number of Jets = 1
* Jets are not b-tagged
* Total Lepton Transverse Momentum > 30 GeV
* Opening angle between leptons < 80

The dominant background after all these cuts in the
Higgs boson + 1 jet channel comes from WW and top pair
production.  

2 Higgs events.  Significance 0.517

## Have a go yourself!

Perhaps try the H→WW + 0 jet, but separate it into leptonic channels and tune the cuts to maximise the number of H→WW events with minimum background.  

Or try something completely different...

