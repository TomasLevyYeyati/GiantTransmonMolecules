# GiantTransmonMolecules
These are the codes used to plot every figure of the article.

"SinglePhotonTransmission.j" replicates fig 2(b)-(c), computing Infidelities and transmission and reflection of single photon pulses with an exact transfer matrix formalism.

"TwoPhotonTransmission.jl" replicates fig 3(a), computing the Two photon transmission in the chiral regime with the SLH formalism, for different input bandwidths and number of molecules and molecular anharmonicities U.

"TwoPhotonTransmissionScalingU.jl" replicates fig 3(b), with the same structure of "TwoPhotonTransmission.jl", but for a given number of molecules and bandwiths, changing U.

"TwoPhotonTransmissionLoss.jl" replicates fig 4(a), with the same structure of "TwoPhotonTransmission.jl",  but for a given number of molecules and bandwiths, adding loss into unwanted channels.

"TwoPhotonTransmissionSpectralNoise.jl" replicates fig 4(b), with the same structure of "TwoPhotonTransmission.jl",  but for a given number of molecules and bandwiths, adding random spectral inhomogeneities to the molecule's fundamental transition frequency. The plots may slightly diverge quantitavely (not qualitatevily) from the ones of the manuscript as is an statistical average over 15 random frequencies.

Supplemental Codes:

"SinglePhoton.jl" computes the output single photon wavepacket from a gaussian input, with an exact transfer matrix formalism. It can help to visualize the spectral distribution of the input and output wavepacket

"GreenFunction.jl" replicates figure 5, although is just plotting a given function.
