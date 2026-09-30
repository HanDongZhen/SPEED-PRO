# 卫星测速隐私政策 / Satellite Speed Privacy Policy

开发者：Mr Han  
联系邮箱：2683326280@qq.com

`index.html` 包含完整的中文和英文隐私政策。页面内切换语言，地址保持不变。无需构建，无外部图片、字体、脚本或接口依赖。

## 导入 GitHub 和 Cloudflare Pages

1. 在自己的 GitHub 账号中创建仓库，例如 `satellite-speed-privacy`。
2. 上传本文件夹中的 `index.html`、`_headers` 和 `README.md`，确保 `index.html` 位于仓库根目录。
3. 在 Cloudflare 的 **Workers & Pages → Create application → Pages → Connect to Git** 中选择该仓库。
4. 框架预设选择 **None**；构建命令留空；构建输出目录填 `.`；生产分支选择仓库默认分支，通常为 `main`。
5. 完成部署后，用中国网络关闭代理实际访问，并检查中文/英文切换。确认可用后，将同一个 HTTPS 页面地址填写到华为应用的隐私政策地址中。

也可以在 Cloudflare Pages 中选择 **Direct Upload / Upload assets**，上传文件夹或压缩包；直接上传创建的项目不能随后改为 Git 集成，需另建 Git 集成项目。

Cloudflare 免费 Pages 的部署成功并不代表每个中国网络均可访问。若默认地址无法访问，需要配置可用的自定义域名并重新验证，或改用支持中国访问的托管服务。此前的 chatgpt.site 地址不作为本次中国区上架地址。

## 维护

只修改政策时，提交新的 `index.html` 即可自动触发 Git 集成项目的重新部署。页面与应用的政策文案应同步更新。

本目录只提供网站文件。应用工程、签名密钥和调试资料应单独保存。
