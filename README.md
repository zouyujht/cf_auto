# Deploy to Cloudflare Workers

[![Deploy to Cloudflare Workers]([https://workers.cloudflare.com/resources/button/deploy-with-workers-dark.svg](https://deploy.workers.cloudflare.com/button))](https://deploy.workers.cloudflare.com/?url=https://github.com/zouyujht/cfauto)

---

### 使用说明

1.  在您的 GitHub 仓库中，创建一个名为 `README.md` 的文件。
2.  将上面代码块中的内容**完整复制**并粘贴到 `README.md` 文件中。
3.  **修改链接**：找到链接 `https://github.com/YOUR_USERNAME/YOUR_REPOSITORY`，将其中的 `YOUR_USERNAME` 改成您的 GitHub 用户名，`YOUR_REPOSITORY` 改成您的仓库名。
    *   例如，如果您的仓库地址是 `https://github.com/wangming/my-worker-script`，那么您应该将链接修改为 `https://deploy.workers.cloudflare.com/?url=https://github.com/wangming/my-worker-script`。
4.  保存并提交文件。

现在，您的仓库主页上就会显示一个 "Deploy to Cloudflare Workers" 的按钮。点击它之后，Cloudflare 会引导用户登录，并从您的这个 GitHub 仓库创建 Worker。在 Cloudflare 的设置界面中，它会自动检测到 `_work.js` 文件，您只需根据提示完成最后的部署步骤即可。
