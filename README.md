# Welcome to WebGIS Lab

目標: デスクトップGISのような操作性のHTML5 WebGISアプリケーション

## Requirements

次の機能が欲しい
- レイヤリストまたはレイヤツリー
    - チェックボックスで表示・非表示切り替え
    - レイヤ順の並べ替え
    - 透過性の調整と混合
    - レイヤ領域へのズーム
    - レイヤの削除
    - タッチデバイス対応
- 属性テーブル
    - 地物へのズーム
- ラスタタイル(ベース地図)の追加
- ベクトルタイルの追加
- WMTS対応
    - 20万分の1日本シームレス地質図 https://gbank.gsj.jp/seamless/
- ジオコーディング (Nominatim/国土数値情報公共施設データ等)
- ローカルのKMLファイルの読み込み (ドラッグ&ドロップで)
- 読み込まれたデータのHTML5 ローカルストレージへの保存
- プロジェクトの保存と読み込み
    - ローカルストレージとファイルダウンロード
    - 追加されたレイヤデータを含む
    - Java Scriptファイルにして初期プロジェクトとして読み込み可能に→プロジェクトの配布
        - var project = {JSON format data};
- 3Dビューアの起動 (Cesium)
    - ローカルストレージデータの共有
- 距離・面積の計測ツール
- 地理院標高タイルを用いた傾斜区分図レイヤの追加
- 地理院標高タイルを用いた地形断面図作成


## TODO

https://github.com/minorua/WebGISLab/issues/1
