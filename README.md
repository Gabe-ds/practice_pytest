# practice_pytest
## 必要環境
- [pyenv](https://github.com/pyenv/pyenv)
- [pipenv](https://github.com/pypa/pipenv)
## 環境構築
### リポジトリのダウンロード
```
$ git clone https://github.com/Gabe-ds/practice_pytest.git
```
or
```
$ gh repo clone Gabe-ds/practice_pytest
```
### Pythonのバージョン設定
```
$ pyenv local [PYTHON_VERSION]
```
※ `[PYTHON_VERSION]`は[Pipfile](./Pipfile)を参照
### ライブラリのインストール
```
$ pipenv install -r requirements.txt
```
## 参考サイト
- [pytest](https://docs.pytest.org/en/7.2.x/contents.html)
- [ゼロから学ぶPython](https://rinatz.github.io/python-book/ch08-02-pytest/)