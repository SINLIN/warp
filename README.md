# warp
参考：[https://p3terx.com/archives/cloudflare-warp-configuration-script.html](https://p3terx.com/archives/cloudflare-warp-configuration-script.html)

原版（默认socks5端口：40000）
```
# Cloudflare WARP 一键配置脚本 功能菜单
bash <(curl -fsSL git.io/warp.sh) menu
```

修改版（默认socks5端口：50000）
```javascript
# Cloudflare WARP 一键配置脚本 功能菜单
bash <(curl -fsSL https://sinlin.github.io/warp/warp.sh) menu
```
