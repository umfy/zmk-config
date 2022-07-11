# umfy-sweep

My Ferris sweep ZMK layout
![Keyboard Image](./images/keyboard.jpg?raw=true "keyboard")

Keyboard's design and source code: [Ferris Sweep](https://github.com/davidphilipbarr/Sweep).

Main inspirations for this layout were [getreuer's symbol layer](https://getreuer.info/posts/keyboards/symbol-layer/index.html#my-symbol-layer) and [Miryoku layout](https://github.com/manna-harbour/miryoku).

## Colemak
Backspace is positioned in top right on every layer.

```
// ----------------------------------------------------------------------------------------------------------------------
// |    Q    |    W    |    F    |    P    |    B    |                |    J    |    L    |    U    |    Y    |  BSPC   |
// |    A    |    R    |    S    |    T    |    G    |                |    M    |    N    |    E    |    I    |    O    |
// |    Z    |    X    |    C    |    D    |    V    |                |    K    |    H    |    ,    |    .    |    /    |
//                               | NUM/ENT | ARR/SPC |                | ARR/TAB | SYM/ESC |
```
## Arrows
Ins can be swapped with any key that makes sense here.

Ctrl + Shift + Del and text manipulation with the right hand on the mouse are possible.
```
// ----------------------------------------------------------------------------------------------------------------------
// |   ESC   |   DEL   |   BSPC  |  ENTER  | CTRL Y  |                | PG UP   |   HOME  |    ⬆    |   END   |   BSPC  |
// |   TAB   |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |                | PG DN   |    ⬅    |    ⬇    |    →    |   INS   |
// | CTRL Z  | CTRL X  | CTRL C  | CTRL D  | CTRL V  |                |    [    |  CTL ←  |    ⬇    |  CTL →  |    ]    |
//                               |  ENTER  |  SPACE  |                |   TAB   | NUM/ESC |
```
## Symbol
The most used symbols are in accessible places and many of the key posions are the same across multiple layers.
```		
// ----------------------------------------------------------------------------------------------------------------------
// |    `    |    "    |    '    |    #    |    $    |                |    &    |    %    |    {    |    }    |   BSPC  |
// |    _    |    -    |    +    |    =    |    \    |                |    |    |    :    |    (    |    )    |    ?    |
// |    [    |    /    |    *    |    ]    |    @    |                |    ~    |    ;    |    <    |    >    |    !    |
//                               | SYS/ENT |  SPACE  |                | NUM/TAB |         | 
```
## Number
Operators like =, +, -, *, / keep their placement just like in Symbol layer.
Enter and Escape are placed like in the Arrows layer.
[] are here because array declaration syntax in programming uses numbers in square brackets e.g. x[0]
```	
// ----------------------------------------------------------------------------------------------------------------------
// |   ESC   |    ,    |    .    |   ENT   |    $    |                |    0    |    7    |    8    |    9    |   BSPC  |
// |    %    |    -    |    +    |    =    |    ^    |                |    -    |    4    |    5    |    6    |    +    |
// |    [    |    /    |    *    |    ]    |    _    |                |    /    |    1    |    2    |    3    |    *    |
//                               | FMW/ENT |  SPACE  |                |  SPACE  | SYS/0 |
```
## System
```       
// // ----------------------------------------------------------------------------------------------------------------------
// |         |   PREV  |  PAUSE  |   NEXT  |         |                |         |   F7    |   F8    |   F9    |   F10   |
// |  PSCRN  |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |                |         |   F4    |   F5    |   F6    |   F11   |
// |   MUTE  | VOL DN  |  VOL UP |  BRI UP | BRI DN  |                |         |   F1    |   F2    |   F3    |   F12   |
//                               |         | FMWARE  |                | FMWARE  |         |
```
## Firmware
Select basic keyboard layout and bluetooth options. Reset and Bootloader options for both halves of the keyboard.
```
// ----------------------------------------------------------------------------------------------------------------------
// |  RESET  |         |         |         |         |                |         | BT PREV |BT CLEAR | BT NEXT |  RESET  |
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
// 
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
