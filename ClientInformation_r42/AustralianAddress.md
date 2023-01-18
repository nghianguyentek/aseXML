# AustralianAddress Type

## Purpose

Define an Australian address

## Detail

The Australian address format allows for either a structured or an unstructured physical address, with locality, state and postcode always being carried as structured elements. In addition, it supports postal address formats. It follows the definitions and rules set out in AS4590 for address exchange.

It is important to note the occurrence frequency of elements within the format, particularly BuildingOrPropertyName, House and Street.

## Elements

1. [StructuredAddress](AustralianStructuredAddressComponents) or [UnstructuredAddress](UnstructuredAddress)
2. [SuburbOrPlaceOrLocality](AustralianSuburbOrPlaceOrLocality) (optional; nillable)
3. [StateOrTerritory](AustralianStateOrTerritory)
4. [PostCode](AustralianPostCode)
5. [DeliveryPointIdentifier](AustralianDeliveryPointIdentifier) (optional; nillable)
6. [GNAFPID](GeocodeNationalAddressFilePersistentIdentifier) (optional; nillable)