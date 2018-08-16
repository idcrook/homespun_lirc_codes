# Sony RM-AAU190

The RM-AAU190 comes bundled with STR-DH550 and STR-DH750.

## Codes - RM-AAU190

Used excellent Arduino-based [IRremote](https://github.com/z3t0/Arduino-IRremote) to decode.

All the codes are either 15-bit Sony or 20-bit Sony codes. Since LIRC has a protocol limitation of one encoding per remote "conf", the values need to be split among two remote definitions.


```
SLEEP       0x030C (15 bits)
POWER       0x540C (15 bits)
BD/DVD      0x68114 (20 bits)
SAT/CATV    0x600D (15 bits)
GAME        0x1F0C (15 bits)
SA-CD/CD    0x520C (15 bits)
VIDEO       0x220C (15 bits)
TV          0x2B0C (15 bits)
FM          0x0C0C (15 bits)
AM          0x2C0C (15 bits)
USB         0xE8114 (20 bits)

iPhone CTRL 0x4E110 (20 bits)
REPEAT      0x34110 (20 bits)
SHUFFLE     0x54110 (20 bits)
A.F.D./2CH  0x710D (15 bits)
MOVIE       0x610D (15 bits)
MUSIC       0x490D (15 bits)

DISPLAY     0x690C (15 bits)
AMP MENU    0x770D (15 bits)
RETURN      0xBE110 (20 bits)
OPTIONS     0xCE110 (20 bits)
UP          0x0F0D (15 bits)
RIGHT       0x6F0D (15 bits)
DOWN        0x4F0D (15 bits)
LEFT        0x2F0D (15 bits)
SELECT      0x180C (15 bits)

HOME                      0x650C (15 bits)
PRESET DOWN Skip Forward  0x0C110 (20 bits)
PLAY PAUSE                0x5C110 (20 bits)
PRESET UP Skip Reverse    0x8C110 (20 bits)
STOP                      0x1C110 (20 bits)

MUTE        0x140C (15 bits)
VOLUME UP   0x240C (15 bits)
VOLUME DOWN 0x640C (15 bits)
```
