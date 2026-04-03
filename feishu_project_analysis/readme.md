# 飞书项目评估
n8n version:1.104.1
## n8n 配置 
配置 `Custom Auth`
```json
{
  "body": {
    "app_id": "cli_XXX",
    "app_secret": "XXXXX"
  }
}
```

## 飞书侧
1. 工作台创建应用
2. 应用添加机器人能力
3. 设置事件配置
4. 添加事件`im.message.receive_v1`
5. 事件权限打开
6. 发布