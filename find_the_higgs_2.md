# Example: Find the Higgs

Follow the steps of a real ATLAS analysis using Histogram Analyser

$$H\rightarrow W^+W^- \rightarrow ℓ^+ ℓ^-\nu  \bar \nu$$ ($$ℓ$$ = electron, muon)

We are looking for a Higgs boson which decays into 2 $$W$$ bosons which subsequently decay into leptons and neutrinos. 

The major background contributions to the search in this decay mode are top (top quark pair and W+top quark), $$WW$$ and $$Z$$+jets events.

**Use the cursor to implement the following cuts, one by one.
As you apply the cuts, you should see the distributions changing.**  

Try to understand why each of the distributions change.  Think of the physics motivating the cuts.

**To clear your selection on a specific histogram click on the white background within the histogram area. **

**To clear all your selections click on "Histogram Analyser" under Get Started in the main top menu.**


Now let's try to separate the signal from the background using Histogram Analyser

## Higgs boson + 0 jet

We want to select events which contain two leptons, high missing transverse momentum and no jets.  

Select: 

* Number of Jets = 0 
* Reconstructed Dilepton Mass < 75 GeV
* Total Lepton Transverse Momentum > 30 GeV
* Missing Transverse Momentum > 40 GeV
* Opening Angle between Leptons < 80


The dominant background after all these cuts in the
Higgs boson + 0 jet channel comes from $$WW$$ and $$Z$$+jets.

3 Higgs events are identified, yielding a significance of 0.277

![](pictures/HWW0jet.png)

Adding an extra cut, the opening angle between MET and leptons > 140, reduces the signal to 3 events and increases the significance to 0.276

## Higgs boson + 1 jet

Select: 

* Number of Jets = 1
* no b-tagged jets
* electron-muon channel only
* Reconstructed Dilepton Mass < 70 GeV
* Total Lepton Transverse Momentum > 30 GeV
* Opening angle between leptons < 80


![](pictures/HWW1jet.png)

The dominant background after all these cuts in the
Higgs boson + 1 jet channel comes from $$WW$$ and top pair
production.  

2 Higgs events are identified, yielding a significance of 0.517.

## Have a go yourself!

Perhaps try the $$H\rightarrow W^+W^-$$ + 0 jet, but separate it into leptonic channels and tune the cuts to maximise the number of $$H\rightarrow W^+W^-$$ events with maximum significance.  

Or try something completely different...

