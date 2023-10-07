# ZMK Layout for Corne
This is the ZMK layout I use with a [Aurora Corne](https://splitkb.com/collections/keyboard-kits/products/aurora-corne). It is geared towards MacOS shortcuts, and it allows typesetting of certain accented Italian letters.


## Default layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
   tab      q       w        e        r         t              y        u        i        o        p        bksp
ctrl/esc    a       s        d        f         g              h        j        k        l       ; :       ' "
  shift     z       x        c        v         b              n        m       , <      . >      / ?     shift/sv
                            cmd     lay. ↓   opt/ent        hyp/spc   lay. ↑    opt
                         +--------+--------+--------+      +--------+--------+--------+

ctrl/esc - mod tap: hold for ctrl, tap for esc
alt/ent  - mod tap: hold for option, tap for enter
hyp/spc  - mod tap: hold for hyper (ctrl+shift+opt+cmd), tap for space
shft/sv  - tapdance: hold for shift, 2 taps for vim save (esc :wq), 3 taps for vimtex save and compile (esc :wq, space l l),
```

## Lower layer
```
//---------+---------+---------+---------+---------+---------+    +---------+---------+---------+---------+---------+---------+     
//    \         !        @         #         $         %               ^         &         *         (         )         bksp
//   f3         1        2         3         4         5               -         +         `         [         ]          |
//  lshift      6        7         8         9         0               _         =         ~         {         }       rshift
//                                cmd               lalt/enter       space      bksp     
//                             +---------+---------+---------+    +---------+---------+---------+
// In this layer f3 is repeated. It is also present, with all oter function keys, in the next layer, because f3 and Cmd+f3 are
// associated to macos shortcuts to exposé and clear the destkop.
-------------------------------------     --------------------------------------
| TAB |  1  |  2  |  3  |  4  |  5  |     |  6  |  7  |  8  |  9  |  0  |  `  |
| CTRL|     |     |     |     |     |     |     |     |     |     |     |     |
| SHFT| BT1 | BT1 | BT3 | BT4 |BTCLR|     |     |     |     |     |     | SHFT|
                  | GUI |✖LWR✖| SPC |     | RET | RSE | BKSP|
```

## Raise layer
```
//---------+---------+---------+---------+---------+---------+    +---------+---------+---------+---------+---------+---------+     
//                                  è         é                                 ù         ì         ò       vol up     bksp
//   f1        à         f2        f3        f4      f5               ←         ↓         ↑         →       vol dn     bt clear
//             f6        f7        f8        f9      f10           play/pause  prev     next                vol mut    bt next 
//                             
//                             +---------+---------+---------+    +---------+---------+---------+
-------------------------------------     -------------------------------------
| TAB |     |     |     |     |     |     |  ⧉  |  ⧈  | PLAY| VDWN| VUP | LOCK|
| CTRL|     |     |     |     |     |     |  ←  |  ↓  |  ↑  |  →  |  [  |  ]  |
| SHFT|     |     |     |     |     |     |  +  |  -  |  =  |  *  |  \  | '|' |
                  | GUI | LWR | SPC |     | RET |✖RSE✖| BKSP|

⧉ - ctrl + ↑ (Mac mission control)
⧈ - ctrl + shift + gui + 4 (Mac capture a portion of the screen)
PLAY - tap once for play / pause, twice for next track, three times for previous track
VDWN - tap volume down, hold mute
LOCK - tap once for lock, twice to sleep
```
