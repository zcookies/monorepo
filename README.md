### 启动

```bash
pnpm install

pnpm --filter {packages/main} dev
```





### 结构

monorepo
├─.npmrc
├─package.json
├─pnpm-lock.yaml
├─pnpm-workspace.yaml
├─README.md
├─packages
|    ├─sub
|    |  ├─.gitignore
|    |  ├─index.html
|    |  ├─package.json
|    |  ├─README.md
|    |  ├─tsconfig.json
|    |  ├─tsconfig.node.json
|    |  ├─vite.config.ts
|    |  ├─src
|    |  ├─public
|    ├─other
|    |   ├─.gitignore
|    |   ├─index.html
|    |   ├─package.json
|    |   ├─README.md
|    |   ├─tsconfig.json
|    |   ├─tsconfig.node.json
|    |   ├─vite.config.ts
|    |   ├─src
|    |   ├─public
|    ├─main
|    |  ├─.gitignore
|    |  ├─.pnpm-debug.log
|    |  ├─index.html
|    |  ├─package.json
|    |  ├─README.md
|    |  ├─tsconfig.json
|    |  ├─tsconfig.node.json
|    |  ├─vite.config.ts
|    |  ├─src
|    |  ├─public