# TP4_MINF
## Explication complementaire gestion memoire de l'EEPROM

## Écriture dans l'EEPROM

### Fonction complète

```c
void I2C_WriteSEEPROM(void *SrcData, uint32_t EEpromAddr, uint16_t NbBytes)