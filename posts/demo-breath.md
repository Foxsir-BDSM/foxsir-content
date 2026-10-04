---
title: 【示例】三段呼吸放松
slug: demo-breath
content_type: task
risk: low
visibility: public
summary: 一个结构完整的示例任务，用于验证接取流程。可随时删除。
cover_url: 
is_public: true
tags: ["示例","放松"]
author_nickname: Foxsir
author_email: 
created_at: 2026-10-04T16:42:03.631Z
---

```json foxsir-post
{
 "type": "task",
 "meta": {
  "title": "【示例】三段呼吸放松",
  "slug": "demo-breath",
  "content_type": "task",
  "risk": "low",
  "visibility": "public",
  "summary": "一个结构完整的示例任务，用于验证接取流程。可随时删除。",
  "cover": "",
  "is_public": true,
  "tags": [
   "示例",
   "放松"
  ],
  "author_nickname": "Foxsir",
  "author_email": "",
  "createdAt": "2026-10-04T16:42:03.631Z"
 },
 "data": {
  "scenes": [
   "居家独处"
  ],
  "times": [
   "夜晚",
   "任意"
  ],
  "durationValue": 15,
  "durationUnit": "分钟",
  "env": "安静、不被打扰的空间。手机静音，坐姿或躺姿均可。",
  "pre": "确认身体状态良好；准备一杯温水放在手边。",
  "mental": "以放松本身为目的，不追求任何结果。任何环节不适可随时停止。",
  "props": [
   {
    "text": "计时器",
    "required": true,
    "note": "手机计时即可"
   },
   {
    "text": "温水一杯",
    "required": false
   },
   {
    "text": "毯子",
    "required": false,
    "alt": "外套亦可"
   }
  ],
  "steps": [
   {
    "text": "静坐，把注意力放在呼吸上，不做任何调整",
    "measure": "3 分钟"
   },
   {
    "text": "缓慢深呼吸，吸气 4 拍、呼气 6 拍",
    "measure": "5 分钟",
    "safety": "出现头晕立即恢复自然呼吸"
   },
   {
    "text": "把注意力依次扫过全身，逐处放松",
    "measure": "4 分钟"
   },
   {
    "text": "静坐片刻，再缓慢起身",
    "measure": "3 分钟",
    "abort": "起身时若感眩晕，先坐回原处"
   }
  ],
  "checkpoints": [
   {
    "text": "全程呼吸是否自然，没有刻意憋气"
   },
   {
    "text": "身体有没有某处一直紧绷未能放松"
   },
   {
    "text": "中途是否被手机或杂念打断"
   }
  ],
  "cleanup": "收好计时器，把水杯放回原处。",
  "body": "结束后喝几口温水，活动一下肩颈。",
  "emotion": "如过程中情绪起伏较大，给自己一点安静时间平复。",
  "observe": "当天余下时间留意身体感受"
 }
}
```

这是一个**示例任务**，用于验证「接取 → 提交反馈」的完整链路。

结构里包含场景、时长、道具、步骤、检查点与收尾，目的在于展示 `玩法任务` 类型支持的字段。内容可随时删除。
