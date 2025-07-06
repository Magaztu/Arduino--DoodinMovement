# Arduino--DoodinMovement
Little Arduino project I made a while ago, it's just a dood being silly!


This project uses a weight sensor and a DC motor to move / make dance a dummy.
It has two modes: coin weight and spin levels.


## In Spin levels, or manual mode:
  - You must use the keypad to control the speed.
      - Max. speed level is 7.
  - Press `*` to change the mode.

## In Coin weight, or automatic mode:
  - Put coins in the scales [Dollars or 10 Cents coins].
    - Max. speed level is reached at $2.
  - Press `*` to change the mode.

### Other parts:
This project also uses a (SCALE MODEL), (SCALE CONTROLLER), 4X4 KEYPAD, (MOTOR CONTROLLER), DC MOTOR, HANDCRAFT MATERIALS.

### Documentation:
This repo also includes a `/evidence` folder and a `/docs` folder, the first one includes pictures of this prototype and the later is a .docx with further information about it.

#### Pin connection guide:
(This are the pin connections for a Arduino board, for other components' pin connections, check `/docs`)
- Pin 2 -> DT, HX711 module
- Pin 3 -> SCK, HX711 module
- Pin 4 -> 3era columna de Keypad 4x4
- Pin 5 -> ENA, L298N module
- Pin 6 -> IN1, L298N module
- Pin 7 -> IN2, L298N module
- Pin 8 -> 2da columna de Keypad 4x4
- Pin 9 -> 1era columna de Keypad 4x4
- Pin 10 -> 4ta fila de Keypad 4x4
- Pin 11 -> 3era fila de Keypad 4x4
- Pin 12 -> 2da fila de Keypad 4x4
- Pin 13 -> 1era fila de Keypad 4x4
- Pin A0 -> CLK, módulo HT16K33
- Pin A1 -> DIO, módulo HT16K33
- Pin A2 -> 4ta columna de Keypad 4x4
- Pin A4 -> SDA, pantalla LCD I2C
- Pin A5 -> SCL, pantalla LCD I2C

  `TO BE EDITED`
