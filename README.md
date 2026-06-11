# NanoLimbo

### 自动构建server.jar指南

1：点击Use this template ➡ Create a new repostory 创建一个私密项目

2：在Actions菜单允许 `I understand my workflows, go ahead and enable them` 按钮

3: 击下方文件名直达文件
- [NanoLimbo.java](./src/ws/java/ua/nanit/limbo/NanoLimbo.java)

4: 修改NanoLimbo.java文件里 195到201 行中添加需要的环境变量，不需要的留空，保存后Actions会自动构建

5：等待2分钟左右，在右侧的Release里下载server.jar文件


### 环境变量说明(可带.env放同路径下运行)
```
UUID=bda7ffa5-5b3a-4037-80ae-27e9bbde7f19
NEZHA_SERVER=nezha.xxx.com
NEZHA_KET=xxxxx
```
或
```
export UUID=bda7ffa5-5b3a-4037-80ae-27e9bbde7f19
export NEZHA_SERVER=nezha.xxx.com
export NEZHA_KET=xxxxx
```
