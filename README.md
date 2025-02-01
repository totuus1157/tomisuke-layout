# Tomisuke配列 for Karabiner-Elements

[とみすけ](https://twitter.com/_Tomisuke)氏によって作成されたキーボード配列【[Tomisuke配列](https://tomisuke.com/tomisuke-keyboard-layout/)】をMacで使用するための[Karabiner-Elements](https://karabiner-elements.pqrs.org/)実装

## 以下の特徴があります
- 完全なレイアウト変更とCommandキーとの組み合わせのみQWERTY準拠、いずれかの方式から選ぶ事ができます。
- `Command + Option + Control + q`を押す事でQWERTY配列に瞬時に切り替える事ができます（`Command + Option + Control + t`でTomisuke配列に戻ります）。

## 導入方法
1. Karabiner-Elementsをまだインストールされていない方は、[こちら](https://karabiner-elements.pqrs.org/)からダウンロード、インストールしてください。
2. Tomisuke配列の設定ファイルを右側にある`Releases`からダウンロード、解凍します。
3. 解凍後のフォルダの中にある`tomisuke.json`と`tomisuke-qwerty-command.json`、いずれかのファイル（あるいは両方）をKarabiner-Elementsの設定フォルダ`~/.config/karabiner/assets/complex_modifications`に移動させて下さい（Macのディレクトリ構成に詳しくない方は、Finderのメニューバーにある`移動`→`フォルダへ移動…`で表示されるポップアップウィンドウにこのパスを入力すれば開くことができます）。
    - `onishi.json`は完全なレイアウト変更、`onishi-qwerty-command.json`はCommand キーとの組み合わせのみ QWERTY 準拠となっています。
4. Karabiner-Elementsの設定ウィンドウを開き`Complex Modifications`の`Add predefined rule`ボタンを押すと、ポップアップウィンドウの中に`Tomisuke配列`または`Tomisuke-QWERTY⌘配列`が存在するので`Enable`ボタンで有効化してください。これでTomisuke配列が使えるようになります（もし見当たらない場合はファイルの場所が正しいか確認して下さい）。

## もし気に入っていただけたなら
<a href="https://www.buymeacoffee.com/totuus1157" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
