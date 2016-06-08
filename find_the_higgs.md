# Find the Higgs

Follow the steps of a real ATLAS analysis. 

**H->ZZ->llqq**.

We are looking for a Higgs which decays into 2 Z bosons which subsequently decay into 2 leptons and 2 quarks. 

Use the cursor to implement the following cuts, one by one.
As you apply the cuts, you should see the distributions and number of events changing.  Check your number of events remaining with the numbers in the table below.


## Cuts:

* Opposite Sign:  The product of the charges of the two selected muons (lep charge product)
should be equal to -1.  (Not to be applied to Electron channel)

* Two Jets:  The number of jets (njets) should be at least 2

* Dilepton Mass:  The invariant mass of the two leptons (lepZm) must be between 83 GeV and 99 GeV

* MET: The value of the Missing Transverse Energy (MET) should be less than 60 GeV

* NumTagJets[0-1-2]:  Number of b-jets (nbjets) is equal to 0 (or 1 or 2)

Comment: the analysis is divided in three categories according to the number of b-jets, so this and the next 2 cuts are applied for each of the cases: 0 or 1 or 2 b-jets

* PtLeadingJet[0-1-2]:  The transverse momentum of the leading jet (realJ1LJpt) should be greater than 45 GeV

* DiJetMass[0-1-2]:   The  invariant  mass  of  the  two  selected  jets  (realZLJm)  should  be between 70 GeV and 105 GeV


|Cut          | Number of Events     |
| -- | -- |
|No cut         |      |
|Opposite sign  | 8056 |
|Two jets       | 7282 |
|DilpetonMass   | 6088 |
|MET            | 5758 |








