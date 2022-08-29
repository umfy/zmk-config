# umfy-sweep
 
![Keyboard Image](./images/keyboard.jpg?raw=true "keyboard")

My Ferris sweep ZMK layout - fully wireless, ergonomic split keyboard.


Keyboard's design and source code: [Ferris Sweep](https://github.com/davidphilipbarr/Sweep).

Main inspirations for this layout were [getreuer's symbol layer](https://getreuer.info/posts/keyboards/symbol-layer/index.html#my-symbol-layer) and [Miryoku layout](https://github.com/manna-harbour/miryoku).

## Colemak
Backspace is positioned in top right on every layer.
This layout uses homerow mods with lalt on the first layer to allow typing non-english symbols.

```
// ----------------------------------------------------------------------------------------------------------------------
// |    Q    |    W    |    F    |    P    |    B    |                |    J    |    L    |    U    |    Y    |  BSPC   |
// |    A    |    R    |    S    |    T    |    G    |                |    M    |    N    |    E    |    I    |    O    |
// |    Z    |    X    |    C    |    D    |    V    |                |    K    |    H    |    ,    |    .    |    /    |
//                               | NUM/ENT | ARR/SPC |                | ARR/TAB | SYM/ESC |
```
## Arrows
Text manipulation with the right hand on the mouse is comfortable.
```
// ----------------------------------------------------------------------------------------------------------------------
// |   ESC   |   BSPC  |   DEL  |  ENTER  | CTRL Y  |                | PG UP   |   HOME  |    ⬆    |   END   |   BSPC  |
// |   TAB   |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |                | PG DN   |    ⬅    |    ⬇    |    →    |   CAPS  |
// | CTRL Z  | CTRL X  | CTRL C  | CTRL D  | CTRL V  |                |    [    |  CTL ←  |    ⬇    |  CTL →  |    ]    |
//                               |  ENTER  |  SPACE  |                |   TAB   | NUM/ESC |
```
## Symbol
The most used symbols are in accessible places and many of the key posions are the same across multiple layers.
```		
// ----------------------------------------------------------------------------------------------------------------------
// |    `    |    '    |    "    |    #    |    $    |                |    &    |    %    |    (    |    )    |   BSPC  |
// |    _    |    -    |    +    |    =    |    \    |                |    |    |    :    |    {    |    }    |    ?    |
// |    [    |    /    |    *    |    ]    |    @    |                |    ~    |    ;    |    <    |    >    |    !    |
//                               | SYS/ENT |  SPACE  |                | NUM/TAB |         | 
```
## Number
Operators like =, +, -, *, / keep their placement just like in Symbol layer.
Enter and Escape are placed like in the Arrows layer.
[] are here because array declaration syntax in programming uses numbers in square brackets e.g. x[0]
```	
// ----------------------------------------------------------------------------------------------------------------------
// |   ESC   |    .    |    ,    |   ENT   |    $    |                |    0    |    7    |    8    |    9    |   BSPC  |
// |    %    |    -    |    +    |    =    |    ^    |                |    -    |    4    |    5    |    6    |    +    |
// |    [    |    /    |    *    |    ]    |    _    |                |    /    |    1    |    2    |    3    |    *    |
//                               | FMW/ENT |  SPACE  |                |  SPACE  |  SYS/0  |
```
## System
```       
// ----------------------------------------------------------------------------------------------------------------------
// |   INS   |   PREV  |  PAUSE  |   NEXT  |  TEXT   |                |   WWW   |   F7    |   F8    |   F9    |   F10   |
// |  PSCRN  |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |                |  CALC   |   F4    |   F5    |   F6    |   F11   |
// |   MUTE  | VOL DN  |  VOL UP |  BRI UP | BRI DN  |                |  FILES  |   F1    |   F2    |   F3    |   F12   |
//                               |         | FMWARE  |                | FMWARE  |         |
## Firmware
Select basic keyboard layout and bluetooth options. Reset and Bootloader options for both halves of the keyboard.
```
// ----------------------------------------------------------------------------------------------------------------------
// |  RESET  |         |         |         |         |                | OUT USB | OUT BT  |BT CLEAR |         |  RESET  |
// |  RESET  |  GAME   |  QWERTY |  COLMAK |         |                |         |  BT 3   |   BT 4  |         |  RESET  |
// |  BOOT   |         |         |         |         |                |         |  BT 0   |   BT 1  |   BT 2  |  BOOT   |
//                               |         |         |                |         |         |
```

## Qwerty
```
// ----------------------------------------------------------------------------------------------------------------------
// |    Q    |    W    |    E    |    R    |    T    |                |    Y    |    U    |    I    |    O    |    P    |
// |    A    |    S    |    D    |    F    |    G    |                |    H    |    J    |    K    |    L    |    ;    |
// |    Z    |    X    |    C    |    V    |    B    |                |    N    |    M    |    ,    |    .    |    /    |
//                               | NUM/ENT | ARR/SPC |                | ARR/TAB | SYM/ESC |
```
## Gaming
Right hand side is irrelevant
```
// ----------------------------------------------------------------------------------------------------------------------
// |   ESC   |    Q    |    W    |    E    |    R    |                |    T    |    Y    |    U    |    I    |    O    |
// |  LSHFT  |    A    |    S    |    D    |    F    |                |    G    |    H    |    J    |    K    |    L    |
// |  LCTRL  |    Z    |    X    |    C    |    V    |                |    B    |    N    |    M    |    ,    |    .    |
//                               | GAMEALT |  SPACE  |                | ARR/TAB | SYM/ESC |
```
## Gaming alt
```
// ----------------------------------------------------------------------------------------------------------------------
// |    0    |    1    |    2    |    3    |    4    |                |    5    |    6    |    7    |    8    |    9    |
// |   TAB   |    5    |    6    |    T    |    G    |                |   F5    |  COLMAK |  QWERTY |         |   F9    |
// |   ALT   |    B    |    N    |    M    |    P    |                |         |         |         |         |         |
//                               |         |  SPACE  |                |   TAB   |   ESC   |
```
