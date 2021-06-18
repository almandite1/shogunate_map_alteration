[h1]※ アップロードテストのための公開なので予告なく非公開になります[/h1]
[h1]Shogunate 地図改変サブ MOD 日本語 アルファ版 Version 0.4.7 'Atoiya'[/h1]
====

Shogunate 地図改変サブ MOD アルファ版は [url=https://steamcommunity.com/workshop/filedetails/?id=2253279956]Shogunate MOD [/url]のサブ MOD です。地図を高解像なものに置き換え、プロヴィンス＝男爵領を増やします。
英語版は[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2391487224]こちら[/url]からサブスクライブできます。

[h2]注意[/h2]
このMODはアルファ版です。既知の問題点、未実装な機能があります。おそらくこのMODがバージョンアップすると、保存したセーブデータは使えなくなります。長期継続を目標としたゲームプレイは控えてください。
メイン MOD である Shogunate セーブデータとの互換性はありません。
地図サイズが CK3 バニラおよびメイン MOD より大きいため、より高性能なハードウェア構成が必要になるでしょう。

[h2]この MOD の説明[/h2]
[h3]地形[/h3]
現実の DEM（数値標高モデル）から新しく生成した height map をベースとし、
地図投影法として東京を中心とした正距方位図法を今のところ採用しています。
標高と実際の土地被覆情報を利用して基本的な地図テクスチャを描画しました。

[h3]プロヴィンス[/h3]
15世紀末頃の郡（ゲーム中の伯爵領に相当）ごとの米の生産高（石高）一万石に対して1プロヴィンスを目安として、伯爵領中のプロヴィンス数を決めましたが一部例外があります。伯爵領中のプロヴィンス数は今後変更する可能性があります。
プロヴィンスの形状は1920年時点での日本の行政区分を組み合わせて作りました。
地図の基本データである heightmap.png と provinces.png はメイン MOD の２倍の面積 16,384 ピクセル × 4,096 ピクセルで新規作成しました。プロヴィンス数はメイン MOD の約 4 倍の 3,140 個あります（海域などを含む）。
プロヴィンス数の増加により戦略と戦術の選択肢が増え、新しいゲームプレイ体験をもたらすことでしょう！

[h3]伯爵領[/h3]
15世紀に存在した郡がゲーム中に伯爵領として出現するように再編し、メイン MOD に比べてz個伯爵領が増加しています。
一部の郡はプロヴィンス数が多かったり、面積が広かったりしたので近代に存在した郡のように分割しました。
京都、大阪、奈良、堺といった町は独立した伯爵領として設定しました。

[h3]既知の問題と未実装[/h3]
[url=https://github.com/almandite1/shogunate_map_alteration/issues?q=is%3Aissue+is%3Aopen+label%3A%22known+issues+%26+not+yet+installed%22]既知の問題と未実装の一覧[/url]

[h2]動作条件[/h2]
[list]
[*] [url=https://store.steampowered.com/app/1158310]Crusader Kings III[/url]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2217567218]Japanese Language Mod[/url]
[*] [url=https://steamcommunity.com/workshop/filedetails/?id=2253279956]Shogunate (Japanese version) MOD[/url]
[/list]

[h2]この MOD への貢献について[/h2]
以下のような分野で協力していただける方を募集しています。
[olist]
[*] 男爵領のタイトル名（お城や寺社や町の名前）が歴史的に適切であるかどうか確認すること。
[*] マップエディターを使って、マップロケーターの位置を適切な場所に調整すること。
[*] タイトル名やこの Steam Workshop のコンテンツを英語その他の言語への翻訳。
[*] キャラクターの髪や服を Maya や Blender でモデリングし、PDX形式でエクスポートし、ゲーム内で動くように調整すること。この MOD、あるいはメイン MOD で必要とされる 3D モデルについて Paradox Forum の投稿にまとめています。[url=https://forum.paradoxplaza.com/forum/threads/mod-public-alpha-shogunate-map-alteration-sub-mod.1467780/post-27623098]こちら[/url]もご参照ください。
[/olist]
成果物の競合を避けるため事前に申告いただければ助かります。ご連絡は [url=https://forum.paradoxplaza.com/forum/threads/mod-public-alpha-shogunate-map-alteration-sub-mod.1467780/]Paradox Forum[/url] からお願いします。

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
