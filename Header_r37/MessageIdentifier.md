# MessageIdentifier Type

*String*

- MinLength: 1
- MaxLength: 36

## Purpose

Uniquely identify every message generated by the message sender

## Detail

Note that message identifiers do not have to be globally unique, only unique to a particular sender. However, the length has been chosen such that UUIDs can be used as message identifiers if considered appropriate, guaranteeing global uniqueness.

A message acknowledgement identifies which message it is acknowledging by providing the message identifier as an attribute.