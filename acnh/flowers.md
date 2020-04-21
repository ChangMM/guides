# Flower Mechanics

## Flower Species

Flowers come in 8 different species and 9 different colors. Not all species are available in all colors.

| 花色       |    红    |  黄  |   白   |   粉    |  橙   |  紫   |   黑   |   蓝    |   绿   |
| ---------- | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
| 玫瑰       | ![RR][RR] | ![YR][YR] | ![WR][WR] | ![PR][PR] | ![OR][OR] | ![LR][LR] | ![BR][BR] | ![UR][UR] |    ❌    |
| 郁金香      | ![RT][RT] | ![YT][YT] | ![WT][WT] | ![PT][PT] | ![OT][OT] | ![LT][LT] | ![BT][BT] |    ❌    |    ❌    |
| 三色堇     | ![RP][RP] | ![YP][YP] | ![WP][WP] |    ❌    | ![OP][OP] | ![LP][LP] |    ❌    | ![UP][UP] |    ❌    |
| 波斯菊     | ![RC][RC] | ![YC][YC] | ![WC][WC] | ![PC][PC] | ![OC][OC] |    ❌    | ![BC][BC] |    ❌    |    ❌    |
| 百合       | ![RL][RL] | ![YL][YL] | ![WL][WL] | ![PL][PL] | ![OL][OL] |    ❌    | ![BL][BL] |    ❌    |    ❌    |
| 风信子   | ![RH][RH] | ![YH][YH] | ![WH][WH] | ![PH][PH] | ![OH][OH] | ![LH][LH] |    ❌    | ![UH][UH] |    ❌    |
| 银莲花 | ![RW][RW] |    ❌    | ![WW][WW] | ![PW][PW] | ![OW][OW] | ![LW][LW] |    ❌    | ![UW][UW] |    ❌    |
| 菊花       | ![RM][RM] | ![YM][YM] | ![WM][WM] | ![PM][PM] |    ❌    | ![LM][LM] |    ❌    |    ❌    | ![GM][GM] |

> 金玫瑰是一个特殊的例子。

## Flower Flags

Flags are hidden information attached to an item. For flowers, those flags hold various information about the flower's state, as well as its genes.

## Flower Genes

A flower's phenotype (its color) is determined by its genotype (its genes). Genes are hidden values attached to each flower. There is no way to check a flower's genes in the game.

### Genes

Genotypes are coded on 4 distinct genes. Roses use all 4 genes, while other flower species use only 3. Genes have been given an unofficial name and code in order to make communication and notation easier.

| Gene Number | Gene Name            | Genetic Code | Effect                                                       |
| ----------- | -------------------- | ------------ | ------------------------------------------------------------ |
| Gene 1      | Red                  | R            | Generally affects the flower's red color level               |
| Gene 2      | Yellow               | Y            | Generally affects the flower's yellow color level            |
| Gene 3      | White                | W            | Generally affects the flower's white color level             |
| Gene 4      | Brightness<br/>Shade | B<br>S       | Roses only<br />Generally affects the flower's red color brightness |

Each individual gene can have 3 different values. To put it simply, that value determines how the flower's phenotype is impacted by the corresponding gene.

| Gene Value | Genetic Notation | Binary Notation |
| ---------- | ---------------- | --------------- |
| `0`        | `xx`             | `00`            |
| `1`        | `Xx`             | `01`            |
| `2`        | `XX`             | `11`            |

>  Binary notation displayed here is the one used in the ACNL flower flag for genotype. It is currently unknown if it is encoded the same way in ACNH. For this reason, I prefer keeping using the datamined representation of trinary digits.

Since various ways of representing the genes exist in the community, here are different representations of the Seed Red Rose. Make sure you understand how those notations are all equivalent.

| Data      | Binary Notation (ACNL) | Genetic Notation | Compacted Genetic Notation |
| --------- | ---------------------- | ---------------- | -------------------------- |
| `2 0 0 1` | `11 00 00 01`          | `RR yy ww Bb`    | `Rb`                       |

> Note that Gene 3 (White, W) is sometimes inverted in genetic notation, notably by Paleh.

### Genotypes

Roses have 81 possible genotypes, other flower species have 27.

This table shows all the 270 different possible flowers.

|  R   |  Y   |  W   |  Rose B0  |  Rose B1  |  Rose B2  |   Tulip   |   Pansy   |  Cosmos   |   Lily    | Hyacinth  | Windflower |    Mum    |
| :--: | :--: | :--: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :--------: | :-------: |
|  0   |  0   |  0   | ![WR][WR] | ![WR][WR] | ![WR][WR] | ![WT][WT] | ![WP][WP] | ![WC][WC] | ![WL][WL] | ![WH][WH] | ![WW][WW]  | ![WM][WM] |
|  0   |  0   |  1   | ![WR][WR] | ![WR][WR] | ![WR][WR] | ![WT][WT] | ![WP][WP] | ![WC][WC] | ![WL][WL] | ![WH][WH] | ![WW][WW]  | ![WM][WM] |
|  0   |  0   |  2   | ![LR][LR] | ![LR][LR] | ![LR][LR] | ![WT][WT] | ![UP][UP] | ![WC][WC] | ![WL][WL] | ![UH][UH] | ![UW][UW]  | ![LM][LM] |
|  0   |  1   |  0   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YC][YC] | ![YL][YL] | ![YH][YH] | ![OW][OW]  | ![YM][YM] |
|  0   |  1   |  1   | ![WR][WR] | ![WR][WR] | ![WR][WR] | ![YT][YT] | ![YP][YP] | ![YC][YC] | ![WL][WL] | ![YH][YH] | ![OW][OW]  | ![YM][YM] |
|  0   |  1   |  2   | ![LR][LR] | ![LR][LR] | ![LR][LR] | ![WT][WT] | ![UP][UP] | ![WC][WC] | ![WL][WL] | ![WH][WH] | ![UW][UW]  | ![WM][WM] |
|  0   |  2   |  0   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YC][YC] | ![YL][YL] | ![YH][YH] | ![OW][OW]  | ![YM][YM] |
|  0   |  2   |  1   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YC][YC] | ![YL][YL] | ![YH][YH] | ![OW][OW]  | ![YM][YM] |
|  0   |  2   |  2   | ![WR][WR] | ![WR][WR] | ![WR][WR] | ![YT][YT] | ![YP][YP] | ![YC][YC] | ![WL][WL] | ![YH][YH] | ![OW][OW]  | ![YM][YM] |
|  1   |  0   |  0   | ![RR][RR] | ![PR][PR] | ![WR][WR] | ![RT][RT] | ![RP][RP] | ![PC][PC] | ![RL][RL] | ![RH][RH] | ![RW][RW]  | ![PM][PM] |
|  1   |  0   |  1   | ![RR][RR] | ![PR][PR] | ![WR][WR] | ![PT][PT] | ![RP][RP] | ![PC][PC] | ![PL][PL] | ![PH][PH] | ![RW][RW]  | ![PM][PM] |
|  1   |  0   |  2   | ![RR][RR] | ![PR][PR] | ![LR][LR] | ![WT][WT] | ![UP][UP] | ![PC][PC] | ![WL][WL] | ![WH][WH] | ![UW][UW]  | ![PM][PM] |
|  1   |  1   |  0   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![OT][OT] | ![OP][OP] | ![OC][OC] | ![OL][OL] | ![OH][OH] | ![PW][PW]  | ![YM][YM] |
|  1   |  1   |  1   | ![RR][RR] | ![PR][PR] | ![WR][WR] | ![YT][YT] | ![OP][OP] | ![OC][OC] | ![YL][YL] | ![YH][YH] | ![PW][PW]  | ![RM][RM] |
|  1   |  1   |  2   | ![RR][RR] | ![PR][PR] | ![LR][LR] | ![YT][YT] | ![OP][OP] | ![PC][PC] | ![YL][YL] | ![YH][YH] | ![PW][PW]  | ![PM][PM] |
|  1   |  2   |  0   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![OT][OT] | ![YP][YP] | ![OC][OC] | ![OL][OL] | ![OH][OH] | ![OW][OW]  | ![LM][LM] |
|  1   |  2   |  1   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![OC][OC] | ![YL][YL] | ![YH][YH] | ![OW][OW]  | ![LM][LM] |
|  1   |  2   |  2   | ![RR][RR] | ![PR][PR] | ![WR][WR] | ![YT][YT] | ![YP][YP] | ![OC][OC] | ![YL][YL] | ![YH][YH] | ![OW][OW]  | ![LM][LM] |
|  2   |  0   |  0   | ![BR][BR] | ![RR][RR] | ![PR][PR] | ![BT][BT] | ![RP][RP] | ![RC][RC] | ![BL][BL] | ![RH][RH] | ![RW][RW]  | ![RM][RM] |
|  2   |  0   |  1   | ![BR][BR] | ![RR][RR] | ![PR][PR] | ![RT][RT] | ![RP][RP] | ![RC][RC] | ![RL][RL] | ![RH][RH] | ![RW][RW]  | ![RM][RM] |
|  2   |  0   |  2   | ![BR][BR] | ![RR][RR] | ![PR][PR] | ![RT][RT] | ![LP][LP] | ![RC][RC] | ![PL][PL] | ![RH][RH] | ![LW][LW]  | ![RM][RM] |
|  2   |  1   |  0   | ![OR][OR] | ![OR][OR] | ![YR][YR] | ![BT][BT] | ![RP][RP] | ![OC][OC] | ![BL][BL] | ![UH][UH] | ![RW][RW]  | ![LM][LM] |
|  2   |  1   |  1   | ![RR][RR] | ![RR][RR] | ![WR][WR] | ![RT][RT] | ![RP][RP] | ![OC][OC] | ![RL][RL] | ![RH][RH] | ![RW][RW]  | ![LM][LM] |
|  2   |  1   |  2   | ![BR][BR] | ![RR][RR] | ![LR][LR] | ![RT][RT] | ![LP][LP] | ![RC][RC] | ![PL][PL] | ![RH][RH] | ![LW][LW]  | ![RM][RM] |
|  2   |  2   |  0   | ![OR][OR] | ![OR][OR] | ![YR][YR] | ![LT][LT] | ![OP][OP] | ![BC][BC] | ![OL][OL] | ![LH][LH] | ![PW][PW]  | ![GM][GM] |
|  2   |  2   |  1   | ![OR][OR] | ![OR][OR] | ![YR][YR] | ![LT][LT] | ![OP][OP] | ![BC][BC] | ![OL][OL] | ![LH][LH] | ![PW][PW]  | ![GM][GM] |
|  2   |  2   |  2   | ![UR][UR] | ![RR][RR] | ![WR][WR] | ![LT][LT] | ![LP][LP] | ![RC][RC] | ![WL][WL] | ![LH][LH] | ![LW][LW]  | ![RM][RM] |

### Breeding

Here comes the interesting part.

When two flowers breed together, the offspring's code is determined from a combination of the parent's genotypes, based of the real-life genetic principle called Mendelian inheritance. This is where genetic notation comes in handy.

To make this simple, think of every gene of the parents being cut in half, making what is called an allele. Then, one of those alleles is randomly chosen from each parent, and those two alleles combine to create the offspring's corresponding gene.

Possible outcomes for the offspring gene may be represented by a simple diagram called Punnett Square.

Imagine breeding two flowers A and B.

1. A's Gene 1 is `RR`. Its alleles for this gene are `R`and `R`.
2. B's Gene 1 is `Rr`. Its alleles for this gene are `R` and `r`.
3. Offspring's Gene 1 will take one allele from A (`R`) and one allele from B (`R` or `r`).
4. Offspring's Gene 1 will be `RR` or `Rr`

Here is the corresponding Punnett Square for Gene 1.

|      | `R`  | `R`  |
| ---- | ---- | ---- |
| `R`  | `RR` | `RR` |
| `r`  | `Rr` | `Rr` |

> Note that `rR` is always noted `Rr` since those are equivalents.

As you can see, there are four possible outcomes : two `RR` and two `Rr`. They both happen 2/4 of the time, so the odds of offspring having either one of the two are 50% each.

At the same time, the exact same thing happens with Genes 2, 3 and 4, and this is how the offspring's entire genotype is determined.

\[to be continued\]



[WR]: https://i.imgur.com/Xacr6JK.png "White Rose"
[RR]: https://i.imgur.com/WNw4bsy.png "Red Rose"
[YR]: https://i.imgur.com/syp5DZO.png "Yellow Rose"
[PR]: https://i.imgur.com/vtLJ18p.png "Pink Rose"
[OR]: https://i.imgur.com/AY4AS3v.png "Orange Rose"
[LR]: https://i.imgur.com/HRDqqUF.png "Purple Rose"
[BR]: https://i.imgur.com/YnAFSip.png "Black Rose"
[UR]: https://i.imgur.com/ShPNLUc.png "Blue Rose"

[WT]: https://i.imgur.com/icXqqff.png "White Tulip"
[RT]: https://i.imgur.com/FocWneF.png "Red Tulip"
[YT]: https://i.imgur.com/XYoBPHj.png "Yellow Tulip"
[PT]: https://i.imgur.com/BcQPAVM.png "Pink Tulip"
[OT]: https://i.imgur.com/Qe1zJRf.png "Orange Tulip"
[LT]: https://i.imgur.com/2Nn2I32.png "Purple Tulip"
[BT]: https://i.imgur.com/swxLB2t.png "Black Tulip"

[WP]: https://i.imgur.com/WbH1f0y.png "White Pansy"
[RP]: https://i.imgur.com/P87wzUX.png "Red Pansy"
[YP]: https://i.imgur.com/Brr59Np.png "Yellow Pansy"
[OP]: https://i.imgur.com/pql7Ur4.png "Orange Pansy"
[LP]: https://i.imgur.com/apel9uO.png "Purple Pansy"
[UP]: https://i.imgur.com/qstosOC.png "Blue Pansy"

[RC]: https://i.imgur.com/bZOJNuX.png "Red Cosmos"
[WC]: https://i.imgur.com/owY9Ipz.png "White Cosmos"
[YC]: https://i.imgur.com/FW4GIKj.png "Yellow Cosmos"
[BC]: https://i.imgur.com/FHppj6Z.png "Black Cosmos"
[OC]: https://i.imgur.com/bQLcOFo.png "Orange Cosmos"
[PC]: https://i.imgur.com/hNIl1Mu.png "Pink Cosmos"

[WL]: https://i.imgur.com/PbIoBfx.png "White Lily"
[RL]: https://i.imgur.com/FKRfD2m.png "Red Lily"
[YL]: https://i.imgur.com/Pg2UA6D.png "Yellow Lily"
[PL]: https://i.imgur.com/jfQO7hl.png "Pink Lily"
[OL]: https://i.imgur.com/rWQgZX0.png "Orange Lily"
[BL]: https://i.imgur.com/3YBcBum.png "Black Lily"

[RH]: https://i.imgur.com/z4Slfi6.png "Red Hyacinth"
[WH]: https://i.imgur.com/DfQ6XxZ.png "White Hyacinth"
[YH]: https://i.imgur.com/fqKtiIj.png "Yellow Hyacinth"
[LH]: https://i.imgur.com/JWy8MxJ.png "Purple Hyacinth"
[OH]: https://i.imgur.com/S8l1iXY.png "Orange Hyacinth"
[PH]: https://i.imgur.com/HbIWR5v.png "Pink Hyacinth"
[UH]: https://i.imgur.com/hAMbFoT.png "Blue Hyacinth"

[RW]: https://i.imgur.com/ZEV3HiA.png "Red Windflower"
[WW]: https://i.imgur.com/LUkHAFI.png "White Windflower"
[UW]: https://i.imgur.com/enSgApS.png "Blue Windflower"
[LW]: https://i.imgur.com/QjSnAoQ.png "Purple Windflower"
[PW]: https://i.imgur.com/sM4KZfQ.png "Pink Windflower"
[OW]: https://i.imgur.com/x6NVTdz.png "Orange Windflower"

[RM]: https://i.imgur.com/3MOgmO5.png "Red Mum"
[WM]: https://i.imgur.com/zAYqa1u.png "White Mum"
[YM]: https://i.imgur.com/jstJuSE.png "Yellow Mum"
[LM]: https://i.imgur.com/C3s80Mc.png "Purple Mum"
[PM]: https://i.imgur.com/vbu5rmI.png "Pink Mum"
[GM]: https://i.imgur.com/a9V82Ao.png "Green Mum"
