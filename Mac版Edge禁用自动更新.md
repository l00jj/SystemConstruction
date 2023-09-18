终端无管理员运行

取消
```bat
launchctl unload -w ~/Library/LaunchAgents/com.microsoft.EdgeUpdater.*.plist
```

恢复
```bat
launchctl load -w ~/Library/LaunchAgents/com.microsoft.EdgeUpdater.*.plist
```
