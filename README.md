# LSPatch-ApkFactory
一个基于LSPatch的打包工具，自动为常见应用打LSPatch补丁的仓库<br>
本仓库打包的任何应用都需要搭配对应的加载器来管理<br>
你没看错，本仓库不管集成模式，只管本地模式<br>
例如 `TikTok-35.3.2-398-lspatched.apk` 对应的加载器是 `LSPatch` , 因为文件名包含`lspatch`

本仓库基于如下分支打包 请注意版本号不能低于这个表格内的
| 分支 | 版本 | 仓库地址 | 发布地址 | 状态 |
| - | - | - | - | - |
| LSPatch | 0.6 | [→](https://github.com/LSPosed/LSPatch) | [↑](https://github.com/LSPosed/LSPatch/releases/tag/v0.6) | √ |
| OPatch | 0.0.7 | | | × |
| NPatch | 
| ONPatch |

本仓库自动打包的项目
| 软件名称 | 来源 | 版本 |
| - | - | - |
| 支付宝 | 豌豆荚 | latest |
| 微信 | 豌豆荚 | latest |
| Soul | 豌豆荚 | latest |
| TikTok | ApkPure | latest |