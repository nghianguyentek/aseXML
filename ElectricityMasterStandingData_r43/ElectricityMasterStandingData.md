# ElectricityMasterStandingData Type

## Purpose

Container for non-repeating standing data associated with an electricity NMI

## Elements

1. [JurisdictionCode](../Common_r43/JurisdictionCode.md) (optional; nillable)
2. [NMIClassificationCode](../Common_r43/NMIClassificationCode.md) (optional; nillable)
3. [TransmissionNodeIdentifier](../Electricity_r43/TransmissionNodeIdentifier.md) (optional; nillable)
4. [DistributionLossFactorCode](../Electricity_r43/DistributionLossFactorCode.md) (optional; nillable)
5. [ParentEmbeddedNetworkIdentifier](EmbeddedNetworkIdentifier.md) (optional; nillable)
6. [ChildEmbeddedNetworkIdentifier](EmbeddedNetworkIdentifier.md) (optional; nillable)
7. [Address](AustralianPartialAddress.md) (optional; nillable)
8. Aggregate (`YesNo`; optional; nillable)
9. [Status](NMIStatus.md) (optional; nillable)
10. [DistanceFromSubstation](DistanceFromSubstation.md) (optional; nillable)
11. [VoltageType](VoltageType.md) (optional; nillable)
12. [PoleNumber](PoleNumber.md) (optional; nillable)
13. [AccessDetails](AccessDetail.md) (optional; nillable)
14. [FeederClass](FeederClass.md) (optional; nillable)
15. [CustomerClassificationCode](EMSDCustomerClassificationCode.md) (optional; nillable)
16. [CustomerThresholdCode](EMSDCustomerThresholdCode.md) (optional; nillable)