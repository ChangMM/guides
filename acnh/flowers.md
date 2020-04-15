# Flower Mechanics

## Flower Species

Flowers come in 8 different species and 9 different colors.

| Type       |                            Red                             |               Yellow                |                 White                 |                Pink                 |                 Orange                  |                 Purple                  |             Black             |                Blue                 |          Green          |
| ---------- | :--------------------------------------------------------: | :---------------------------------: | :-----------------------------------: | :---------------------------------: | :-------------------------------------: | :-------------------------------------: | :---------------------------: | :---------------------------------: | :---------------------: |
| Rose       | ![RR][RR]  									  |     ![YR][YR]     |       ![WR][WR]       |       ![PR][PR]       |       ![OR][OR]       |       ![LR][LR]       |   ![BR][BR]   |       ![UR][UR]       |            X            |
| Tulip      |                  ![RT][RT]                   |    ![YT][YT]    |      ![WT][WT]      |      ![PT][PT]      |      ![OT][OT]      |      ![LT][LT]      |  ![BT][BT]  |                  X                  |            X            |
| Pansy      |                  ![RP][RP]                   |    ![YP][YP]    |      ![WP][WP]      |                  X                  |      ![OP][OP]      |      ![LP][LP]      |               X               |      ![UP][UP]      |            X            |
| Cosmos     |                 ![RCosmos][RCosmos]                  |   ![YCosmos][YCosmos]   |     ![WCosmos][WCosmos]     |     ![PCosmos][PCosmos]     |     ![OCosmos][OCosmos]     |                    X                    | ![BCosmos][BCosmos] |                  X                  |            X            |
| Lily       |                   ![RLily][RLily]                    |     ![YLily][YLily]     |       ![WLily][WLily]       |       ![PLily][PLily]       |       ![OLily][OLily]       |                    X                    |   ![BLily][BLily]   |                  X                  |            X            |
| Hyacinth   |               ![RH][RH]                | ![YH][YH] |   ![WH][WH]   |   ![PH][PH]   |   ![OH][OH]   |   ![LH][LH]   |               X               |   ![UH][UH]   |            X            |
| Windflower |             ![RW][RW]              |                  X                  | ![WW][WW] | ![PW][PW] | ![OW][OW] | ![LW][LW] |               X               | ![UW][UW] |            X            |
| Mum        |                    ![RM][RM]                     |      ![YM][YM]      |        ![WM][WM]        |        ![PM][PM]        |                    X                    |        ![LM][LM]        |               X               |                  X                  | ![GM][GM] |

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

Each individual gene can have 3 different values. Broadly speaking, that value determines how much the flower's phenotype is impacted by the corresponding gene.

| Gene Value | Genetic Notation | Binary Notation (ACNL) | Gene Effect |
| ---------- | ---------------- | ---------------------- | ----------- |
| 0          | xx               | 00                     | None        |
| 1          | Xx               | 01                     | Low         |
| 2          | XX               | 11                     | High        |

Different ways of representing the genotype exist in the community.

It is currently unknown if the generated flag for genotype is encoded in ACNH the same way it was in ACNL. For this reason, I prefer keeping using the datamined representation of trinary digits.

Here are different representations of the Seed Red Rose.

| Data    | Binary Notation (ACNL) | Genetic Notation | Compacted Genetic Notation |
| ------- | ---------------------- | ---------------- | -------------------------- |
| 2 0 0 1 | 11 00 00 01            | RR yy ww Bb      | Rb                         |

Note that Gene 3 (White, W) is sometimes inverted in genetic notation, notably by Paleh.

### Genotypes

Roses have 81 possible genotypes, other flower species have 27.

This table shows all the 270 different possible flowers.

|  R   |  Y   |  W   |           Rose B0           |           Rose B1           |           Rose B2           |             Tulip             |             Pansy             |             Cosmos              |            Lily             |              Hyacinth               |               Windflower                |            Mum            |
| :--: | :--: | :--: | :-------------------------: | :-------------------------: | :-------------------------: | :---------------------------: | :---------------------------: | :-----------------------------: | :-------------------------: | :---------------------------------: | :-------------------------------------: | :-----------------------: |
|  0   |  0   |  0   |  ![WR][WR]  |  ![WR][WR]  |  ![WR][WR]  |  ![WT][WT]  |  ![WP][WP]  |  ![WCosmos][WCosmos]  |  ![WLily][WLily]  |  ![WH][WH]  |  ![WW][WW]  |  ![WM][WM]  |
|  0   |  0   |  1   |  ![WR][WR]  |  ![WR][WR]  |  ![WR][WR]  |  ![WT][WT]  |  ![WP][WP]  |  ![WCosmos][WCosmos]  |  ![WLily][WLily]  |  ![WH][WH]  |  ![WW][WW]  |  ![WM][WM]  |
|  0   |  0   |  2   | ![LR][LR] | ![LR][LR] | ![LR][LR] |  ![WT][WT]  |   ![UP][UP]   |  ![WCosmos][WCosmos]  |  ![WLily][WLily]  |   ![UH][UH]   |   ![UW][UW]   | ![LM][LM] |
|  0   |  1   |  0   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YCosmos][YCosmos] | ![YLily][YLily] | ![YH][YH] | ![OW][OW] | ![YM][YM] |
|  0   |  1   |  1   |  ![WR][WR]  |  ![WR][WR]  |  ![WR][WR]  | ![YT][YT] | ![YP][YP] | ![YCosmos][YCosmos] |  ![WLily][WLily]  | ![YH][YH] | ![OW][OW] | ![YM][YM] |
|  0   |  1   |  2   | ![LR][LR] | ![LR][LR] | ![LR][LR] |  ![WT][WT]  |   ![UP][UP]   |  ![WCosmos][WCosmos]  |  ![WLily][WLily]  |  ![WH][WH]  |   ![UW][UW]   |  ![WM][WM]  |
|  0   |  2   |  0   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YCosmos][YCosmos] | ![YLily][YLily] | ![YH][YH] | ![OW][OW] | ![YM][YM] |
|  0   |  2   |  1   | ![YR][YR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![YCosmos][YCosmos] | ![YLily][YLily] | ![YH][YH] | ![OW][OW] | ![YM][YM] |
|  0   |  2   |  2   |  ![WR][WR]  |  ![WR][WR]  |  ![WR][WR]  | ![YT][YT] | ![YP][YP] | ![YCosmos][YCosmos] |  ![WLily][WLily]  | ![YH][YH] | ![OW][OW] | ![YM][YM] |
|  1   |  0   |  0   |    ![RR][RR]    |   ![PR][PR]   |  ![WR][WR]  |    ![RT][RT]    |    ![RP][RP]    |   ![PCosmos][PCosmos]   |    ![RLily][RLily]    |    ![RH][RH]    |    ![RW][RW]    |   ![PM][PM]   |
|  1   |  0   |  1   |    ![RR][RR]    |   ![PR][PR]   |  ![WR][WR]  |   ![PT][PT]   |    ![RP][RP]    |   ![PCosmos][PCosmos]   |   ![PLily][PLily]   |   ![PH][PH]   |    ![RW][RW]    |   ![PM][PM]   |
|  1   |  0   |  2   |    ![RR][RR]    |   ![PR][PR]   | ![LR][LR] |  ![WT][WT]  |   ![UP][UP]   |   ![PCosmos][PCosmos]   |  ![WLily][WLily]  |  ![WH][WH]  |   ![UW][UW]   |   ![PM][PM]   |
|  1   |  1   |  0   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![OT][OT] | ![OP][OP] | ![OCosmos][OCosmos] | ![OLily][OLily] | ![OH][OH] |   ![PW][PW]   | ![YM][YM] |
|  1   |  1   |  1   |    ![RR][RR]    |   ![PR][PR]   |  ![WR][WR]  | ![YT][YT] | ![OP][OP] | ![OCosmos][OCosmos] | ![YLily][YLily] | ![YH][YH] |   ![PW][PW]   |    ![RM][RM]    |
|  1   |  1   |  2   |    ![RR][RR]    |   ![PR][PR]   | ![LR][LR] | ![YT][YT] | ![OP][OP] |   ![PCosmos][PCosmos]   | ![YLily][YLily] | ![YH][YH] |   ![PW][PW]   |   ![PM][PM]   |
|  1   |  2   |  0   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![OT][OT] | ![YP][YP] | ![OCosmos][OCosmos] | ![OLily][OLily] | ![OH][OH] | ![OW][OW] | ![LM][LM] |
|  1   |  2   |  1   | ![OR][OR] | ![YR][YR] | ![YR][YR] | ![YT][YT] | ![YP][YP] | ![OCosmos][OCosmos] | ![YLily][YLily] | ![YH][YH] | ![OW][OW] | ![LM][LM] |
|  1   |  2   |  2   |    ![RR][RR]    |   ![PR][PR]   |  ![WR][WR]  | ![YT][YT] | ![YP][YP] | ![OCosmos][OCosmos] | ![YLily][YLily] | ![YH][YH] | ![OW][OW] | ![LM][LM] |
|  2   |  0   |  0   |  ![BR][BR]  |    ![RR][RR]    |   ![PR][PR]   |  ![BT][BT]  |    ![RP][RP]    |    ![RCosmos][RCosmos]    |  ![BLily][BLily]  |    ![RH][RH]    |    ![RW][RW]    |    ![RM][RM]    |
|  2   |  0   |  1   |  ![BR][BR]  |    ![RR][RR]    |   ![PR][PR]   |    ![RT][RT]    |    ![RP][RP]    |    ![RCosmos][RCosmos]    |    ![RLily][RLily]    |    ![RH][RH]    |    ![RW][RW]    |    ![RM][RM]    |
|  2   |  0   |  2   |  ![BR][BR]  |    ![RR][RR]    |   ![PR][PR]   |    ![RT][RT]    | ![LP][LP] |    ![RCosmos][RCosmos]    |   ![PLily][PLily]   |    ![RH][RH]    | ![LW][LW] |    ![RM][RM]    |
|  2   |  1   |  0   | ![OR][OR] | ![OR][OR] | ![YR][YR] |  ![BT][BT]  |    ![RP][RP]    | ![OCosmos][OCosmos] |  ![BLily][BLily]  |   ![UH][UH]   |    ![RW][RW]    | ![LM][LM] |
|  2   |  1   |  1   |    ![RR][RR]    |    ![RR][RR]    |  ![WR][WR]  |    ![RT][RT]    |    ![RP][RP]    | ![OCosmos][OCosmos] |    ![RLily][RLily]    |    ![RH][RH]    |    ![RW][RW]    | ![LM][LM] |
|  2   |  1   |  2   |  ![BR][BR]  |    ![RR][RR]    | ![LR][LR] |    ![RT][RT]    | ![LP][LP] |    ![RCosmos][RCosmos]    |   ![PLily][PLily]   |    ![RH][RH]    | ![LW][LW] |    ![RM][RM]    |
|  2   |  2   |  0   | ![OR][OR] | ![OR][OR] | ![YR][YR] | ![LT][LT] | ![OP][OP] |  ![BCosmos][BCosmos]  | ![OLily][OLily] | ![LH][LH] |   ![PW][PW]   |  ![GM][GM]  |
|  2   |  2   |  1   | ![OR][OR] | ![OR][OR] | ![YR][YR] | ![LT][LT] | ![OP][OP] |  ![BCosmos][BCosmos]  | ![OLily][OLily] | ![LH][LH] |   ![PW][PW]   |  ![GM][GM]  |
|  2   |  2   |  2   |   ![UR][UR]   |    ![RR][RR]    |  ![WR][WR]  | ![LT][LT] | ![LP][LP] |    ![RCosmos][RCosmos]    |  ![WLily][WLily]  | ![LH][LH] | ![LW][LW] |    ![RM][RM]    |









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

[RCosmos]: https://i.imgur.com/bZOJNuX.png "Red Cosmos"
[WCosmos]: https://i.imgur.com/owY9Ipz.png "White Cosmos"
[YCosmos]: https://i.imgur.com/FW4GIKj.png "Yellow Cosmos"
[BCosmos]: https://i.imgur.com/FHppj6Z.png "Black Cosmos"
[OCosmos]: https://i.imgur.com/bQLcOFo.png "Orange Cosmos"
[PCosmos]: https://i.imgur.com/hNIl1Mu.png "Pink Cosmos"

[WLily]: https://i.imgur.com/PbIoBfx.png "White Lily"
[RLily]: https://i.imgur.com/FKRfD2m.png "Red Lily"
[YLily]: https://i.imgur.com/Pg2UA6D.png "Yellow Lily"
[PLily]: https://i.imgur.com/jfQO7hl.png "Pink Lily"
[OLily]: https://i.imgur.com/rWQgZX0.png "Orange Lily"
[BLily]: https://i.imgur.com/3YBcBum.png "Black Lily"

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