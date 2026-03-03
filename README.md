# LSPatch-ApkFactory
> [!NOTE]
> 一个基于LSPatch的打包工具，自动为常见应用打LSPatch补丁的仓库<br>
包括 表格内所提及到的分支管理器 <br>
本项目打包的任何应用都需要搭配对应的加载器来管理(仅打包本地模式)<br>
例如 `Alipay-10.8.30.8000-lspatch.apk` 对应的加载器是 `LSPatch`<br>
在此希望 LSPatch能恢复更新，且大一统，且多选项，且最新，（我可不想一个应用包得服务多个分支）

> [!TIP]
> 自助餐食用方法 <br>
1.(可选) 如果没有在这找到你想要的应用 [填写表单提交](https://github.com/8Mi-Tech/LSPatch-ApkFactory/issues/new?template=add-app.yaml) <br>
2.[进入](https://github.com/8Mi-Tech/LSPatch-ApkFactory/actions/workflows/manual.yaml)并点击 `Run Workflow` 且勾选 `Release` <br>
3.稍等片刻可在[此处](https://github.com/8Mi-Tech/LSPatch-ApkFactory/releases/tag/CI-APKs)获取

> [!WARNING]  
> APK问题或模块问题，请优先找管理器作者反馈，在这里反馈没有作用 <br>
例:  `Alipay-10.8.30.8000-npatch.apk` ， 安装后若使用过程遇到在原版程序内没有出现的问题或模块问题，请向 `NPatch` 作者反馈

本仓库基于如下分支打包 请注意版本号不能低于这个表格内的
| 分支 | 版本 | 仓库地址 | 发布地址 | 状态 | 原因 |
| - | - | - | - | :-: | - |
| LSPatch | 0.6 | [GitHub](https://github.com/LSPosed/LSPatch) | [GitHub](https://github.com/LSPosed/LSPatch/releases/) | ✅ |
| JM_LSPatch | 0.7 | [GitHub](https://github.com/JingMatrix/LSPatch) | [GitHub](https://github.com/JingMatrix/LSPatch/releases) | ✅ |
| NPatch | 0.7.4_521 | [GitHub](https://github.com/7723mod/NPatch) | [Telegram](https://t.me/NPatch) | ❓ | 产物有些许问题,正在修复中 |

本仓库自动打包的项目
| 软件名称 | 别名 | 来源 | 版本 |
| :-: | :-: | :-: | :-: |
| 支付宝 | Alipay | vivo应用商店 | latest |
| 微信 | WeChat | vivo应用商店 | latest |
| Soul | | vivo应用商店 | latest |
| 抖音 | Douyin | vivo应用商店 | latest |
| 抖音极速版 | DouyinLite | vivo应用商店 | latest |
| QQ | | vivo应用商店 | latest |
| 小红书 | RedNote | vivo应用商店 | latest |
| 快手 | KwaiShou | vivo应用商店 | latest |
| TikTok | | ApkPure | latest |
|  | CamScanner | vivo应用商店 | latest |
