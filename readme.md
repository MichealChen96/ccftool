创建CLI工具步骤
1: pnpm init
2: 创建bin目录
3: 在package.json中配置bin,并且在index.js中第一行标明在哪个环境中执行
   #!/usr/bin/env node 表示去环境变量里面找node
4: 将ccftool 添加到环境变量中: npm link
5: ccftool --version 通过commander来解析命令行中的参数
