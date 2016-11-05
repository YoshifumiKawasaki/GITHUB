# Github-howto

## ０．GithubにNew Repository作成

## １．既存ディレクトリをgitの管理下に置く
  `cd directory　# ディレクトリに移動`  
  `git init (d) # dというディレクトリを作成`  
  `git add . # -A: all`  
  `git commit -m "first commit" # -mでメッセージを追加`
  
## ２．Githubのリポジトリをリモートリポジトリとして登録
  `git remote add original https://github.com/Username/Repository.git`

## ３．ローカルからリモートにpush
  `git push origin master # push master to origin`


## ４．リモートからclone
  `cd directory　# ディレクトリに移動`  
  `git clone https://github.com/Username/Repository.git`

## 参考サイト
http://www.backlog.jp/git-guide/

http://fistofmath.sakura.ne.jp/git%E3%82%92%E4%BD%BF%E3%81%84%E5%A7%8B%E3%82%81%E3%81%9F-%E6%97%A2%E5%AD%98%E3%83%87%E3%82%A3%E3%83%AC%E3%82%AF%E3%83%88%E3%83%AA%E3%82%92github%E3%81%AE%E3%83%AC%E3%83%9D%E3%82%B8%E3%83%88%E3%83%AA/

http://qiita.com/oreo/items/82183bfbaac69971917f (Markdown)
