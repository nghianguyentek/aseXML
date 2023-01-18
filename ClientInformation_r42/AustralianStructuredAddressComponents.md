# AustralianStructuredAddressComponents Type

## Purpose

Define those fields of an Australian address that are only provided as part of a structured address

## Detail

See the definition of AustralianAddress for more details. This type should be used where a complete address is being provided. If only part of an address is being provided, use the AustralianStructuredAddressPartialComponents type.

## Elements

1. [FlatOrUnit](FlatUnit.md) (optional)
2. [FloorOrLevel](FloorOrLevel.md) (optional)
3. [BuildingOrPropertyName](AustralianBuildingOrPropertyName.md) (optional; nillable; limited: 2)
4. [LocationDescriptor](AustralianLocationDescriptor.md) (optional; nillable)
5. [House](House.md) (optional; limited: 2)
6. [Lot](Lot.md) (optional)
7. [Street](Street.md) (optional; limited: 2)
8. [PostalDelivery](PostalDelivery.md) (optional)