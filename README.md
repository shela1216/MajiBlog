# MajiBlog
- 個人綜合部落格
- 使用Hexo建置

## 常用指令

1. 初始化

`hexo init blog`

`cd blog`

`npm install`

`hexo server`

2. 自定 IP

`hexo server -i 192.168.1.1`

3. 使用butterfly佈景主題

`npm i hexo-theme-butterfly`

- 參考: https://github.com/jerryc127/hexo-theme-butterfly

4. 發布github

`hexo clean && hexo deploy`

 
    deploy:
    type: git
    repo: https://github.com/<username>/<project>
     # example, https://github.com/hexojs/hexojs.github.io
    branch: gh-pages``
 
