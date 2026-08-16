# くるくるするやつ
## お買い物
- ポテンショメータ
  - [amazon](https://www.amazon.co.jp/dp/B0C13JZNG2?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- USB-Cブレークアウトボード
  - [amazon](https://www.amazon.co.jp/dp/B0C3V88923?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- 3ポジションスイッチ
  - [amazon](https://www.amazon.co.jp/dp/B07F6XW87H?ref=ppx_yo2ov_dt_b_fed_asin_title)
- ギアモータ
  - [amazon](https://www.amazon.co.jp/dp/B01ABHK38A?ref=ppx_yo2ov_dt_b_fed_asin_title)
- ベアリング
  - [amazon](https://www.amazon.co.jp/dp/B07NTZJG1R?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

## 組み立て方
1. 印刷する
2. 印刷物をばらしてベアリング5つを配置
   1. 土台部分の円周上に4か所縦に配置。印刷した4つの棒で軽く固定。1つは中央にある軸に配置(ぽろぽろ落ちるのでたぶんはんだごてとかで圧入したほうがいい)
3. モーターを配置して配線を左右に流したのちに歯車をモーター軸に刺す
4. ポテンショメータを頑張って刺す
5. 配線メモに従って配線

## 配線メモ
| 接続元 | 接続先 |
|---|---|
| USB-Cブレークアウトボード VBUS端子 | ポテンショメータボード Power+ |
| USB-Cブレークアウトボード GND端子 | ポテンショメータボード Power- |
|モーター -側 | 3ポジションスイッチの真ん中のどっちか |
|モーター +側|3ポジションスイッチの真ん中の-のつなげてないほう|
|3ポジションスイッチ右側と左側をたすき掛け(2か所行う)| ポテンショメータボード Motor + or -(2か所のたすき掛けにそれぞれ別端子の配線) |

