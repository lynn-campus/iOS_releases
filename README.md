# iOS_releases

各软件的 IPA 分发仓：只放构建产物，不放源码（源码仓均为 private）。

## 布局

```
icons/<app>.png      # 各 App 的 1024 图标，供 apps.json 的 iconURL 引用
releases/tag: <app>  # 每个 App 一个稳定 tag，如 ccut
```

| App | 稳定下载地址 |
| --- | --- |
| CCUT | https://github.com/lynn-campus/iOS_releases/releases/download/ccut/CCUT.ipa |
| CCUT（AltStore 源） | https://github.com/lynn-campus/iOS_releases/releases/download/ccut/apps.json |

新增 App：新建自己的 tag（如 `myapp`），由对应源码仓的 Actions 推送产物到这里。
