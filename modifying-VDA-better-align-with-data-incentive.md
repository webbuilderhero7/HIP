#Modifying VDA to better align with data incentives HIP-XXX


This HIP aims to aligns the current VDA score more with the generators of data burn on the network.

The change is simple in HIP-51 the "VDA" score is outlined however there is an imbalance between the variables, and is not rewarding accordingly,

This HIP proposal aims to change the current score:

DAO Utility Score=V×D×A
where
V=max(1,SQRT(veHNTDNP)
D=max(1,SQRT(DNP DCs burned in USD)
A=max(1,4SQRT(DNP Active Device Count×DNP Device Activation Fee4)

To:

DAO Utility Score=V×D×A
where
V=max(1,SQRT(veHNTDNP)
D=max(1,(DNP DCs burned in USD)
A=max(1,4SQRT(DNP Active Device Count×DNP Device Activation Fee4)

This incredibly simple change increases data usage alignment to help reward drivers in data consumption. 


Previous HIPs
51,52,53

Drawbacks:

Changing the reward mechanism is always something that should be done minimally.