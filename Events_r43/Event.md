# Event Type

## Purpose

Common format used to report events

## Detail

aseXML encourages the use of events in transactions to report status information. They are also used in message and transaction acknowledgements. Where possible, an element name of "Event" should be used.

## Attributes

- [class](EventClass.md) (default: `Application`)
- [severity](EventSeverity.md) (default: `Fatal`)

## Elements

1. [Code](EventCode.md)
2. [KeyInfo](EventKeyInfo.md) (optional)
3. [Context](EventContext.md) (optional)
4. Explanation (String; optional)
5. [SupportedVersions](EventSupportedVersions.md) (optional)