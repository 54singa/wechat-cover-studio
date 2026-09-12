# 案例索引

先选最接近当前任务的案例，读取提示词并打开图片；结合 feedback.md 应用修正。以下图片由用户主动标记为优质案例或负例，非算法评分。
“原始提示词”链接保留 GPT 的完整回复及当轮用户要求。缺失原始 GPT 提示词的案例只记录可证实资料，不补写后冒充原文。

| 案例 | 图片 | 适用经验 | 原始文字 |
|---|---|---|---|
| Kimi K3 | [正例](images/kimi-good.png) | 城堡、海浪、雷雨的电影画面；左上小幅衬线标题，主体占画面 | 原图为用户最初参考；原始生成提示词未获取 |
| MiniMax H3 | [正例](images/minimax-good.png)、[负例](images/minimax-bad-extra.png) | 真实商业产品案例，明亮蓝白海水、青柠、水花；需要保留具体产品 | [完整原文](prompts/minimax.md)；删除额外信息卡和未指定卖点文案 |
| Wan 3.0 | [正例](images/wan-good.png)、[负例](images/wan-bad-large.png) | 暖纸白、墨黑与宫殿橙，艺术作品优先；字体不能挤满左侧 | [完整原文](prompts/wan.md)；后续改副标题为“阿里这波确实有点东西” |
| DSH Harness v0.1 | [正例](images/dsh-ring-good.png) | 用户参考支持的光环背景，黑底橙紫流光，鲸鱼图标在标题上方 | source-conversation.md 搜索“DeepSeek Harness v0.1”；未返回 GPT 原始提示词 |
| DSH Harness 插件 | [正例](images/dsh-whale-good.png)、[负例](images/dsh-whale-bad-text.png) | 最重要的文字方向生成案例：蓝色系、右边鲸鱼；深色留白、流动轨迹与渐变副标题 | [完整原文](prompts/dsh-whale.md)；修正错字与偏小字号 |
| EvoX | [正例](images/evox-good.png) | 完整白色图标字标，深色有厚度蜂巢，局部橙紫单元和连接；不要全部点亮 | [完整原文](prompts/evox.md)；副标题避免单薄 |
| Qwen3.8-27B | [正例](images/qwen-good.png) | 参考中的几何装置与地球轨道、冷暖轮廓光；可左右交换图文 | [完整原文](prompts/qwen.md)；后续布局和图标不变形指令优先 |
| 百度搭子 | [正例](images/baidu-good.png) | 提取参考中的品牌模块和图标，构成右侧主视觉；深色左侧保证文字可读 | source-conversation.md 搜索“百度搭子”；未返回 GPT 原始提示词 |
| Qoder | [正例](images/qoder-good.png) | 代码到产品界面的有方向层次，黑橙少量酸绿；为其中一种方向 | [完整原文](prompts/qoder.md)；用户后续要求换风格，不固化 |
| GPT-6 Astra | [正例](images/astra-good.png) | 从用户参考的座椅/屏幕场景扩展为人机观看宇宙，暖室内与冷地球 | source-conversation.md 搜索“1979”；原图年份后续要求改为 2026；未返回 GPT 原始提示词 |
| 豆包工作风景 | 无已确认的最终成图 | 仅作为无参考图时换方向的文字方案：日出山路、自然摄影，品牌色小面积点缀 | [完整原文](prompts/doubao-landscape.md)；不要冒充已确认视觉正例 |
| 豆包办公人物 | 无确认成图 | 历史备选方案，之后用户不满意反复办公场景，要求换方向 | [完整原文](prompts/doubao-office.md)；只按需使用，非默认推荐 |

## 选择提示

- 已有作品：MiniMax / Wan / Kimi 的“作品本身就是封面主视觉”。
- 品牌参考元素：Qwen / 百度搭子 / DSH 光环。
- 一句背景方向：DSH 鲸鱼为最完整正例。
- Coding 主题：Qoder 提供材质与层次参考，但用户想换风格时必须换概念。
- 非字面产品场景：Astra / Kimi / 豆包风景方案；不要硬加 AI 元素。
- 字号与装饰：查看对应正反例，不只套用原始提示词里的百分比。

正例不授权复用其他品牌、标题、作品或人物作为当前背景；用户素材为本次内容依据。历史图用于风格和质量尺度。

