| **TEST ID** |  **DESCRIPTON**                                              | **EXP IN** | **EXP OUT** |**ACTUAL OUT** |
|-------------|-----|--------------------------------------------------------------|------------|------|
|  HLR1|The panel moves towards the x axis  | LDR on x axis sensor senses light|the motors  on x axis  rotates|the motors  on x axis  rotates|
|  HLR2|The panel moves towards the y axis  |LDR on y axis sensor senses light|the motor on y axis rotates|the motor on y axis rotates|
|  HLR3|The panel stops rotating |there is no light on the LDR|the motors stops rotating|there is no light on the LDR|the motors stops rotating|
# Table : High level test plan
|Test ID| 	Description|
|---|----|
|H_01|	The sensor senses the intensity of light|
|H_02|	The panel moves towards the region where the intensity of light is more|
|H_03|	The panel stops moving when there is no light|

# Table : Low level test plan
|Test ID| 	Description|
|---|---|
|L_01 |	LDR sensor is used to sense the light  |
|L_02 |	One servo motor is used for tracking along x-axis and the other is for y-axis tracking|
|L_03 |	There is no light falls on LDR during night the motors stops rotating |
