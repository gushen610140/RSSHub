# 部署

## 克隆仓库

```bash
gh repo clone gushen610140/RSSHub -- --depth=1
```

```bash
git clone --depth 1 git@github.com:gushen610140/RSSHub.git
```

## 安装依赖

```bash
pnpm i
```

## 编译

```bash
pnpm build
```

## 启动

```bash
pnpm start
```

```bash
pm2 start dist/index.mjs --name rsshub
```
