# 视频下载

本页面介绍如何使用 XHS1 下载小红书视频。

## 功能特点

- 支持单个视频下载
- 支持批量视频下载
- 自动提取视频标题和描述
- 支持自定义保存路径
- 支持下载进度显示
- 支持下载历史记录

## 使用方法

### 单个视频下载

1. 复制视频链接
   - 在小红书 App 中点击分享按钮
   - 选择"复制链接"
   - 或直接复制浏览器地址栏的链接

2. 粘贴链接
   - 打开 XHS1 主页
   - 将链接粘贴到输入框中

3. 开始下载
   - 点击"下载"按钮
   - 等待下载完成
   - 视频将保存到默认下载目录

### 批量下载

1. 准备链接列表
   - 创建文本文件，每行一个链接
   - 或使用 Excel/CSV 文件（第一列为链接）

2. 导入链接
   - 点击"批量下载"按钮
   - 选择导入方式：
     - 上传文本文件
     - 上传 Excel/CSV
     - 直接粘贴多行链接

3. 开始批量下载
   - 确认链接列表
   - 点击"开始下载"
   - 查看下载进度

## 下载设置

### 保存路径

1. 默认路径
   - Windows: `%USERPROFILE%/Downloads/xhs-videos`
   - macOS: `~/Downloads/xhs-videos`
   - Linux: `~/Downloads/xhs-videos`

2. 自定义路径
   - 点击设置图标
   - 进入"下载设置"
   - 选择自定义保存路径

### 文件命名

默认命名格式：`[作者]-[标题]-[日期]-[ID]`

可自定义的命名变量：
- `{author}`: 作者昵称
- `{title}`: 视频标题
- `{date}`: 发布日期
- `{id}`: 视频ID
- `{custom}`: 自定义文本

### 下载选项

- 是否下载封面图
- 是否下载视频描述
- 是否创建作者子文件夹
- 下载完成后是否通知
- 失败重试次数
- 并发下载数量

## 下载历史

### 查看历史记录

1. 点击"历史记录"标签
2. 可以查看：
   - 下载时间
   - 视频信息
   - 下载状态
   - 保存路径

### 管理历史记录

- 搜索历史记录
- 删除单条记录
- 清空历史记录
- 导出下载历史

## 常见问题

### 下载失败的原因

1. 网络问题
   - 检查网络连接
   - 尝试更换代理

2. 链接失效
   - 确认链接是否可访问
   - 尝试重新获取链接

3. 权限问题
   - 检查保存路径权限
   - 尝试更换保存位置

### 视频质量选择

- 自动选择最高质量
- 可手动选择清晰度：
  - 1080p
  - 720p
  - 480p
  - 360p

### 批量下载注意事项

- 建议单次不超过 50 个链接
- 注意磁盘空间是否充足
- 可能需要更长的处理时间
- 建议使用代理避免 IP 限制

## 相关链接

- [代理设置](/guide/proxy-settings)
- [数据持久化](/guide/data-persistence)
- [常见问题](/guide/faq) 