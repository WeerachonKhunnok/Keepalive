# 各种自动保活脚本

## VPS一键五协议无交互安装脚本

vless+reality | vmess+argo | hy2 | tuic | socks5

```bash
PORT=34766 bash <(curl -Ls https://raw.githubusercontent.com/yutian81/Keepalive/main/vps_sb5in1.sh)
```

### 其他支持的变量

- **CFIP**：CF优选IP或域名，默认 `cf.090227.xyz`
- **CFPORT**：CF优选IP或域名的端口，默认 `443`

CF 隧道默认监听端口: `8001`

### 参数 PORT 的含义

- PORT=34766，即 vless reality 协议端口为 34766，类型为 TCP
- socks5 端口+1，即 34767，类型为 TCP
- tuic 端口+2，即34768，类型为 UDP
- hy2 端口+3，即34769，类型为 UDP
- vmess+argo 为 cdn 协议，不占用端口

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yutian81/Keepalive&type=date&legend=top-left)](https://www.star-history.com/#yutian81/Keepalive&type=date&legend=top-left)
