# 3d-pose-baselineテスト

## Update
- Pre-trainedモデルと、デフォルトのモデルが違うので、`src/predict_3dpose.py`に
変更を加えた。

## ダウンロード
- `h36m`データのダウンロード  
```shell
git clone https://github.com/una-dinosauria/3d-pose-baseline.git
cd 3d-pose-baseline
mkdir data
cd data
wget https://www.dropbox.com/s/e35qv3n6zlkouki/h36m.zip
unzip h36m.zip
rm h36m.zip
cd ..
```

- Pre-trained modelのダウンロード
[本家のGoogle Drive](https://drive.google.com/file/d/0BxWzojlLp259MF9qSFpiVjl0cU0/view?usp=sharing)から落としてくる。

プログラムを実行するディレクトリ直下(たとえば、`notebooks`で行うなら`notebooks`内)
にzipから解凍した`experiments`を置く

## リンク
- [本家github](https://github.com/una-dinosauria/3d-pose-baseline/tree/da0cc60f49ebebfa99cfe6465a693684003f543a)

