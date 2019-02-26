# atcoder

## ファイル,ディレクトリ作成

ABC063のファイル、ディレクトリを作る場合(言語はpythonを使用)

```
python main.py --mkdir --level abc --rnd 63 --lang python
```

pythonファイルの雛形が各問題ごとに作られる.
srcディレクトリがない場合はまとめて作られる.

## test

ABC063のA問題のコードをテストしたい場合(python)


```
python main.py  --level abc --rnd 63 --prob a --lang python
```

## submit

全てのサンプルをテストし、全て通った場合は提出する場合(python)

```
python main.py --submit  --level abc --rnd 63 --prob a --lang python
```


## parameters

* -v,--verbose (verbose mode)
* --lang (default : python)
* --level (default : abc) 
* --rnd (コンテストの回数) 
* --prob (A問題とか.小文字で指定)
* --src-dir (提出コードのディレクトリ. default: src)
* --submit (つけるとテストしたあと全部パスしてたら提出する.)
* --mkdir (つけると雛形生成)