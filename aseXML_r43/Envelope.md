# Envelope Type

## Purpose

Envelope used by all aseXML compliant messages.

## Detail

The envelope consists of a header element followed by a payload element. The payload may either be one or more transactions, or one or more acknowledgements.
A detailed description of aseXML may be found in "Guidelines for Development of A Standard for Energy Transactions in XML (aseXML)".

## Elements

1. [Header](../Header_r37/Header)
2. [Transactions]() or [Acknowledgements]()