# やったこと
エレベーター関連機能のテスト、実装、ホイール制御の正面方向の調整
- エレベーターのプログラムをテスト、バグ修正
- コントローラーでエレベーターを操作できるようにする(要テスト)
- エレベーターのギア半径、ギア比を調べる、エンコーダーのプログラムに反映
- プログラム内でのロボットの正面の向きの設定を修正
# 気づいたこと
- ハードの関連システムの制御をテストするコードが、ばらけてしまっている。一つの機能に対して、もっとまとまりを持って書けるようにしたい
- エレベーターを動かせる範囲の限界を超えてモータを動かすと、危ない。リミットスイッチをつけて止まるようにしたい