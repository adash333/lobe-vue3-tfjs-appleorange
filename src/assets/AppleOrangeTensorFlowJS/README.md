# AppleOrangeTensorFlowJS

詳細は[（９）TensorFlow.js形式で出力してWindowsローカル環境でtfjsExample.tsを実行](https://i-doctor.sakura.ne.jp/font/?p=45547)へ


## デプロイしたもの





## Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる 目次

[（１）LobeのインストールからTensorFlowモデルのエクスポートまで](https://i-doctor.sakura.ne.jp/font/?p=44635)

[（２）Windows10でPython3.6+TensorFlow1.15をセットアップ](https://i-doctor.sakura.ne.jp/font/?p=44703)

[（３）Windows10ローカル環境でtf_example.pyを実行](https://i-doctor.sakura.ne.jp/font/?p=44808)

[（４）Windows10ローカル環境でFlaskを用いて画像判定](https://i-doctor.sakura.ne.jp/font/?p=44883)

[（５）FlaskアプリをHerokuにデプロイ](https://i-doctor.sakura.ne.jp/font/?p=44947)

[（６）Windows10にTensorFlow.jsの環境構築とDEMOアプリのNetlifyへのデプロイ](https://i-doctor.sakura.ne.jp/font/?p=45117)

[（７）ExpressアプリをHerokuまたはNetlifyにデプロイ](https://i-doctor.sakura.ne.jp/font/?p=45277)

[（８）Lobeで出力した自前モデルをTensorFlow.js用モデルに変換してNetlifyで公開にtry](https://i-doctor.sakura.ne.jp/font/?p=45386)

[（９）TensorFlow.js形式で出力してWindowsローカル環境でtfjsExample.tsを実行](https://i-doctor.sakura.ne.jp/font/?p=45547)

## 実行方法

`git clone https://github.com/adash333/AppleOrangeTensorFlowJS`

Run `cd example`

Run `npm install`

AppleOrangeTensorFlowJS\example\node_modules\@tensorflow\tfjs-node\deps\lib  
内の、`tensorflow.dll`を、  
AppleOrangeTensorFlowJS\example\node_modules\@tensorflow\tfjs-node\lib\napi-v6  
にコピー＆ペースト  
参考：https://fantashit.com/windows-error-the-specified-module-could-not-be-found-node-modules-tensorflow-tfjs-node-lib-napi-v6-tfjs-binding-node/

Run `npm run predict apple.jpg` to predict.(Windowsローカル環境)   


## 開発環境

```
Windows10 Pro
Lobe 0.8.1208.4
VisualStudioCode 1.51.0
Git for Windows v2.29.2
python 3.6
pip 20.2.4
pipenv 2020.11.4

nvm-windows 1.1.7
node v14.15.0
npm 6.14.8
yarn 1.22.10
Visual Studio Community 2019 + "Desktop development with C++" (約8GB)
parcel-bundler 
```
