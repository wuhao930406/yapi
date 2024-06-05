## changelog

see `CHANGELOG.v2.md`

## 使用

1. `git clone https://github.com/gozeon/yapii.git` or 下载项目
2. `npm install --production`
3. 修改 `config.json` 配置文件
4. `pm2 start server/app.js --name yapii`

日志管理建议使用 `pm2-logrotate`

## 设置系统管理员

```bash
npm run install-server
```

## develop

```bash
docker build . -t yapii
docker run --rm -it -p 4000:4000 -v $PWD:/app -w /app yapii /bin/sh
```

## note

知道你们忙，所以我来了。


- yapi不维护了
- 我还挺喜欢用
- 万恶的`node_modules`，弄得js开发者跟`诈骗犯`一样 
