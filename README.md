# Hayabusa2♯ EDU Simulator

はやぶさ2♯（拡張ミッション）の軌道・イベントを学習用に可視化するシミュレーターです。

姉妹プロジェクト：[はやぶさ（初代）ミッションシミュレーター](https://github.com/expster/hayabusa-mission-simulator) — こちらは実際のミッション（巡航〜帰還〜再突入）の再現、本リポジトリは今後の飛行の**予測モデル**です。

## 特徴

- ケプラー軌道伝播によるアニメーション表示（フレーム単位）
- スイングバイ時のカメラ追従・ズーム、スローモーション再生
- 3D俯瞰表示（回転・傾き調整、Z軸強調トグル）
- スクラブバーによるタイムライン操作、イベントへのジャンプ、次イベントのカウントダウン表示

## 使い方

`index.html` をブラウザで開くだけで動作します（オフライン単体HTML、外部通信なし）。

```
git clone https://github.com/expster/hayabusa2-edu-simulator.git
```

またはGitHub Pagesで公開中のものをそのまま閲覧できます：
`https://expster.github.io/hayabusa2-edu-simulator/`

## 注意

本シミュレーターは教育・学習目的の予測モデルです。実際のミッション運用データとは異なる場合があります。

## ライセンス

MIT License
