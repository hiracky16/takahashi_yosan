# takahashi_yosan
高梁川流域の市町の予算比較グラフ

##使い方
1 簡易httpサーバーを走らせる
 - python2系だと`python -m SimpleHTTPServer`
 - python3軽だと`python -m http.server`

2 [ローカルホストの８０００番ポート](http://localhost:8000)へブラウザでアクセス  
3 グラフが描画される

##機能
- ソート（棒グラフをクリックすると予算額の昇順、もう一度押すと降順にソートする）
- データの切り替え（グラフの下にあるボタンをクリックすると議会費、総務費・・・と描画するグラフが変化する）

##データの引用元
* [高梁川流域圏自治体_一般会計_予算](http://catalog.dataeye.jp/dataset/33tak000001)
