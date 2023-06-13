| 参数          | 说明                                             |
| ------------- | ------------------------------------------------ |
| ALI_REFRESH_TOKEN  | 阿里云盘 ALI_REFRESH_TOKEN, 添加多个环境变量可支持多账户签到 |
| CLIENT_ID     | 可选项, 用于青龙面板 API 更新 ALI_REFRESH_TOKEN 字段  |
| CLIENT_SECRET | 可选项, 用于青龙面板 API 更新 ALI_REFRESH_TOKEN 字段  |

> 添加订阅后可在定时任务列表发现新增任务, 可自行调整任务执行时间
```shell
ql repo https://github.com/ZhanPhty/aliySignin.git "aliyAutoSignin" "" "qlApi"
```
