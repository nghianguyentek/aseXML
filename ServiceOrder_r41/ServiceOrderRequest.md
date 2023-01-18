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
3. [ContactDetail](CustomerDetail.md) (optional)
4. [CustomerDetail](CustomerDetail.md) (optional)
5. [Co-ordinatingContactDetail](CustomerDetail.md) (optional)
6. [AppointmentDetail](AppointmentDetail.md) (optional)
7. [RequestData](ServiceOrderRequestData.md) (optional)
8. [NotifiedParties](NotifiedParties.md) (optional)

