## Steps to test the namespace package

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install --upgrade pip
$ cd foo
$ pip install -e .
$ cd ../namespace-foo
$ pip install -e .
$ cd ..
$ python main.py
"hello world"
```
