TEST PLAN AND OUTPUT:
---------------------------------------------------------------------------------------------------------------------------------

|Test ID   |Test Case objective  |Input data   |Expected output   |Actual Output| Status|
|----------|---------------------|-------------|------------------|-------------|-------|
|TC-01|Check encryption|3+4|7|7|Pass|
|TC-01     |Lock the system    |7 & press blue switch once |Car door locked(All LEDs are ON) | Car door is locked(All LEDs are ON)| Pass|
|TC_02     |Unlock the system  | Press the blue switch is pressed twice | Car door unlocked(All leds are OFF) | Car door unlocked(All LEDs are OFF)|Pass|
|TC_03     |Alarm activation/deactivation  | Press blue switch three times |Car alarm activate/deactivate(All LED are ON in clockwise manner) | Car alarm activate/deactivate(All LEDs are ON in clockwise manner)|Pass|
|TC_04| Approach light |Press the blue switch four  |Car alarm approach light(All LEDs are ON in anti-clockwise manner)| Car alarm approach light(All LEDs are ON in anti-clockwise manner)|Pass|
