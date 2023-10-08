# ZMK Layout for Corne
This is the ZMK layout I use with a [Aurora Corne](https://splitkb.com/collections/keyboard-kits/products/aurora-corne). It is geared towards MacOS shortcuts, and it allows typesetting of certain accented Italian letters.

![corne image](https://github.com/danieleavitabile/zmk-config/main/corne-small-2.png?raw=true) 

## Default layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
   tab      q       w        e        r         t              y        u        i        o        p        bksp
ctrl/esc    a       s        d        f         g              h        j        k        l       ; :       ' "
  shift     z       x        c        v         b              n        m       , <      . >      / ?     shift/sv
                            cmd     lay. ↓   opt/ent         space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

ctrl/esc - mod tap: hold for ctrl, tap for esc
alt/ent  - mod tap: hold for option, tap for enter
hyper    - hyper key (ctrl+shift+opt+cmd), tap for space
opt/ent  - mod tap: hold for option, tap for enter
shft/sv  - tapdance: hold for shift, 2 taps for vim save (esc :wq), 3 taps for vimtex save and compile (esc :wq, space l l),
```

## Lower layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
   \        !       @        #        $        %               ^         &         *         (         )         bksp
mscntrl     1       2        3        4        5               -         +         `         [         ]          |
 shift      6       7        8        9        0               _         =         ~         {         }        shift/sv
                            cmd              opt/ent         space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

mscntrl - macos mission control to view windows; cmd+mscntrl shows the desktop. This button is just f3 key, brought on this layer
```

## Upper layer
```
--------+-------+--------+--------+--------+--------+      +--------+--------+--------+--------+--------+--------+     
                             è        é                                 ù        ì         ò     vol up     delete
   f1       à       f2       f3       f4       f5               ←       ↓        ↑         →     vol dn     bt clear
          f6        f7       f8       f9       f10         play/pause  prev     next             vol mut    bt next 
                            cmd              opt/ent          space              hyper
                         +--------+--------+--------+      +--------+--------+--------+

delete                    - deletes character to the right (compare with backspace that deletes to the left)
à, è, é, ì, ò, ù          - selected italian accented letters, positioned where the corresponding vowels 
                            are in the default layer (except for the repeated e)
play/pause, prev, next    - music controls
vol up, vol down, vol mut - volume controls
bt clear, bt next         - bluetooth clear and next
```
