# Anycubic-Predator-SKR2-Klipper
Klipper config and firmware (STM32F407) for Anycubic Predator running SKR2 board and TMC2209 drivers. 


### Manual Leveling
Run **DELTA_CALIBRATE**, bring print head down to bed with **TESTZ** until it rubs against paper. Run **ACCEPT** when height is satisfactory and move onto next point. **SAVE_CONFIG** after last point.

```
G28
DELTA_CALIBRATE METHOD=manual
TESTZ Z=-.1
ACCEPT
SAVE_CONFIG
