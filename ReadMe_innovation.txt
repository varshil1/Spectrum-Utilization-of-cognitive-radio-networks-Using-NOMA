From the report using equation(8), we can generate the graph by varying values of Pf and can get values of Pd.
Parameters used are:
σi is the noise power in subchannel i 

gi is the subchannel gain between PU transmitter and
receiver

The SU and the PU transmit data in subchannel
i with the power pi and qi

subchannel sensing time τ

M is the number of the samplings

Supposing the sampling frequency is fs,
we have M = τfs.

Sometimes spectrum sensing is imperfect, in which we let
Pf ≤ α and Pd ≥ β. From (24) and (25), we can get that the
range of sensing threshold as follows

In the simulations, the total number of subchannels is N =
40, the frame time is T = 1s, the subchannel sensing time is
τ = 20ms, the absence and presence probabilities of the PU
are u0 = u1 = 0.5, the noise power σi = 0.01mW, and the
channels obey the Rayleigh fading.

fs can be taken as 500hz.

ρ is the detection threshold



Here detection_probabilit.m is the main function and nak_m.m is the function of nakagami channel.