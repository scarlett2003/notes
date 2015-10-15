##合併固定幾個版本
  git rebase -i HEAD~~
>表合併head前3個小版本

##一次合併多個版本到最新版本
  git rebase -i origin/gh-pages
>一次合併多個版本


#.gitconfig 參考別名設置
<p>
  [user]
    name = xxx<br />
    email = xxx@gmail.com<br />
  [core]<br />
    editor = vim<br />
  [alias]<br />
    ci = commit -a -v<br />
    st = status -s<br />
    br = branch<br />
    throw = reset --hard HEAD<br />
    throwh = reset --hard HEAD^<br />
  [color]<br />
    ui = true<br />
  [push]<br />
    default = current<br />
</p>
