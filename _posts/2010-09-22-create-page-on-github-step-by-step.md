---
layout: post
title: 在 github 上建立 pages 的过程
---
#{{ page.title }}
2010-09-22 @杭州

##建立项目-Repository
  首先在 GitHub 上建立自己库，例如一个 test 库;
  接着在本地建立 test 库的连接：
####Global Setup:
    Set up git 
      git config --global user.name "yourname"
      git config --global user.email "yourmail"
####Next steps:
    mkdir Test
    cd Test
    git init
    touch README
    git add README
    git commit -m 'first commit'
    git remote add origin git@github.com:yourname/Test.git
    git push -u origin master
##创建页面-pages


