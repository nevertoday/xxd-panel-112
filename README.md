<div align="center">

# XXD Panel 112｜金线纸本志

让一块不规整的纸面色域，托住一枚安静而闪光的记忆

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 样张展示

**16:9 横版左右样张**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 竖版上下样张**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

以上八张由本 Panel 从不同原始参考图独立生成：横版为原图在左、设计在右；竖版为原图在上、设计在下；全部使用英文智能文案并通过严格 50:50 双区检查。

有些照片最动人的地方，不是信息量，而是某种关系、触感或停顿。这个 Panel 保留照片的现实部分，再把另一半转译成独立的纸上视觉语言，适合艺术海报、独立出版、展览图像、社交内容和纯设计图。

它解决照片与设计各说各话、主体被过度装饰、留白不足，以及同一审美无法稳定交付不同画幅的问题。

## 原始提示词 · 五种语言

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 四种输出模式

- `top-bottom`：现实照片在上，Panel 112 设计在下，严格各占 50%。
- `left-right`：现实照片在左，设计在右，严格各占 50%，不会旋转成上下结构。
- `design-only`：整张画布只呈现本 Panel 的设计转译，照片只作参考。
- `wallpaper-pack`：按设备分别生成完整画布。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-112.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-112" ~/.codex/skills/xxd-panel-112
```

也可以直接使用 `npx skills` 安装：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-112 --skill xxd-panel-112
```

命令会从 GitHub 获取仓库并安装同名 Skill；需要用户级 Codex 安装时，可追加 `--global --agent codex --yes`。

安装后重新启动 Agent 会话，然后调用 `$xxd-panel-112`。

## 许可证

本项目采用 **PolyForm Noncommercial License 1.0.0**。完整法律文本见 [LICENSE](LICENSE)，官方页面：<https://polyformproject.org/licenses/noncommercial/1.0.0>。

- 允许个人学习、研究、实验、测试、兴趣项目、私人娱乐，以及符合协议定义的非商业组织使用。
- 非商业用途可使用、复制、修改、制作衍生作品和分发，但必须附带许可证及 Required Notice。
- 商业产品、服务、收费交付、出售访问权或预期商业应用需要另行书面许可。
