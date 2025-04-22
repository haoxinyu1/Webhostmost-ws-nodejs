# Webhostmost部署 node-ws 项目教程： [www.kejiland.com](https://www.kejiland.com/post/273275c7.html)
# Dataonline 部署 node-ws 项目教程:  [www.kejiland.com](https://www.kejiland.com/post/a5fe04de.html)
| 环境变量       | 默认值                                      | 说明                                                         |
|----------------|---------------------------------------------|--------------------------------------------------------------|
| `UUID`         | `b28f60af-d0b9-4ddf-baaa-7e49c93c380b`       | 用户 UUID，用于唯一标识客户端或用户                          |
| `NEZHA_SERVER` | `nezha.gvkoyeb.eu.org`                      | 哪吒监控服务器地址                                           |
| `NEZHA_PORT`   | `443`                                       | 哪吒监控端口，443 时会自动开启 TLS                           |
| `NEZHA_KEY`    | `""`（空字符串）                            | 哪吒监控认证密钥，若未设置完整的三个哪吒变量将不启用监控     |
| `CFDOMAIN`     | `""`                                        | Cloudflare 加速域名（可选）                                  |
| `DOMAIN`       | `""`                                        | 项目主域名或已反代域名（不带协议前缀）                       |
| `NAME`         | `dataonline`                                | 项目名称，用于识别展示等用途                                |
| `PORT`         | `3000`                                      | 服务运行端口                                                 |
| `TOKEN`        | `sub`                                       | 路由令牌，例如 `/sub` 将被用作订阅接口路径                  |
