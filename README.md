# fast-video-switcher
### 项目价值
1. 用户画像：18-25岁年轻人
2. 需求背景：用户下载了很多视频，但是在使用播放器进行观看时，视频间切换十分麻烦，需要退出当前视频，然后再进入另一个视频
3. 技术背景：这个项目利用H5对于Video的原生支持，编写了一个新的视频播放器video-player

### 功能
1. 自动识别目录下的所有mp4视频
2. 基于浏览器观看视频
3. 快速切换视频
4. 根据视频列表选择视频
5. 速度控制条

### 这是一个前后端分离项目
- 前端启动：atom代码编辑器 liver-server插件 非8081端口启动
- 后端启动：nodejs（fs、express、path）8081端口启动

### 用法
#### 将两个文件下载到你的视频文件夹中
命令行输入
```
node app.js
```
#### 命令行显示：启动成功
浏览器输入
```
http://127.0.0.1:3000/player.html
```

---
### 2022-12-16 UPDATE
- 修改列表的呈现方式：将新添加的视频放在列表顶部
- 修改了视频列表中必须有视频准备的用户体验问题
- 添加了丝滑的速度控制条
