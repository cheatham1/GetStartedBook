# Find the Higgs

Follow the steps of a real ATLAS analysis. 

**H->WW->4l**

We are looking for a Higgs which decays into 2 W bosons which subsequently decay into leptons. 

Use the cursor to implement the following cuts, one by one.
As you apply the cuts, you should see the distributions changing.  

## Analysis 1:

If we consider both W-boson decay leptonically, the final state is characterised by the presence of two highly energetic leptons, large MET and 2 jets from the 2 b-quarks.

Select: 
* **2 jets**
* **B-tag**
* **MET > 40GeV**
* **Only electron-muon (em) channel**


![](pictures/ttbarSelection.png)

## Analysis 2:

Select: 
* **0 jets**
* **No B-tag**
* **MET < 20GeV**
* **Only electron-muon (em) channel**
* **DeltaPhiLL > 160**


![](pictures/WWselection2.png)

We also see that we have about 100 HWW events and 800 WW events left after the cuts.

Look at the ZWindow.
There are 2 peaks.  One at 10-25 GeV and the other at 35-40 GeV.

**Why do we see no Z in the N events histo, but we do see Z in the fiducial **

Now add a cut requiring Zwindow > 60GeV


![](pictures/WWpureSelection2.png)

The total number of WW events has reduced to around 100 but the sample is now very pure.
