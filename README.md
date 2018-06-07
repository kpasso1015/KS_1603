# United Photogram
[![photo](https://imgur.com/a/UzgUleu)]([https://www.slideshare.net/secret/Tk8Y07l3A6CE9])
## 製品概要
### Dimension Tech
### 背景（製品開発のきっかけ、課題等）
誰しも過去の自分に会いに行き、過ちの修正、人生を良い方向に導きたいと願ったことがあるはずです。現代社会の写真の活用場所の中では、現在(に近い)の写真ばかりが扱われますが、「保存され続ける」だけが役割の昔の写真を有効活用することが課題です。

また昨今、「君の名は。」に代表されるように、アニメやドラマの舞台巡りが盛んに行われています。しかし、現実世界(3次元)とデフォルメされた世界(2次元)との格差(ギャップ)が懸念されています。そこでギャップを利用して、写真に新たな価値を付加することで舞台めぐりをさらに活性させることが課題です。

### 製品説明（具体的な製品の説明）
United Photogramは、過去の写真や作品の1シーンの画像を資源として、複数枚の画像を融合された"多次元写真"という新しい遊び方を提案します。ノスタルジックな体験と新奇な感覚との出会いをユーザに与えるアプリです。

1. アルバムから合成したい昔の写真(背景写真)を選択する
2. 背景写真の位置情報を元に、背景写真の撮影場所に移動する
3. ガイド(背景写真をエッジ処理して薄く表示したもの)を参考にしながら、撮影をする(現在の写真)
4. 現在の写真から背景写真と合成したいものを選択する。(未実装)
5. 好みのオプションにあわせて写真を合成


### 特長
#### 1.高品質な写真合成
Poisson Image Editing のアルゴリズムを利用することによって、違和感のないシームレスな画像合成を100行のコンパクトなコードで実現します。

#### 2.恒久的なコンセプト
「フォレスト・ガンプ」(1994年)の映画にもあるように, 昔の映像に現代の映像を合成する描写は昔から存在します。最近でもChino Otsuka(写真家)のImagine Finding Me(2012年)という写真集が発刊され、長い間使われている表現方法といえます。

#### 3.一元化された機能
Goodle Mapsを活用することで、写真の選択から写真の合成までのプロセスを本アプリで完結します。

### 解決出来ること
思い出の場所にいくことで、過去の未練を払拭する機会や幸せな気持ちが生まれるます。

つまり、震災などの負の遺産を振り返り命を大事にする様にもなりますし、過去を振り返ることで未来に向けて明るい気持ちを持てるようになります。

### 今後の展望
* 昔の写真のノイズや傷を検出し、それを復元しながらの画像合成。 また、位置情報の追加UI。
* 細かいUIや未実装の機能の搭載
* サーバーを使った写真共有コミュニティの作成
* 静止画だけでなく動画にも対応

### 注力したこと（こだわり等）
* シンプルなUI
* ガイド撮影(カラーでのエッジ処理)

## 開発技術
### 活用した外部技術

#### フレームワーク・ライブラリ・モジュール
* OpenCV
* GoogleMaps

#### デバイス
* iOS
