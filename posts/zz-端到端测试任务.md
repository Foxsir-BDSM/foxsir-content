---
title: 端到端测试任务（可删除）
slug: zz-端到端测试任务
content_type: task
risk: low
visibility: public
summary: 用于验证「接取 → 提交反馈」全链路的测试内容，验证完可删除。
cover_url: 
is_public: true
tags: ["测试"]
author_nickname: Foxsir
author_email: 
created_at: 2026-10-04T16:32:34.650Z
---

```json foxsir-post
{
 "type": "task",
 "meta": {
  "title": "端到端测试任务（可删除）",
  "slug": "zz-端到端测试任务",
  "content_type": "task",
  "risk": "low",
  "visibility": "public",
  "summary": "用于验证「接取 → 提交反馈」全链路的测试内容，验证完可删除。",
  "cover": "",
  "is_public": true,
  "tags": [
   "测试"
  ],
  "author_nickname": "Foxsir",
  "author_email": "",
  "createdAt": "2026-10-04T16:32:34.650Z"
 },
 "data": {
  "scenes": [
   "居家独处"
  ],
  "times": [
   "夜晚"
  ],
  "durationValue": 15,
  "durationUnit": "分钟",
  "env": "安静、不被打扰的私密空间；手机静音。",
  "pre": "确认身体状态良好，无不适；准备好一杯温水。",
  "mental": "以放松为前提，任何环节感到不适可随时停止。",
  "props": [
   {
    "text": "计时器",
    "required": true,
    "note": "手机即可"
   },
   {
    "text": "温水一杯",
    "required": false
   }
  ],
  "steps": [
   {
    "text": "静坐三分钟，把注意力放在呼吸上",
    "measure": "3 分钟"
   },
   {
    "text": "逐项回想今天发生的事，不做评判",
    "measure": "5 分钟"
   },
   {
    "text": "写下此刻最想对自己说的一句话",
    "measure": "3 分钟",
    "safety": "不想写可以跳过"
   },
   {
    "text": "伸展身体，缓慢结束",
    "measure": "4 分钟",
    "abort": "出现头晕等不适立即停止"
   }
  ],
  "checkpoints": [
   {
    "text": "全程是否保持了放松的呼吸"
   },
   {
    "text": "有没有出现被强迫的感觉"
   }
  ],
  "cleanup": "把写下的纸片收好或自行处理，整理好周边环境。",
  "body": "结束后喝点温水，做几次深呼吸。",
  "emotion": "如果过程中情绪起伏较大，给自己一点独处时间平复。",
  "observe": "24 小时"
 }
}
```

这是一条用于验证流程的测试任务，可随时删除。
