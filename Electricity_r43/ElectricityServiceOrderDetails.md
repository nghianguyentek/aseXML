# ElectricityServiceOrderDetails Type

*Extends [ServiceOrderRequestData](../ServiceOrder_r41/ServiceOrderRequestData.md)*

## Purpose

Defines the data type for new connection and meter additions and alterations

### v36.1.WL.

Change LifeSupport to be optional field.

## Attributes

- version (default: `r41`)

## Elements

1. CustomerConsultationRequired (Boolean)
2. [InstallationType](InstallationType.md) (optional)
3. [SupplyPhase](SupplyPhase.md) (optional)
4. [AverageDailyLoad](AveragedDailyLoad.md) (optional)
5. [CustomerType](../ElectricityEnumerations/CustomerType.md) (optional)
6. [MeteringType](MeteringType.md) (optional)
7. [OffPeakRequirements](../Common_r43/SpecialComments.md) (optional)
8. [MaximumDemand](MeterDemand.md) (optional)
9. [ServiceTime](ServiceTimeType.md)
10. [SwitchingServiceRequired](SwitchingServiceRequired.md) (optional)
11. ConfirmedDe-energisation (Boolean; optional)
12. [License](License.md) (optional)
13. [MeterLicense](License.md) (optional)
14. [De-energisationReason](../ElectricityEnumerations/De-energisationReason.md) (optional)
15. LifeSupport (YesNo; optional)
16. Co-ordinationRequired (YesNo; optional)
17. [RegClassification](../ElectricityEnumerations/RegClassification.md) (optional)
18. [PurposeOfRequest](../ElectricityEnumerations/PurposeOfRequest.md) (optional)
19. [Escalation](../ElectricityEnumerations/Escalation.md) (optional)
20. ExemptionCode (String; optional)