# WeChat Cover Studio

一个用于生成或修改微信公众号文章封面的 Codex skill。输入产品 Logo、主标题、副标题，以及可选的背景参考图或视觉方向，即可生成 2.35:1 的公众号横版封面。

这个仓库保留了真实使用中沉淀的核心规则、完整提示词、优质成图和失败案例，用于校准背景选择、Logo 使用、文字准确性、字号与视觉层次。

## 安装

将仓库克隆或下载到 Codex 的 skills 目录：

```bash
git clone https://github.com/54singa/wechat-cover-studio.git ~/.codex/skills/wechat-cover-studio
```

重新打开 Codex 后，可以通过 `$wechat-cover-studio` 调用。

## 使用示例

```text
使用 $wechat-cover-studio，根据我提供的 Logo、主标题、副标题和背景参考图直接生成公众号封面。

主标题：GPT image2.5实测
副标题：草图生图可以给到夯
背景：参考附件里的斗鱼、红青鳞光和微距摄影质感
```

## 推荐输入

- 产品 Logo
- 主标题
- 副标题
- 与主题或产品有关的视觉元素、案例图，或一句明确的背景方向

背景参考不是必填项。没有参考图时，skill 会根据产品和标题自行选择视觉概念。

## 目录

- `SKILL.md`：核心工作流和验收规则
- `references/cases.md`：正反例索引
- `references/prompts/`：历史案例的完整提示词
- `references/images/`：用于风格校准的正反例图片
- `references/feedback.md`：用户修改反馈与优先级

历史案例只用于学习风格与判断标准，不授权复用其中的品牌、人物或文案。
