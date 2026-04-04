# マスターズ甲子園 大会資料アーカイブ

[横浜市立南高校 野球部OB会サイト](https://minami-baseball-ob.vercel.app/masters)で使用する大会資料（PDF）の永続ストレージ。

## 構成

年度ごとのフォルダに大会要項・取り決め事項等を保存。

```
2025/
  _マスターズ甲子園2025_神奈川県大会トーナメント表.pdf
  _マスターズ甲子園神奈川県大会_大会要項.pdf
  _上部大会への出場チーム_取り決め事項.pdf
  _神奈川県大会_取り決め事項.pdf
```

## アップロード方法

OB会サイトの編集画面（[/edit/masters](https://minami-baseball-ob.vercel.app/edit/masters)）からアップロードすると、GitHub Contents API経由でこのリポジトリに自動保存されます。

## 関連リポジトリ

- [minami-baseball-ob](https://github.com/yasumorishima/minami-baseball-ob)（private） — OB会サイト本体
- [minami-baseball-ob-docs](https://github.com/yasumorishima/minami-baseball-ob-docs) — 技術解説
- [issue-images](https://github.com/yasumorishima/issue-images) — フィードバック画像ストレージ
