# 概要
avif形式ファイルをjpeg形式ファイルに変換するプログラムになります。  
指定したディレクトリに存在する全てのavifファイルを変換します。  
  
Cf. 参考  
[JavaScriptでAVIFをJPEGに変換する](https://zenn.dev/kyome/articles/22c314b3da88d8)  


# 環境構築
パッケージインストール  
```
npm install
```

プロジェクトを作成した時のNode.jsとnpmのバージョンは下記。  
- Node.js: v17.8.0  
- npm: 8.5.5  


# 使用例
- 構文  
```
node main.js inputPath outputPath
```

- 使用例  
```
node main.js /Users/user_name/Documents/input /Users/user_name/Documents/output
```
