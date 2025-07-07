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
This repo also includes a `/evidence` folder and a `/docs` folder, the first one includes pictures of this prototype and the later is a .docx with further information about it [In Spanish].

#### Pin connection guide:
(This are the pin connections for a Arduino board, for other components' pin connections, check `/docs`)
{The ones in `/docs` are in Spanish, I'll provide translations in the future}
- Pin 2 -> DT, HX711 module
- Pin 3 -> SCK, HX711 module
- Pin 4 -> Keypad's 4x4 third column
- Pin 5 -> ENA, L298N module
- Pin 6 -> IN1, L298N module
- Pin 7 -> IN2, L298N module
- Pin 8 -> Keypad's 4x4 second column
- Pin 9 -> Keypad's 4x4 first column
- Pin 10 -> Keypad's 4x4 fourth row
- Pin 11 -> Keypad's 4x4 third row
- Pin 12 -> Keypad's 4x4 second row
- Pin 13 -> de Keypad's 4x4 first row
- Pin A0 -> CLK, HT16K33 module
- Pin A1 -> DIO, HT16K33 module
- Pin A2 -> Keypad's 4x4 fourth column
- Pin A4 -> SDA, LCD I2C screen
- Pin A5 -> SCL, LCD I2C screen

  `TO BE EDITED`
