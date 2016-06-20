# The display histograms

App Analyser displays 9 histograms.
The description of each follows:


## NJets

![](pictures/Njets.jpg)


Number of jets found in the event.

H->WW is most prominent in the 0 and 1 jet bin, whereas ttbar tends to have higher jet multiplicities

## Channel

Both W bosons decay to leptons so we may have either a di-electron (ee) , electron-muon (em) or muon-muon (mm) channel depending on the actual decay taking place. Decays to taus or hadrons are not considered.

## MET

Missing transverse momentum. This cut is mainly intended to get rid off Z+jets as it is does not have any neutrinos in the final state while the other processes do.


## BTag

This is a boolean whether there have been b-tagged jets or not in the event. This is actually something for the 1 jet bin and to get rid of ttbar as it is the one background where we expect to see btags


## ZWindow

This gives the deviation of the dilepton mass from the Z peak. For Z events this is obviously peaking at 0 but for Higgs to WW it peaks away from it.


## SumLepPt

This is the vectorial sum of the transverse momenta of the charged leptons observed. For Z it peaks at 0 as the two leptons from the Z decay are relatively balanced against each other. For HWW you see that this distribution peaks at around 50.


## DeltaPhiLL

This is the opening angle in phi between the two leptons. Due to the Higgs being a scalar the distribution seen here peaks at rather low values in contrast to all other backgrounds.