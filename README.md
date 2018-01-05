# functional-sass

Sass for functional CSS

Further to my [musings](https://artfulrobot.uk/blog/functional-css), this is a configurable
set of functional css rules. I'm trying to reduce/keep it down in size to avoid zillions of
rules that are not needed while still benefiting from the functional aproach.

Use

    @import 'vendor/functional-config';
    // Then EITHER:
    @import 'vendor/functional';
    // OR just the modules you want:
    @import 'vendor/functional-core';

## Functional classes

- `aa-{linkcol}`        Link colour set - for a link
- `ac-{linkcol}`        Link colour set - for links within a container.
- `aa`                  Different link inside ac
- `bc-{col}`            Background colour
- `bdr-[trblvha]-{col}` Set border, with colour.
- `bdrr-[1234]`         Border radius
- `bdrw-[1234]`         Border width.xxx
- `bdrs-s`              Border style solid. xxx

- `bxs-[1234]`          Box shadows
- `d(b|ib|f|n)`         Display, block, inline-block, flex, none
- `fd-col`              Flex direction column
- `fi-2`                Flex item: 50% (e.g. 2 flex columns.)
- `fi-a`                auto flex item
- `fi-ag`               auto with grow flex item
- `fi-ags`              auto with grow and shrink flex item
- `fo-[n]`              (flex) order
- `fjc-(end|start|centre|sb|sa)` flex justify-content
- `fai-(end|start|centre)` flex align-items.
- `ff-{font}`           Font Family.
- `fs-[12345678]`       Font size.
- `fsl-[12345678]`      Font size with line height pair.
- `fw-[wn]`             Flex wrap
- `h100`                height: 100%
- `lh-[12345678]`       Line height.
- `ls-none`             Remove list style
- `m[trblvh]-?[01234]`  Margin levels,  1 smallest, 4 largest. Inc. negative.
- `op-[012345]`         Opacity in 20% jumps.
- `ov-[vha]`            Overflow visible, hidden, auto
- `p[trblvh][1234]`     Padding levels, 1 smallest, 4 largest.
- `pos-[rafs]`          Position relative, absolute...
- `tc-{col}`            Text colour
- `td-off`              remove text decoration.
- `tt-(up|off)`         uppercase|none
- `txs-[1234]`          text shadows.
- `(top|bot|left|right)0` Set top: 0 etc.

Media suffixes:

- `-s`  small+
- `-m`  medium+
- `-l`  large+
- `-w`  wide+
- `-to` tiny only
- `-so` small only
- `-mo` medium only
- `-lo` large only
- `-wo` wide only

Configuration

- define a colour pallette.
- define margin/padding levels.
- define link colour sets.
- define font families.
- define font sizes heights
- define line heights
- define breakpoints.


