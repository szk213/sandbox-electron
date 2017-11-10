sandbox-electron
===

Electronを試してみる

## ビルド実行
```cmd
npm run electron .
```

## ビルド
### Windows 64bit
```cmd
npm run electron-packager . sandbox-electron --platform=win32 --arch=x64 --overwrite
```

### メモ
package.jsonのトップレベルのmainにエントリーポイントのjsを指定しないと**Unable to find Electron app**エラーがでる

## 参考
- [最新版で学ぶElectron入門 – HTML5でPCアプリを開発する利点と手順](https://ics.media/entry/7298)
- [Electronの環境構築（for Windows）](https://qiita.com/TigRig/items/64d55b5fc5483b01c3b5)
- [Electron で開発したアプリの Windowsインストーラの作成](http://tech.at-iroha.jp/?p=548)

## Tags
- v1.0.0: electrionアプリ作成