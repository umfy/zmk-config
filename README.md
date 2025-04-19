# umfy-sweep
 
![Keyboard Image](./images/keyboard.jpg?raw=true "keyboard")

My Ferris sweep ZMK layout - fully wireless, ergonomic split keyboard.


Keyboard's design and source code: [Ferris Sweep](https://github.com/davidphilipbarr/Sweep).

Main inspirations for this layout were [getreuer's symbol layer](https://getreuer.info/posts/keyboards/symbol-layer/index.html#my-symbol-layer) and [Miryoku layout](https://github.com/manna-harbour/miryoku).

## Colemak
Backspace is positioned in top right on every layer.
This layout uses homerow mods with RALT on the first layer to allow typing non-english symbols.

```
// ------------------------------------------------------------------------------------------------------------------
// |    Q    |    W    |    F    |    P    |    B    |            |    J    |    L    |    U    |    Y    |  BSPC   |
// |    A    |    R    |    S    |    T    |    G    |            |    M    |    N    |    E    |    I    |    O    |
// |    Z    |    X    |    C    |    D    |    V    |            |    K    |    H    |    ,    |    .    |    /    |
//                               | NUM/ENT | ARR/SPC |            | ARR/TAB | SYM/ESC |
```
## Arrows
Text manipulation with the right hand on the mouse is comfortable.
```
// ------------------------------------------------------------------------------------------------------------------
// |   ESC   |   BSPC  |   DEL   |  ENTER  | CTRL Y  |            | PG UP   |   HOME  |    ⬆    |   END   |   BSPC  |
// |   TAB   |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |            | PG DN   |    ⬅    |    ⬇    |    →    |   CAPS  |
// | CTRL Z  | CTRL X  | CTRL C  | CTRL D  | CTRL V  |            |    [    |   5x ←  |    ⬇    |   5x →  |    ]    |
//                               |ARRM/ENTE|  SPACE  |            |   TAB   | NUM/ESC |
```
## Arrows mirror
Left hand optional arrows
```
// ------------------------------------------------------------------------------------------------------------------
// |  BSPC   |   HOME  |    ⬆    |   END   |  PG UP  |            | CTRL Y  |  ENTER  |   BSPC  |   DEL   |   ESC   |
// |  CAPS   |    ⬅    |    ⬇    |    →    |  PG DN  |            |  LGUI   |  LCTRL  |  LSHFT  |  LALT   |   TAB   |
// |    [    |  CTL ←  |    ⬇    |  CTL →  |    ]    |            | CTRL V  | CTRL D  | CTRL C  | CTRL X  | CTRL Z  |
//                               |         |         |            |   TAB   |   ESC   |
```
## Symbol
The most used symbols are in accessible places and many of the key posions are the same across multiple layers.
```		
// ------------------------------------------------------------------------------------------------------------------
// |    `    |    '    |    "    |    #    |    $    |            |    &    |    @    |    (    |    )    |   BSPC  |
// |    _    |    -    |    +    |    =    |    \    |            |    |    |    :    |    {    |    }    |    ?    |
// |    [    |    /    |    *    |    %    |    ]    |            |    ~    |    ;    |    <    |    >    |    !    |
//                               | SYS/ENT |  SPACE  |            | NUM/TAB |         | 
		bindings = <
```
## Number
Operators like =, +, -, *, / keep their placement just like in Symbol layer.
Enter and Escape are placed like in the Arrows layer.
[] are here because array declaration syntax in programming uses numbers in square brackets e.g. x[0]
```	
// ------------------------------------------------------------------------------------------------------------------
// |   ESC   |    .    |    ,    |   ENT   |    $    |            |    0    |    7    |    8    |    9    |   BSPC  |
// |    _    |    -    |    +    |    =    |    ^    |            |    -    |    4    |    5    |    6    |    +    |
// |    [    |    /    |    *    |    %    |    ]    |            |    /    |    1    |    2    |    3    |    *    |
//                               | FMW/ENT |ARRM/SPAC|            |  SPACE  |  SYS/0  |
```
## System
```       
// ------------------------------------------------------------------------------------------------------------------
// |   INS   |   PREV  |  PAUSE  |   NEXT  |  POWER  |            |   WWW   |   F7    |   F8    |   F9    |   F10   |
// |  PSCRN  |  LALT   |  LSHFT  |  LCTRL  |  LGUI   |            |  CALC   |   F4    |   F5    |   F6    |   F11   |
// |   MUTE  | VOL DN  |  VOL UP |  BRI UP | BRI DN  |            |  FILES  |   F1    |   F2    |   F3    |   F12   |
//                               |         | FMWARE  |            | FMWARE  |         |
```
## Firmware
Select basic keyboard layout and bluetooth options. Reset and Bootloader options for both halves of the keyboard.
```
// ------------------------------------------------------------------------------------------------------------------
// |  RESET  |GAME_ALT |         |         |         |            | OUT USB | OUT BT  |BT CLEAR |         |  RESET  |
// |  RESET  |  GAME   |  QWERTY |  COLMAK |         |            |         |  BT 3   |   BT 4  |         |  RESET  |
// |  BOOT   |         |         |         |         |            |         |  BT 0   |   BT 1  |   BT 2  |  BOOT   |
//                               |         |         |            |         |         |
```

## Qwerty
```
// ------------------------------------------------------------------------------------------------------------------
// |    Q    |    W    |    E    |    R    |    T    |            |    Y    |    U    |    I    |    O    |    P    |
// |    A    |    S    |    D    |    F    |    G    |            |    H    |    J    |    K    |    L    |    ;    |
// |    Z    |    X    |    C    |    V    |    B    |            |    N    |    M    |    ,    |    .    |    /    |
//                               | NUM/ENT | ARR/SPC |            | ARR/TAB | SYM/ESC |
```
## Gaming
League of Legends
```
// ------------------------------------------------------------------------------------------------------------------
// |   TAB   |    1    |    2    |    3    |    4    |            |    B    |    P    |    M    |    I    |   ESC   |
// |  LSHFT  |    Q    |    W    |    E    |    R    |            |    G    |    T    |    S 	|    J    |    A    |
// |  LCTRL  |    5    |    6    |    D    |    F    |            |    V    |    H    |    C    |    X    |    Z    |
//                               |  L_ALT  |  SPACE  |            |GAME_ALT | COLEMAK |
```
## Gaming alt
Tibia
```
// ------------------------------------------------------------------------------------------------------------------
// |   ESC   |    N7   |    N8   |    N9   |   F16   |            |   F13   |   F7    |   F8    |   F9    |   F10   |
// |   TAB   |    N4   |    N5   |    N6   |   F17   |            |   F14   |   F4    |   F5 	|   F6    |   F11   |
// |  ENTER  |    N1   |    N2   |    N3   |   F18   |            |   F15   |   F1    |   F2    |   F3    |   F12   |
//                               |  L_ALT  |   CTRL  |            |   GAME  |  SHIFT  |
```