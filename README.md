# hello-test

一个用于测试 Git 流程的极简项目。提交、推送、分支、Pull Request 都可以在这里放心练。

仓库地址：https://github.com/cwh1024/hello-test

## 文件

| 文件 | 用途 |
| --- | --- |
| `index.html` | 自包含静态首页，双击即可打开 |
| `README.md` | 项目说明 |

## 本地查看

双击 `index.html` 即可，无需安装依赖，也无需构建。

## 练习建议

1. 修改 `index.html` 里任意一行文字。
2. 提交并推送：

   ```bash
   git add index.html
   git commit -m "test: 修改首页文案"
   git push
   ```

3. 回到仓库页面，确认提交记录和文件内容都已更新。

也可以新建分支、发起 Pull Request 再合并，把完整流程走一遍。

## 说明

- 仓库是公开的，请不要上传密码、私钥、令牌或 `.env` 等敏感信息。
- 目前没有部署。在 GitHub 上打开 `index.html` 看到的是源码；要看网页效果，请本地打开。
