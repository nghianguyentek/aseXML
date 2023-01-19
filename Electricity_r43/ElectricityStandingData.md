# ElectricityStandingData Type

*Extends [NMIStandingData](../Common_r43/NMIStandingData.md)*

## Purpose

Standing data associated with an electricity NMI.

## Detail

The structure supports multiple data streams, meters and role assignments. Note that because this type is derived from the NMIStandingData type, it begins with the elements defined for that type, notably the NMI.

## Attributes

- version (default: `r43`)

## Elements

1. [MasterData](ElectricityMasterStandingData.md) (optional)
2. [RoleAssignments](RoleAssignments.md) (optional)
3. [DataStreams](ElectricityDataStreams) (optional)
4. [MeterRegister](ElectricityMeters.md) (optional)