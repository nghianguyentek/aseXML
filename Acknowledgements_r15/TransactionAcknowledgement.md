# TransactionAcknowledgement Type

## Purpose

Acknowledge a received transaction

## Detail

For every transaction, a transaction acknowledgment is generated.

Any errors are reported via Event elements.

If a transaction is rejected, no receipt identifier need be provided with the acknowledgement.

## Attributes

- [initiatingMessageID](../Header_r37/MessageIdentifier) (required)
- [receiptID](ReceiptIdentifier)
- receiptDate (DateTime; required)
- [status](TransactionStatus) (required)
- duplicate (`Yes`|`No`; default: `No`)
- acceptedCount (Non-NegativeInteger)

## Elements

- [Event](../Events_r43/Event) (optional; unlimited)