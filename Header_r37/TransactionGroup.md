# TransactionGroup Enum

## Purpose

Provide the transaction group to which all the contained transactions or transaction acknowledgments belong.

## Detail

The target application is at liberty to reject any transactions within the message that do not belong to the stated TransactionGroup. Where only message acknowledgements are carried, a transaction group of "MSGS" should be used.

The following groups are B2B process related:

- `FLTS`: Faults and Outages
- `SORD`: Service order, planned works
- `NETB`: Network billing
- `MTRD`: Meter data
- `CUST`: Customer related
- `NOTF`: Notifications (broadcast)
- `MKTW`: Wholesale market operations
- `HSMD`: High Speed Monitoring system
- `OWNP`: Own Way Notification
- `EMMS`: Electricity Market Management System
- `ERFT-NSW-ACT`: Wholesale Transaction Type
- `IAIT-NSW-ACT`: Wholesale Transaction Type
- `MRSR`: remote services request/response
- `OWNX`: NOMW, PIN and MFN
- `NPNX`: Notified Party transaction
- `PTPE`: Peer to Peer bilateral exchange
- `HMGT`: Hub management

## Values

- `CATS`
- `MDMT`
- `MSGS`
- `NMID`
- `FLTS`
- `SORD`
- `NETB`
- `MTRD`
- `CUST`
- `NOTF`
- `SITE`
- `FLDW`
- `OUTG`
- `BAR`
- `NMIF`
- `MKTW`
- `HSMD`
- `OWNP`
- `EMMS`
- `ERFT`
- `IAIT`
- `MRSR`
- `OWNX`
- `NPNX`
- `PTPE`
- `HMGT`