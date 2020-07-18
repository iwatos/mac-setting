# ssh鍵の作成
```shell script
# 参考 https://qiita.com/suthio/items/2760e4cff0e185fe2db9
ls -al ~/.ssh #すでに作られてないか確認
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"ssh-keygen -t rsa -b 4096 -C "git hubの登録アドレスとか" # 作成
pbcopy < ~/.ssh/id_rsa.pub # ~/.ssh/id_rsa.pubの内容をクリップボードにコピー
```
- git hubに登録

# fish 
```shell script
# デフォルトをfishにする
echo /usr/local/bin/fish | sudo tee -a /etc/shells
chsh -s /usr/local/bin/fish
# oh-my-fish
curl -L http://get.oh-my.fish | fish
# fishのエイリアス設定
nano ~/.config/fish/config.fish
```

# コマンド追加
- VScode: code
- jetbrains toolbox: idea

# 設定同期
- Alfred
- iterm
- BetterTouchTool

# anyenv設定

# mackup