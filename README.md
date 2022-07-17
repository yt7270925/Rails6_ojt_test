# OJT 卒業テスト

## 使用方法

### Clone する場合

```
$ git clone https://github.com/ls-contents/Rails6_ojt_test.git
$ cd ojt-test
$ git branch -r | grep -v "\->" | grep -v main | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
$ git checkout ~~~
```

### ダウンロードする場合

テストを行うブランチへ移動し[Code > Download ZIP]をクリックしダウンロードする

## 詳細資料

[OJT マニュアル](https://infratop.docbase.io/posts/1470551)  
[OJT 卒業テスト用語解説](https://infratop.docbase.io/posts/1470557)  
[OJT 卒業テスト配布用](https://infratop.docbase.io/posts/1470563)
