# Analyses

Histogram Analyser focusses on four physics processes; the signal Higgs boson process $$H\rightarrow W^+W^-$$ and three background processes $$WW$$, $$t\bar t$$ and $$Z$$+jets.
Let's take a look at these processes. 

## $$H\rightarrow W^+W^-$$
 
The [Higgs boson](https://home.cern/topics/higgs-boson) is an essential ingredient of the [Standard Model](https://home.cern/about/physics/standard-model) of particle physics, the theory that describes all known elementary particles and their interactions. 

The Higgs boson interacts with all Standard Model elementary particles having mass.  Thus, there are different ways to produce a Higgs boson, and different ways for a Higgs boson to decay to other particles.

One of the most likely ways a Higgs boson will decay is into a pair of [W bosons](https://home.cern/about/physics/w-boson-sunshine-and-stardust). 
This happens about 23% of the time for a Higgs boson with a mass of 125 GeV.
The $$W$$ bosons can subsequently decay either into a quark-antiquark, a [lepton](https://en.wikipedia.org/wiki/Lepton)-[antineutrino](https://en.wikipedia.org/wiki/Neutrino), or an antilepton-neutrino pair.

The process we want to study is known as the **signal process**.
The signal process in Histogram Analyser is the Higgs boson decaying into two $$W$$ bosons which subsequently decay into leptons and neutrinos:

$$H\rightarrow W^+W^-\rightarrow ℓ^+ ℓ^-\nu \bar\nu$$   (ℓ= lepton = electron or muon).

A key feature, or **signature** of this signal process, is an isolated high-$$p_\text{T}$$ lepton. 
The term $$p_\text{T}$$ stands for transverse momentum, the component of momentum perpendicular to the beam line (colliding protons).  Unfortunately, the main background processes also contain isolated high-$$p_\text{T}$$ leptons from $$W$$ or $$Z$$ boson decays.

Often physicists refer to a particle and its [antiparticle](https://en.wikipedia.org/wiki/Antiparticle) collectively by just the particle's name.  So, when we talk about quarks we mean quarks and antiquarks.
It is a shorthand that physicists adopt for brevity. 

![](EventDisplays/HWW2plusCaption.png)

## $$WW$$

The $$W$$ boson is a fundamental particle. Together with the $$Z$$ boson, it is responsible for the weak force, one of four fundamental forces that govern the behaviour of matter in our universe. 

$$W$$ boson pair production occurs via

* **quark–antiquark annihilation:** $$q\bar q \rightarrow W^+W^-$$
 
* **diphoton process:**  $$\gamma\gamma\rightarrow W^+W^-$$

* **gluon fusion:** $$gg\rightarrow W^+W^-$$


$$W$$ boson pair production is an important process for checks of the [gauge structure](https://en.wikipedia.org/wiki/Gauge_theory) of the Standard Model and the search for [new physics](https://en.wikipedia.org/wiki/Physics_beyond_the_Standard_Model).
It is an irreducible background for many Higgs boson studies and new physics searches. 

$$W$$ bosons can decay either
* [leptonically](https://en.wikipedia.org/wiki/Lepton): into an [electron](https://en.wikipedia.org/wiki/Electron) or [muon](https://en.wikipedia.org/wiki/Muon) and [neutrino](https://en.wikipedia.org/wiki/Neutrino). 
* [hadronically](https://en.wikipedia.org/wiki/Hadron): into an [up-type quark](https://en.wikipedia.org/wiki/Quark) and a [down-type quark](https://en.wikipedia.org/wiki/Quark).

Leptonic $$W$$ boson decays are characterised by the presence of a highly energetic isolated lepton and large missing transverse momentum.  Missing transverse momentum can occur due to neutrinos escaping detection. 

Hadronic $$W$$ boson decays lead to the presence of two jets due to the two quarks.

Only leptonic decays are considered in Histogram Analyser.
The $$WW$$ process will thus be seen in the electron-electron (ee), muon-muon (mm) and electron-muon (em) channel.

Final states with leptons and missing energy are typical for many new physics models ,[supersymmetry](https://home.cern/about/physics/supersymmetry) is a classic example, but also for many Standard Model processes.

Understanding the Standard Model processes possessing multiple leptons and missing energy is crucial in the quest to discover or rule out new models.

![](EventDisplays/WWplusCaption.png)

## $$t\bar t$$

The [top quark](https://press.cern/backgrounders/top-quark) is the only quark that can be studied in isolation, due to its high mass and short lifetime.
All other quarks are only accessible as constituents of hadrons.

Top quark processes can be used to optimise data simulation generators,  [QCD](https://en.wikipedia.org/wiki/Quantum_chromodynamics) models and parton distribution functions.

Top quark pair production is an important background in various Higgs boson analyses and beyond the Standard Model searches.
It is therefore crucial to understand this process in detail. 

In the Standard Model, the top-quark generally decays into a [$$W$$ boson](https://en.wikipedia.org/wiki/W_and_Z_bosons) and a 
[$$b$$-quark](https://en.wikipedia.org/wiki/Bottom_quark).

As we said before, $$W$$ bosons can decay either [leptonically](https://en.wikipedia.org/wiki/Lepton) or [hadronically](https://en.wikipedia.org/wiki/Hadron), but in Histogram Analyser we just consider the leptonic decays.

The two $$b$$-quarks from the two top-quark decays will be seen as two jets in the final state.
Algorithms are used to identify these jets.
Jets thought to originate from $$b$$-quarks are called b-tagged jets.
Additional jets in $$t \bar t $$ events can originate from gluon radiation.

For top quark studies, three channels are available depending on the decays of the $$W$$ bosons:
* If both $$W$$ bosons decay leptonically two jets are seen, originating from the $$b$$-quarks.
* If both $$W$$ bosons decay hadronically, six jets are seen, two from each $$W$$ and two from the $$b$$-quarks.
* If the decay is semi-leptonic, one $$W$$ boson decays leptonically and the other hadronically; four jets are seen, two of them are from $$b$$-quarks.

![](EventDisplays/ToppairPlusCaption.png)

## $$Z$$

The [$$W$$](http://home.cern/about/physics/w-boson-sunshine-and-stardust) and [$$Z$$](http://home.cern/about/physics/z-boson) bosons are together known as the weak or intermediate vector bosons.  

At the LHC, $$Z$$ bosons are produced by:

* **Drell-Yan **: $$ q \bar q \rightarrow Z/\gamma^* \rightarrow \mu^+\mu^-$$(65%). A quark of one proton and an antiquark of another proton annihilate, creating a [virtual photon](https://en.wikipedia.org/wiki/Virtual_particle) or $$Z$$ boson which then decays into a pair of oppositely-charged leptons. 

* **Quark gluon scattering**: $$qg \rightarrow qZ/γ^* \rightarrow q\mu^+\mu^−$$ (35%). A quark and a [gluon](https://en.wikipedia.org/wiki/Gluon) interact and the quark radiates a virtual photon or $$Z$$ boson which then decays into a pair of oppositely-charged leptons. 

A $$Z$$ boson then decays into a:

* **quark-antiquark pair** (70%). These appear as jets.  If the jets are identified as originating from $$b$$-quarks they will be b-tagged.

* **neutrino-antineutrino pair** (20%).  Neutrinos do not interact and so are very difficult to detect.  This neutrino decay mode can sometimes be identified by missing transverse momentum.

* **lepton-antilepton pairs** (10%).  The three lepton-pair types are equally probable, [electron](https://en.wikipedia.org/wiki/Electron)-positron, [muon](https://en.wikipedia.org/wiki/Muon)-antimuon, and [tau](https://en.wikipedia.org/wiki/Tau_(particle)-antitau pairs.  

A $$Z$$ boson is neutral and so the sum of the charges of its decay products must be zero.

In Histogram Analyser the lepton-antilepton pair production can be studied in the electron-electron (ee) and muon-muon (mm) channel.
Electrons and muons are much easier to measure than $$\tau$$-leptons.

![](EventDisplays/ZmumuPlusCaption.png)


