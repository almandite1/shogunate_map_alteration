Shogunate 地図改変サブ MOD アルファ版 Version 0.2.9 'Aonae'

[h1]※ アップロードテストのための公開なので予告なく非公開になります[/h1]
[h1]Shogunate 地図改変サブ MOD アルファ版 Version 0.2.9 'Aonae'[/h1]
====

Shogunate 地図改変サブ MOD アルファ版 Version 0.2.9 'Aonae'は Shogunate MOD のサブ MOD です。地図を高解像なものに置き換え、プロヴィンス＝男爵領を増やします。

[h2]注意[/h2]
このMODはアルファ版です。既知の問題点、未実装な機能があります。おそらくこのMODがバージョンアップすると、保存したセーブデータは使えなくなります。長期継続を目標としたゲームプレイは控えてください。
メイン MOD である Shogunate セーブデータとの互換性はありません。
地図サイズが CK3 バニラおよびメイン MOD より大きいため、より高性能なハードウェア構成が必要になるでしょう。

[h2]この MOD の説明[/h2]
[h3]地形[/h3]
現実の DEM（数値標高モデル）から新しく生成した height map をベースとし、
地図投影法として東京を中心とした正距方位図法を今のところ採用（将来変更するかもしれません）。
標高と実際の土地被覆情報を利用して地図テクスチャを描画。

[h3]プロヴィンス[/h3]
15世紀末頃の郡（ゲーム中の伯爵領に相当）毎米の生産高（石高）一万石に対して1プロヴィンスを目安として、伯爵領中のプロヴィンス数を決めましたが一部例外があります。伯爵領中のプロヴィンス数は今後変更する可能性があります。
1920年時点での日本の行政区分を組み合わせて作ったプロヴィンスの形状です。
地図の基本データである heightmap.png と provinces.png はメイン MOD の２倍 16,384 ピクセル × 4,096 ピクセルで新規作成しました。プロヴィンス数はメイン MOD の約 4 倍の 3,140 個あります（海域などを含む）。
プロヴィンス数の増加により戦略と戦術の選択肢が増え、新しいゲームプレイ体験をもたらすことでしょう！

[h3]伯爵領[/h3]
15世紀に存在した郡がゲーム中に出現するように再編し、メイン MOD に比べてz個伯爵領が増加しています。
一部の郡はプロヴィンス数が多かったり、面積が広かったりしたので近代に存在した郡のように分割しました。
京都、大阪、奈良、堺といった町は独立した伯爵領として設定しました。

[h3]既知の問題と未実装[/h3]
[list]
[*] メイン MOD には存在していた渡河可能な河川、渡河不可能な河川が存在しない。
[*] 特別なマップオブジェクトが存在しない。
[*] 一部プロヴィンスが分離して存在している。
[*] サラウンドマップが存在しない
[*] 男爵領タイトル名や伯爵領タイトル名のランゲージデータが未設定のものがある。
[*] 男爵領タイトル名や伯爵領タイトル名の歴史的に正確な名称が未設定のものがある。
[*] 小さすぎるプロヴィンス
[*] タイトルと連動していないプロヴィンスがある
[*] 湖にマップオブジェクトが設置されておらず干上がっている。
[*] 航海不能な湖より海にしたほうが良い湖プロヴィンスがある。
[*] 男爵領タイトルの名前後置子が重複する。
[*] ロケーターがない、ロケーターの位置が重複している。
[*] 新しく追加した伯爵領歴史データは連接する既存歴史データをコピーしただけのものです。
[*] Shogunate MOD にある男爵領タイトル名歴史データは反映されません。
[*] 地図に表示される地面テクスチャは史実とは異なります。
[*] 男爵領タイトル名を 12 世紀基準で調査・設定しているため有効なブックマークの数をメイン MOD から暫定的に削減しています。
[/list]

[h2]動作条件[/h2]
[list]
[*] [url=https://store.steampowered.com/app/1158310]Crusader Kings III[/url]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2253278582]Shogunate MOD[/url]
[/list]

[h2]クレジット[/h2]
[h3]gfx / map / terrain / *.*[/h3]
[list]
[*][url=https://globalmaps.github.io/glcnmo.html]Land Cover (GLCNMO) - Global version[/url] / Geospatial Information Authority of Japan, Chiba University and collaborating organizations.
[/list]
[h3]history / *.* ほか[/h3]
Shogunate MOD を一部改変
[h3]map_data / heightmap.png[/h3]
[list]
[*][url=https://globalmaps.github.io/el.html]Elevation - Global version[/url] / Geospatial Information Authority of Japan.
[/list]
[h3]map_data / rivers.png[/h3]
[list]
[*][url=https://osmdata.openstreetmap.de]Land polygons - Data Derived from OpenStreetMap for Download[/url] / The OpenStreetMap project
[*][url=https://nlftp.mlit.go.jp/ksj]「国土数値情報（湖沼データ）」（国土交通省）[/url]を加工して作成
[*][url=https://nlftp.mlit.go.jp/ksj]「国土数値情報（河川データ）」（国土交通省）[/url]を加工して作成
[/list]
[h3]map_data / provinces.png[/h3]
[list]
[*][url=https://nlftp.mlit.go.jp/ksj]「国土数値情報（行政区域データ）」（国土交通省）[/url]を加工して作成
[/list]

[h3]thumbnail.png[/h3]
[list]
[*]© Kanenori, [url=https://pixabay.com/ja/users/kanenori-4749850/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2297961]Plz do not use photos showing people for commercial uses.[/url]による[url=https://pixabay.com/ja/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2297961]Pixabay[/url]からの画像
[/list]
