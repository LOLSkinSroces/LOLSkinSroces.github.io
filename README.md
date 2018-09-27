# LOL Skin Sroces
A table that attempts to compare and describe the effects of a `skin` by `scoring`.

## Why make it?
There are `874` skins in the `League of Legends` until Patch `8.19`.

To classify skin's tier or quality or effects,
- Riot use the `Ultimate`, `Legendary`, `Epic` and other Tags to classify,
- or use the `T1`, `T2`, `T3` and other Tier Levels to classify in china region.

But they all use one `word` to classify. It's not always exact enough, or has different tag in different regions. There some cases:
- Legendary Skin `High Noon Lucian` has new animations, Legendary Skin `Corporate Mundo` does not.
- `Blood Moon Akali` is `Legendary` Skin in China, but nothing in Global.

## How to resolve?
**word** :x: **score** :heavy_check_mark:

**Use a `score` instead of a `word`.**

`score` can not fully describe the level of the skin, but will intuitively show the difference of skin.

## Score Rule (W.I.P.)
There are `3` kinds of meansure in the plan:

- **Public Score**, `PBS`
  - The score based public items owned by all champion.
  - e.g. VFX, SFX, animations of `PQWER` Skill.

- **Private Score**, `PRS`
  - The score based private items only owned by his champion.
  - e.g. `Lucian`'s `W` Skill has two little item by cross and speed up buff.

- **Absolutely Champion Percentage** (TBD), `ACP`
  - The percentage means how high quality is in all his champion's skin.
  - e.g. A Champions has 4 skins.
    - The `PRS`s are `20`, `40`, `50`, `60`.
    - The average value is `42`.
    - Skin C's ACP is `(50 / 42) * 100% = 119%`.
    - Skin D's ACP is `(60 / 42) * 100% = 142%`.
	- Skin D should has higher quality than Skin C, D's ACP > C's ACP.
  - **I'm not sure it is correct or not. Help me improve please!**

- **Scoring**
  - all calculation is `plus`, no `minus`;
  - the Maximun `Public Score` is `(WIP)`;
  - the Maximun `Private Score` is depending on the count of his champion items;
  - `PBS` and `PRS` are independent of each other. `PRS` can be larger then `PBS`;
    - e.g. one `W` Skill VFX item is `10` points in public item,
    - `Lucian`'s `W` VFX in private has two item that the cross is `10` and the speed up buff `5`. Total is `15`.

- **Roadmap**
  - More