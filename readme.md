#### ionic

```
# 最新版 ionic CLI
npm install -g @ionic/cli@latest

# 创建项目
ionic start myApp tabs --type vue

# 启动服务
ionic server
```
#### capacitor
```
# 添加Capacitor
ionic integrations enable capacitor

ionic cap add ios
ionic cap add android

ionic build
# 修改代码执行
ionic cap copy
# 插件更新执行
ionic cap sync

# 打开原生ide
ionic cap open ios
ionic cap open android

# 实时更新
ionic cap run ios -l --external
ionic cap run android -l --external
```