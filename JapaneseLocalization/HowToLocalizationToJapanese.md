### はじめに
![日本語化のプレビュー画像](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/img/Localizated_gameplay.png "日本語化されたゲーム画面のサンプル画像")

この日本語化はゲーム非公式のものです。

「なんとなく日本語化してみたらできた」という内容のものです。

この方法で何らかのバグが起きても、それはゲーム開発者やパブリッシャーはなんら動作の保証をしません。

自己責任でお願いします。

また、ゲーム本体が日本語化対応したり、日本語化や Modding などの手段が公式アナウンスされた場合

この内容は古いものとなります。

---
### 日本語化ファイルについて

[ここ](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/Custom.txt)に日本語化ファイルがあります。

この日本語化ファイルはまだ翻訳途中です。

英語のままだったり、翻訳が不十分だったり、不適切だったりします。

また、一部の単語(漢字)を頭文字に入れるとゲームが進行不能になる現象を確認しています。

そのため、不自然な訳語になりますが一部の単語はその現象を回避するもので訳語をあてています。

---
### 日本語化のやりかた

1. [日本語化ファイル](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/Custom.txt) を保存します。ファイル名はそのまま「 Custom.txt 」で保存して下さい。(名前を付けてリンク先を保存 または 右クリックで名前を付けて保存 です)
2. Starship Theory の Config ディレクトリを開きます。
    - Config ディレクトリの場所:
        - Windows の場合:
            - `C:\Program Files (x86)\Steam\steamapps\common\Starship Theory\Config`
        - Mac の場合:
            - `~/Library/Application Support/Steam/steamapps/common/Starship Theory/Config/`
        - Linux(Ubuntu) の場合:
            - `~/Steam/steamapps/common/Starship Theory/Config/`
3. Config ディレクトリに手順1で保存した Custom.txt を配置します。
4. ゲームを起動します。
5. Interface ＞ Language を選んで デフォルトでは English となっている部分を Cunstom になるまでクリックします。
    - ![Language で Custom を選ぶ](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/img/SettingToJapanese.png "画面操作のイメージ")
6. Quit を選んでゲームを終了します。
7. もう一度、ゲームを起動すると日本語化されます。

---
### 元に戻す方法

1. ゲームを起動します。
2. インターフェース ＞ 言語設定 を選んで Custom となっている部分を English になるまでクリックします。
    - ![Language で English を選ぶ](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/ "画面操作のイメージ")
3. 終了 を選んでゲームを終了します。
4. Starship Theory の Config ディレクトリを開いて、 Custom.txt を削除します。

---
### 日本語化を更新する方法

1. 最新の[日本語化ファイル](https://github.com/saronpasu/Starship-Theory/raw/master/JapaneseLocalization/Custom.txt) を保存します。ファイル名はそのまま「 Custom.txt 」で保存して下さい。
2. Starship Theory の Config ディレクトリを開きます。
    - Config ディレクトリの場所:
        - Windows の場合:
            - `C:\Program Files (x86)\Steam\steamapps\common\Starship Theory\Config`
        - Mac の場合:
            - `~/Library/Application Support/Steam/steamapps/common/Starship Theory/Config/`
        - Linux(Ubuntu) の場合:
            - `~/Steam/steamapps/common/Starship Theory/Config/`
3. Config ディレクトリに手順1で保存した Custom.txt を上書き保存します。

---
### 日本語化の割合(だいたい)

40% ぐらい

---
### 日本語化するとバグった単語リスト

これらの単語を行頭に入れるとバグりました

- 船
    - Hull を 船体 に翻訳しようとしましたが、バグったので フレーム にしています
- 床
    - Floor を 床 に翻訳しようとしましたが、バグったので フロア にしています
