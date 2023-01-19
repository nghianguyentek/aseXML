# ServiceOrderRequest Transaction Type

## Purpose

Submit Service Order Request to the Service Provide

## Detail

- Application - `Service Order`
- TransactionExchange -
- TransactionGroup - `SORD`
- Priority - `Medium`

## Attributes

- version (default: `r41`)
- [actionType](ActionType.md) (default: `New`)

## Elements

1. [ServiceOrder](ServiceOrderHeader.md)
2. [ServicePoint](../Common_r43/ServicePoint.md) (optional)
3. [ContactDetail](../CustomerDetails_r41/CustomerDetail.md) (optional)
4. [CustomerDetail](../CustomerDetails_r41/CustomerDetail.md) (optional)
5. [Co-ordinatingContactDetail](../CustomerDetails_r41/CustomerDetail.md) (optional)
6. [AppointmentDetail](../Common_r43/AppointmentDetail.md) (optional)
7. [RequestData](ServiceOrderRequestData.md) (optional)
8. [NotifiedParties](../Common_r43/NotifiedParties.md) (optional)

