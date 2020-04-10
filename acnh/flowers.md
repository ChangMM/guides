# Flower Heredity in ACNH

## Genes

Genes are hidden values attached to each flower, which determine their actual color.

### Gene Types

Four different genes exist. Roses use all four, while other flower types use only three.

| Gene Code | Gene Name  | Details                                                      |
| --------- | ---------- | ------------------------------------------------------------ |
| Rr        | Red        | Reflects the flower's red coloration level                   |
| Yy        | Yellow     | Reflects the flower's yellow coloration level                |
| Ww        | White      | Reflects the flower's white coloration level                 |
| Bb        | Brightness | Roses only<br />Reflects the flower's red coloration brightness |

### Gene Values

Each individual gene can have 3 different values.

| Genetic Value | Numeric Value | Gene Effect |
| ------------- | ------------- | ----------- |
| xx            | 0             | None        |
| Xx            | 1             | Low         |
| XX            | 2             | High        |

### Gene Combinations

Thus we have 81 different combinations for Roses, and 27 different combinations for other flower types.

|  R   |  Y   |  W   |            Rose             |            Rose             |            Rose             |             Tulip             |             Pansy             |             Cosmos              |            Lily             |              Hyacinth               |               Windflower                |            Mum            |
| :--: | :--: | :--: | :-------------------------: | :-------------------------: | :-------------------------: | :---------------------------: | :---------------------------: | :-----------------------------: | :-------------------------: | :---------------------------------: | :-------------------------------------: | :-----------------------: |
|  0   |  0   |  0   |  ![White Rose][White Rose]{:height="36px" width="36px"}  |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  |  ![White Tulip][White Tulip]  |  ![White Pansy][White Pansy]  |  ![White Cosmos][White Cosmos]  |  ![White Lily][White Lily]  |  ![White Hyacinth][White Hyacinth]  |  ![White Windflower][White Windflower]  |  ![White Mum][White Mum]  |
|  0   |  0   |  1   |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  |  ![White Tulip][White Tulip]  |  ![White Pansy][White Pansy]  |  ![White Cosmos][White Cosmos]  |  ![White Lily][White Lily]  |  ![White Hyacinth][White Hyacinth]  |  ![White Windflower][White Windflower]  |  ![White Mum][White Mum]  |
|  0   |  0   |  2   | ![Purple Rose][Purple Rose] | ![Purple Rose][Purple Rose] | ![Purple Rose][Purple Rose] |  ![White Tulip][White Tulip]  |   ![Blue Pansy][Blue Pansy]   |  ![White Cosmos][White Cosmos]  |  ![White Lily][White Lily]  |   ![Blue Hyacinth][Blue Hyacinth]   |   ![Blue Windflower][Blue Windflower]   | ![Purple Mum][Purple Mum] |
|  0   |  1   |  0   | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Yellow Cosmos][Yellow Cosmos] |  ![White Lily][White Lily]  | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Yellow Mum][Yellow Mum] |
|  0   |  1   |  1   |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Yellow Cosmos][Yellow Cosmos] |  ![White Lily][White Lily]  | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Yellow Mum][Yellow Mum] |
|  0   |  1   |  2   | ![Purple Rose][Purple Rose] | ![Purple Rose][Purple Rose] | ![Purple Rose][Purple Rose] |  ![White Tulip][White Tulip]  |   ![Blue Pansy][Blue Pansy]   |  ![White Cosmos][White Cosmos]  |  ![White Lily][White Lily]  |  ![White Hyacinth][White Hyacinth]  |   ![Blue Windflower][Blue Windflower]   |  ![White Mum][White Mum]  |
|  0   |  2   |  0   | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Yellow Cosmos][Yellow Cosmos] | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Yellow Mum][Yellow Mum] |
|  0   |  2   |  1   | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Yellow Cosmos][Yellow Cosmos] | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Yellow Mum][Yellow Mum] |
|  0   |  2   |  2   |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  |  ![White Rose][White Rose]  | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Yellow Cosmos][Yellow Cosmos] |  ![White Lily][White Lily]  | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Yellow Mum][Yellow Mum] |
|  1   |  0   |  0   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |  ![White Rose][White Rose]  |    ![Red Tulip][Red Tulip]    |    ![Red Pansy][Red Pansy]    |   ![Pink Cosmos][Pink Cosmos]   |    ![Red Lily][Red Lily]    |    ![Red Hyacinth][Red Hyacinth]    |    ![Red Windflower][Red Windflower]    |   ![Pink Mum][Pink Mum]   |
|  1   |  0   |  1   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |  ![White Rose][White Rose]  |   ![Pink Tulip][Pink Tulip]   |    ![Red Pansy][Red Pansy]    |   ![Pink Cosmos][Pink Cosmos]   |   ![Pink Lily][Pink Lily]   |   ![Pink Hyacinth][Pink Hyacinth]   |    ![Red Windflower][Red Windflower]    |   ![Pink Mum][Pink Mum]   |
|  1   |  0   |  2   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   | ![Purple Rose][Purple Rose] |  ![White Tulip][White Tulip]  |   ![Blue Pansy][Blue Pansy]   |   ![Pink Cosmos][Pink Cosmos]   |  ![White Lily][White Lily]  |  ![White Hyacinth][White Hyacinth]  |   ![Blue Windflower][Blue Windflower]   |   ![Pink Mum][Pink Mum]   |
|  1   |  1   |  0   | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Orange Tulip][Orange Tulip] | ![Orange Pansy][Orange Pansy] | ![Orange Cosmos][Orange Cosmos] | ![Orange Lily][Orange Lily] | ![Orange Hyacinth][Orange Hyacinth] |   ![Pink Windflower][Pink Windflower]   | ![Yellow Mum][Yellow Mum] |
|  1   |  1   |  1   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |  ![White Rose][White Rose]  | ![Yellow Tulip][Yellow Tulip] | ![Orange Pansy][Orange Pansy] | ![Orange Cosmos][Orange Cosmos] | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] |   ![Pink Windflower][Pink Windflower]   |    ![Red Mum][Red Mum]    |
|  1   |  1   |  2   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   | ![Purple Rose][Purple Rose] | ![Yellow Tulip][Yellow Tulip] | ![Orange Pansy][Orange Pansy] |   ![Pink Cosmos][Pink Cosmos]   | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] |   ![Pink Windflower][Pink Windflower]   |   ![Pink Mum][Pink Mum]   |
|  1   |  2   |  0   | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Orange Tulip][Orange Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Orange Cosmos][Orange Cosmos] | ![Orange Lily][Orange Lily] | ![Orange Hyacinth][Orange Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Purple Mum][Purple Mum] |
|  1   |  2   |  1   | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Rose][Yellow Rose] | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Orange Cosmos][Orange Cosmos] | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Purple Mum][Purple Mum] |
|  1   |  2   |  2   |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |  ![White Rose][White Rose]  | ![Yellow Tulip][Yellow Tulip] | ![Yellow Pansy][Yellow Pansy] | ![Orange Cosmos][Orange Cosmos] | ![Yellow Lily][Yellow Lily] | ![Yellow Hyacinth][Yellow Hyacinth] | ![Orange Windflower][Orange Windflower] | ![Purple Mum][Purple Mum] |
|  2   |  0   |  0   |  ![Black Rose][Black Rose]  |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |  ![Black Tulip][Black Tulip]  |    ![Red Pansy][Red Pansy]    |    ![Red Cosmos][Red Cosmos]    |  ![Black Lily][Black Lily]  |    ![Red Hyacinth][Red Hyacinth]    |    ![Red Windflower][Red Windflower]    |    ![Red Mum][Red Mum]    |
|  2   |  0   |  1   |  ![Black Rose][Black Rose]  |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |    ![Red Tulip][Red Tulip]    |    ![Red Pansy][Red Pansy]    |    ![Red Cosmos][Red Cosmos]    |    ![Red Lily][Red Lily]    |    ![Red Hyacinth][Red Hyacinth]    |    ![Red Windflower][Red Windflower]    |    ![Red Mum][Red Mum]    |
|  2   |  0   |  2   |  ![Black Rose][Black Rose]  |    ![Red Rose][Red Rose]    |   ![Pink Rose][Pink Rose]   |    ![Red Tulip][Red Tulip]    | ![Purple Pansy][Purple Pansy] |    ![Red Cosmos][Red Cosmos]    |   ![Pink Lily][Pink Lily]   |    ![Red Hyacinth][Red Hyacinth]    | ![Purple Windflower][Purple Windflower] |    ![Red Mum][Red Mum]    |
|  2   |  1   |  0   | ![Orange Rose][Orange Rose] | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] |  ![Black Tulip][Black Tulip]  |    ![Red Pansy][Red Pansy]    | ![Orange Cosmos][Orange Cosmos] |  ![Black Lily][Black Lily]  |   ![Blue Hyacinth][Blue Hyacinth]   |    ![Red Windflower][Red Windflower]    | ![Purple Mum][Purple Mum] |
|  2   |  1   |  1   |    ![Red Rose][Red Rose]    |    ![Red Rose][Red Rose]    |  ![White Rose][White Rose]  |    ![Red Tulip][Red Tulip]    |    ![Red Pansy][Red Pansy]    | ![Orange Cosmos][Orange Cosmos] |    ![Red Lily][Red Lily]    |    ![Red Hyacinth][Red Hyacinth]    |    ![Red Windflower][Red Windflower]    | ![Purple Mum][Purple Mum] |
|  2   |  1   |  2   |  ![Black Rose][Black Rose]  |    ![Red Rose][Red Rose]    | ![Purple Rose][Purple Rose] |    ![Red Tulip][Red Tulip]    | ![Purple Pansy][Purple Pansy] |    ![Red Cosmos][Red Cosmos]    |   ![Pink Lily][Pink Lily]   |    ![Red Hyacinth][Red Hyacinth]    | ![Purple Windflower][Purple Windflower] |    ![Red Mum][Red Mum]    |
|  2   |  2   |  0   | ![Orange Rose][Orange Rose] | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] | ![Purple Tulip][Purple Tulip] | ![Orange Pansy][Orange Pansy] |  ![Black Cosmos][Black Cosmos]  | ![Orange Lily][Orange Lily] | ![Purple Hyacinth][Purple Hyacinth] |   ![Pink Windflower][Pink Windflower]   |  ![Green Mum][Green Mum]  |
|  2   |  2   |  1   | ![Orange Rose][Orange Rose] | ![Orange Rose][Orange Rose] | ![Yellow Rose][Yellow Rose] | ![Purple Tulip][Purple Tulip] | ![Orange Pansy][Orange Pansy] |  ![Black Cosmos][Black Cosmos]  | ![Orange Lily][Orange Lily] | ![Purple Hyacinth][Purple Hyacinth] |   ![Pink Windflower][Pink Windflower]   |  ![Green Mum][Green Mum]  |
|  2   |  2   |  2   |   ![Blue Rose][Blue Rose]   |    ![Red Rose][Red Rose]    |  ![White Rose][White Rose]  | ![Purple Tulip][Purple Tulip] | ![Purple Pansy][Purple Pansy] |    ![Red Cosmos][Red Cosmos]    |  ![White Lily][White Lily]  | ![Purple Hyacinth][Purple Hyacinth] | ![Purple Windflower][Purple Windflower] |    ![Red Mum][Red Mum]    |

[White Rose]: https://i.imgur.com/Xacr6JK.png
[Red Rose]: https://i.imgur.com/WNw4bsy.png
[Yellow Rose]: https://i.imgur.com/syp5DZO.png
[Pink Rose]: https://i.imgur.com/vtLJ18p.png
[Orange Rose]: https://i.imgur.com/AY4AS3v.png
[Purple Rose]: https://i.imgur.com/HRDqqUF.png
[Black Rose]: https://i.imgur.com/YnAFSip.png
[Blue Rose]: https://i.imgur.com/ShPNLUc.png

[White Tulip]: https://i.imgur.com/icXqqff.png
[Red Tulip]: https://i.imgur.com/FocWneF.png
[Yellow Tulip]: https://i.imgur.com/XYoBPHj.png
[Pink Tulip]: https://i.imgur.com/BcQPAVM.png
[Orange Tulip]: https://i.imgur.com/Qe1zJRf.png
[Purple Tulip]: https://i.imgur.com/2Nn2I32.png
[Black Tulip]: https://i.imgur.com/swxLB2t.png

[White Pansy]: https://i.imgur.com/WbH1f0y.png
[Red Pansy]: https://i.imgur.com/P87wzUX.png
[Yellow Pansy]: https://i.imgur.com/Brr59Np.png
[Orange Pansy]: https://i.imgur.com/pql7Ur4.png
[Purple Pansy]: https://i.imgur.com/apel9uO.png
[Blue Pansy]: https://i.imgur.com/qstosOC.png

[Red Cosmos]: https://i.imgur.com/bZOJNuX.png
[White Cosmos]: https://i.imgur.com/owY9Ipz.png
[Yellow Cosmos]: https://i.imgur.com/FW4GIKj.png
[Black Cosmos]: https://i.imgur.com/FHppj6Z.png
[Orange Cosmos]: https://i.imgur.com/bQLcOFo.png
[Pink Cosmos]: https://i.imgur.com/hNIl1Mu.png

[White Lily]: https://i.imgur.com/PbIoBfx.png
[Red Lily]: https://i.imgur.com/FKRfD2m.png
[Yellow Lily]: https://i.imgur.com/Pg2UA6D.png
[Pink Lily]: https://i.imgur.com/jfQO7hl.png
[Orange Lily]: https://i.imgur.com/rWQgZX0.png
[Black Lily]: https://i.imgur.com/3YBcBum.png

[Red Hyacinth]: https://i.imgur.com/z4Slfi6.png
[White Hyacinth]: https://i.imgur.com/DfQ6XxZ.png
[Yellow Hyacinth]: https://i.imgur.com/fqKtiIj.png
[Purple Hyacinth]: https://i.imgur.com/JWy8MxJ.png
[Orange Hyacinth]: https://i.imgur.com/S8l1iXY.png
[Pink Hyacinth]: https://i.imgur.com/HbIWR5v.png
[Blue Hyacinth]: https://i.imgur.com/hAMbFoT.png

[Red Windflower]: https://i.imgur.com/ZEV3HiA.png
[White Windflower]: https://i.imgur.com/LUkHAFI.png
[Blue Windflower]: https://i.imgur.com/enSgApS.png
[Purple Windflower]: https://i.imgur.com/QjSnAoQ.png
[Pink Windflower]: https://i.imgur.com/sM4KZfQ.png
[Orange Windflower]: https://i.imgur.com/x6NVTdz.png

[Red Mum]: https://i.imgur.com/3MOgmO5.png
[White Mum]: https://i.imgur.com/zAYqa1u.png
[Yellow Mum]: https://i.imgur.com/jstJuSE.png
[Purple Mum]: https://i.imgur.com/C3s80Mc.png
[Pink Mum]: https://i.imgur.com/vbu5rmI.png
[Green Mum]: https://i.imgur.com/a9V82Ao.png