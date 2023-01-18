# Header Type

## Purpose

Define the contents of the aseXML message header.

## Detail

Every aseXML message carries a header. It is used to indicate information pertaining to the message as a whole.
When not provided, a default value of NEM will be assumed for the market.

## Elements

1. [From](../Common_r43/PartyIdentifier.md)
2. [To](../Common_r43/PartyIdentifier.md)
3. [MessageID](MessageIdentifier.md)
4. MessageDate (DateTime)
5. [TransactionGroup](TransactionGroup.md)
6. [Priority](TransactionPriority.md) (optional)
7. [SecurityContext](MessageSecurityContext.md) (optional)
8. [Market](EnergyMarket.md) (default: `NEM`, optional)