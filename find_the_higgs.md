
# Find the Higgs

Follow the steps of a real ATLAS analysis. 

**H->WW->ℓνℓν**

We are looking for a Higgs which decays into 2 W bosons which subsequently decay into leptons and neutrinos. 

The major background contributions to the search in this decay mode are top, WW and W+jet events.

As a first step we are going to try and select the background processes, to understand them better.

**Use the cursor to implement the following cuts, one by one.
As you apply the cuts, you should see the distributions changing.**  Try and understand why each of the distributions changes.  Think of the physics motivating the cut.

## Analysis 1:

If we consider two W-bosons decaying leptonically, the final state is characterised by the presence of two highly energetic leptons, large MET and 2 jets from the 2 b-quarks.

Select: 
* **2 jets**
* **B-tag**
* **MET > 40GeV**
* **Only electron-muon (em) channel**


![](pictures/ttbarSelection.png)

This is the top-quark background.


**Clear your previous selection by clicking on App Analyser under Get Started in the main top menu.**

## Analysis 2:

Select: 
* **0 jets**
* **MET < 20GeV**
* **Only electron-muon (em) channel**
* **DeltaPhiLL > 160**


![](pictures/WWselection2.png)

We see that we have about 100 HWW events and 800 WW events left after the cuts.

Look at the ZWindow.
There are 2 peaks.  One at 10-25 GeV and the other at 35-40 GeV.

**Why do we see no Z in the N events histo, but we do see Z in the fiducial cross section? **

Now add a cut requiring Zwindow > 60GeV


![](pictures/WWpureSelection2.png)

The total number of WW events has reduced to around 100 but the sample is now very pure.

This is the WW background.



