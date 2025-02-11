# STM32H7-FREERTOS-setup
## First Step
### Debug
```
Serial Wire --- ST-Link
```
### SYS
Timebase Source
```
Basic Timer --- e.g. TIM6
```
### RCC
Depends on your senario
```
Higher than 240MHz
Power Regulator Voltage Scale --- Power Regulator Voltage Scale 0
Product Revision --- V (only if chip revision = rev.V)

Higher than 480MHz
Power Regulator Voltage Scale --- Power Regulator Voltage Scale 0
Product Revision --- V (only if chip revision = rev.V)
```
### Coretex-M7
Depends on your senario
```

```
