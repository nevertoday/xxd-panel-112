<div align="center">

# XXD Panel 112｜金線ペーパー誌

不規則な紙の色面に、静かに光る記憶をひとつ留める。

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## サンプル

**16:9 横長・左右サンプル**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 縦長・上下サンプル**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

8点は異なる元画像から独立生成しました。横長は写真が左・デザインが右、縦長は写真が上・デザインが下です。英語の自動文案を使い、50:50の二領域を確認済みです。

写真の魅力は情報量ではなく、関係や手触り、間に宿ることがあります。このPanelは写真の現実を残し、もう一方を独立した紙上の視覚言語へ翻訳します。アートポスター、出版、展示、SNS、デザイン専用出力に適しています。

写真とデザインの分離、装飾過多、余白不足、比率ごとの不安定さを解決します。

## 原始プロンプト · 五言語

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 4つの出力モード

- `top-bottom`：現実写真を上、Panel 112 のデザインを下に、各50%。
- `left-right`：現実写真を左、デザインを右に、各50%。上下へ回転しません。
- `design-only`：全画面を本Panelのデザインだけにし、写真は参照のみ。
- `wallpaper-pack`：端末ごとに完全なキャンバスを生成します。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-112.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-112" ~/.codex/skills/xxd-panel-112
```

`npx skills` でも直接インストールできます：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-112 --skill xxd-panel-112
```

GitHubから取得して同名のSkillをインストールします。ユーザー単位のCodexには `--global --agent codex --yes` を追加してください。

インストール後にAgentセッションを再起動して呼び出します `$xxd-panel-112`.

## ライセンス

本プロジェクトは **PolyForm Noncommercial License 1.0.0** で提供されます。全文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

- 個人の学習・研究・実験・テスト・趣味・私的娯楽と、対象となる公益組織の利用が許可されます。
- 非営利目的なら使用・複製・改変・派生物作成・配布ができますが、ライセンスと通知を添付してください。
- 商用製品・サービス、対価を受ける納品、アクセス販売、商用利用予定には別途書面許可が必要です。
