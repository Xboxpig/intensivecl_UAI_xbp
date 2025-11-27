解决系统内 yarn 冲突问题
Ubuntu 系统内自带了一个很久的 yarn ,在
`/usr/bin/yarn`
经过实验 无法在 ZetaChain 的 webapp 安装中使用

故查找系统环境变量下的所有 yarn想
`which -a yarn`

```
/home/xboxpig/.nvm/versions/node/v20.19.6/bin/yarn
/usr/bin/yarn
/bin/yarn
```

并删除了`/bin/yarn`

```
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ yarn
yarn install v1.22.22
[1/4] Resolving packages...
```

```
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ npx install yarn
npm error could not determine executable to run
npm error A complete log of this run can be found in: /home/xboxpig/.npm/_logs/2025-11-27T09_22_20_903Z-debug-0.log
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ which -a yarn
/home/xboxpig/.nvm/versions/node/v20.19.6/bin/yarn
/usr/bin/yarn
/bin/yarn
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ sudo rm /usr/bin/yarn
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ which yarn
/home/xboxpig/.nvm/versions/node/v20.19.6/bin/yarn
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ nano ~/.bashrc
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ ls
README.md  eslint.config.mjs  index.html  package.json  public  src  tsconfig.app.json  tsconfig.json  tsconfig.node.json  vite.config.ts  yarn.lock
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ yarn
-bash: /usr/bin/yarn: No such file or directory
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ source ~/.bash
.bash_history  .bash_logout   .bashrc        
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ source ~/.bash
.bash_history  .bash_logout   .bashrc        
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ source ~/.bash
.bash_history  .bash_logout   .bashrc        
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ source ~/.bashrc 
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ yarn
yarn install v1.22.22
[1/4] Resolving packages...
...
[2/4] Fetching packages...
...
[3/4] Linking dependencies...
...
[4/4] Building fresh packages...
Done in 84.38s.
```


```
xboxpig@XBPG-PC:~/zetachin_proj/hello/frontend$ yarn dev
```


```
yarn run v1.22.22
$ vite

  VITE v7.1.6  ready in 141 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
[baseline-browser-mapping] The data in this module is over two months old.  To ensure accurate Baseline data, please update: `npm i baseline-browser-mapping@latest -D`
5:30:51 PM [vite] (client) ✨ new dependencies optimized: @zetachain/wallet
5:30:51 PM [vite] (client) ✨ optimized dependencies changed. reloading
```

部署成功.