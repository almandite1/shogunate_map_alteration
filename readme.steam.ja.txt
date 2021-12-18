Shogunate 地図改変サブ MOD 日本語 ベータ版 Version 0.6.5 'Benkei'

[h1]Shogunate 地図改変サブ MOD 日本語 ベータ版 Version 0.6 'Benkei'[/h1]
====

Shogunate 地図改変サブ MOD ベータ版は [url=https://steamcommunity.com/workshop/filedetails/?id=2253279956]Shogunate MOD [/url]のサブ MOD です。地図を高解像なものに置き換え、プロヴィンス＝ holding を増やします。
英語版は[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2391487224]こちら[/url]からサブスクライブできます。

[h2]注意[/h2]
このMODはベータ版です。未知の不具合、既知の問題点、未実装機能があります。おそらくこの　MOD　がバージョンアップすると、保存したセーブデータは使えなくなります。
メイン MOD である Shogunate のセーブデータとの互換性はありません。
地図サイズが CK3 バニラおよびメイン MOD より大きいため、より高性能なハードウェア構成が必要になるでしょう。

[h2]この MOD の説明[/h2]
[h3]地形[/h3]
現実の DEM（数値標高モデル）から新しく生成した height map をベースとし、地図投影法として東経135°を中心とした[url=https://ja.wikipedia.org/wiki/%E3%82%A4%E3%82%B3%E3%83%BC%E3%83%AB%E3%82%A2%E3%83%BC%E3%82%B9%E5%9B%B3%E6%B3%95]イコールアース図法[/url]を使っています。この地図投影法により土地の面積比は正しく表示されます。
DEM と現実の土地被覆情報を利用して基本的な地図テクスチャを描画しました。

[h3]プロヴィンス[/h3]
15世紀末頃の郡（ゲーム中の伯爵領に相当）ごとの米の生産高（石高）一万石に対して1プロヴィンスを目安として、伯爵領中のプロヴィンス数を決めましたが一部例外があります。伯爵領中のプロヴィンス数は今後変更する可能性があります。
プロヴィンスの形状は1920年時点での日本の行政区分を組み合わせて作りました。
地図の基本データである heightmap.png と provinces.png はメイン MOD の３倍の面積 12,288 × 8,192 ピクセルで新規作成しました。プロヴィンス数はメイン MOD の約 4 倍の 3,140 個あります（海域などを含む）。
プロヴィンス数の増加により戦略と戦術の選択肢が増え、新しいゲームプレイ体験をもたらすことでしょう！
一部の holding　は、稲葉山城が岐阜城に変わったように時代に伴い名前が変化します。
通行不能地帯が存在します。

[h3]伯爵領[/h3]
15世紀に存在した郡がゲーム中に伯爵領として出現するように再編し、メイン MOD に比べて200個あまり伯爵領が増加しています。
一部の郡はプロヴィンス数が多かったり、面積が広かったりしたので近代に存在した郡のように分割しました。
京都、大阪、奈良、堺といった町は独立した伯爵領として設定しました。

[h3]家（Houses）の追加[/h3]
メイン MOD にはない多数の庶家（Cadet Branch）を設定しています。
バージョン 0.5 の時点で 230 の家があります。
新しく追加した家のモットーは故事成語や日本のことわざにしています。

[h3]その他[/h3]
ごく一部のキャラクターデータをより歴史的に正確になるように変更しました。
一部のタイトル歴史データをより歴史的に正確になるように変更しました。
メイン MOD で家紋設定されていない氏族に家紋を設定しました。
清和源氏義国流新田氏の家紋「大中黒」といった、10 個の新しい家紋画像ファイルを追加しました。
x_buddhist 文化を持つ男性キャラクターの髪がなくなるように設定しました。

[h3]ロードマップ[/h3]
現在作業中の内容は[url=https://github.com/almandite1/shogunate_map_alteration/issues?q=is%3Aopen+assignee%3Aalmandite1]ここ[/url]からご覧いただけます。

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
[*] その他
[/olist]
成果物の競合を避けるため事前に申告いただければ助かります。ご連絡は [url=https://forum.paradoxplaza.com/forum/threads/mod-public-alpha-shogunate-map-alteration-sub-mod.1467780/]Paradox Forum[/url] か [url=https://discord.gg/jfcSfchJGC]Discord[/url] からお願いします。

[h2]クレジット[/h2]
[url=https://github.com/almandite1/shogunate_map_alteration/tree/main#credit]ここ[/url]からご覧いただけます。