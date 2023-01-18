# MessageAcknowledgement Type

## Purpose

Acknowledge a received message.

## Detail

For every message, a message acknowledgment is generated (with the exception of messages containing message acknowledgements).

Any errors are reported via Event elements.

If a message is rejected, no receipt identifier need be provided with the acknowledgement.

## Attributes

- [initiatingMessageID](../Header_r37/MessageIdentifier.md) (required)
- [receiptID](ReceiptIdentifier.md)
- receiptDate (DateTime; required)
- [status](MessageStatus.md) (required)
- duplicate (`Yes`|`No`; default: `No`)

## Elements

- [Event](../Events_r43/Event.md) (optional; unlimited)