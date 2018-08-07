# Git 版本控制
這裡放置Git學習進度
## 索引(Index)

### 使用者設定

`git config --[global,local] user.[name,email] "string"`
### 縮寫

alias:別號,且設定擋在gitconfig裡,可做修改

`git config --global alias.co checkout`

`git config --global alias.br branch`

`git config --global alias.st status`

`git config --global alias.l "log --oneline --graph"`
### 使用git

```
git init
git status
git add
git rm
git commit
git commit -a -m "message"                    一段式commit
git log --oneline --graph
git log --oneline --author="name\|name2"      查找作者
git log --oneline --grep="message"            查找commit訊息
git log -S "content"                          查找檔案內容
git log --oneline --since="9am"               查找特定時間commit
                  --until="12am"              查找特定時間commit
                  --after="2017-01"           查找特定日期commit
```
