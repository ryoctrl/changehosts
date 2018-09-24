# ChangeHosts

Mac環境で自宅と外とでhostsファイル書き換えたい奴

自宅サーバー内触りたくないサーバーアプリケーション映えある１位がBINDなのでhostsで対応したい。

homehostsには192.168.0.xxx  hoge.foo.jpとか書いて使う.

パス通してコマンド的に実行したかったので拡張子はなし。


# Usage

```bash
# 初期設定
git clone https://github.com/ryoctrl/changehosts.git
cd changehosts
PATH=$PATH:/path/to/changehosts
sudo cp /etc/hosts .
sudo cp hosts homehosts
sudo cp hosts otherhosts
sudo vi homehosts
sudo vi otherhosts


# 普段使い
change home

# or

change other
```
