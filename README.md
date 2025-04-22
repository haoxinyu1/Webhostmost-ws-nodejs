# Webhostmost部署 node-ws 项目教程： [www.kejiland.com](https://www.kejiland.com/post/273275c7.html)
# Dataonline 部署 node-ws 项目教程:  [www.kejiland.com](https://www.kejiland.com/post/a5fe04de.html)
| 环境变量       | 默认值                                      | 说明                                                         |
|----------------|---------------------------------------------|--------------------------------------------------------------|
| `UUID`         | `b28f60af-d0b9-4ddf-baaa-7e49c93c380b`       | 用户 UUID，用于唯一标识客户端或用户                          |
| `NEZHA_SERVER` | `nezha.gvkoyeb.eu.org`                      | 哪吒监控服务器地址                                           |
| `NEZHA_PORT`   | `443`                                       | 哪吒监控端口，`443` 时自动启用 TLS                          |
| `NEZHA_KEY`    | `""`                                        | 哪吒认证密钥，缺失任一哪吒相关变量将不启用监控               |
| `DOMAIN`       | `""`                                        | 项目主域名或已反代域名（不带 `http(s)://` 前缀）         |
| `CFDOMAIN`     | `DOMAIN`                                    | Cloudflare 加速域名，未配置时使用 `DOMAIN`                  |
| `NAME`         | `JP-webhostmost-GCP`                                | 项目名称，不填会自动获取                            |
| `PORT`         | `3000`                                      | 服务监听端口                                                 |
| `TOKEN`        | `sub`                                       | 订阅路径，如 `/sub`                                          |
