# 跳舞视频生成记录

## 基本信息

- **生成日期**: 2026-03-19 12:13
- **文件名**: dance_video.mp4
- **文件大小**: 2.4 MB
- **格式**: MP4 (720p)
- **时长**: 6 秒
- **模型**: PPIO Grok Imagine Video i2v

## 生成参数

```json
{
  "prompt": "A person dancing happily and energetically, smooth movements, upbeat rhythm, cinematic lighting",
  "duration": 6,
  "resolution": "720p",
  "api_endpoint": "https://api.ppio.com/v3/async/grok-imagine-video-i2v"
}
```

## 输入图片

- 来源: 用户上传
- 格式: JPEG (1080x1528)
- 文件路径: `3DE0EFFE90B6B8E5CD3349DF34AB0163_1773891958979.jpg`

## 生成过程

1. 图片转换为 base64 编码
2. 调用 PPIO Grok Imagine Video i2v API
3. 异步任务创建成功 (task_id: 6f47a8a3-060f-42c8-b526-707849aedf5c)
4. 等待76秒后视频生成完成
5. 下载并保存为 MP4 格式

## 直接下载链接

```
https://raw.githubusercontent.com/tonyli15903090018-crypto/AIGC-Hub/master/videos/dance_video.mp4
```

## 效果描述

视频展示了人物从静态图片中"动起来"的效果，执行流畅的舞蹈动作，具有动感和节奏感。
