## Changelog

[CHANGELOG](./CHANGELOG.md)

## 代码目录说明

```shell

src
├── data                        # 静态数据
│   └── fundSuggestData.ts      # 基金数据，执行 `node ./demo/fundSuggestList.js` 更新生成
├── explorer                    # 侧边栏核心代码
│   ├── binanceProvider.ts      # 数字货币
│   ├── binanceService.ts
│   ├── forexProvider.ts        # 外汇
│   ├── forexService.ts
│   ├── fundProvider.ts         # 基金
│   ├── fundService.ts
│   ├── leekService.ts
│   ├── newsProvider.ts         # 雪球新闻
│   ├── newsService.ts
│   ├── stockProvider.ts        # 股票
│   └── stockService.ts
├── extension.ts                # 插件初始化入口
├── globalState.ts              # 全局缓存，插件激活到销毁周期内的变量缓存
├── output                      # Terminal 视图下的OUTPUT栏输出新闻
│   └── flash-news
├── registerCommand.ts          # 注册命令
├── shared                      # 工具函数或者类
│   ├── WVMessageUtils.ts
│   ├── constant.ts
│   ├── holidayHelper.ts
│   ├── leekConfig.ts
│   ├── leekTreeItem.ts
│   ├── remindNotification.ts
│   ├── telemetry.ts
│   ├── typed.ts
│   └── utils.ts
├── statusbar                   # 状态栏
│   ├── Profit.ts
│   └── statusBar.ts
└── webview   # webview 页面

```

## License

[LICENSE](./LICENSE)
