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

## 向いている場面と解決できること

写真によっては、賑やかさより一つの記憶を支える紙面が必要です。**Panel 112** は写真の現実を残し、もう半分を米白の手漉き紙、横長の細い色域、小さな蝋クレヨン印章、極少量の金線へ圧縮します。静かな人物、旅、植物や器物、文芸表紙、私的記念、展示に向きます。

紙本表現が灰色で重くなること、金色が派手になること、完全描写が硬くなること、色面と装飾で画面を埋める問題を解決します。

## 原始プロンプト · 五言語

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中国語版は原文を逐語保存した実行時唯一の創作基準です。他の4言語は完全で忠実な閲覧訳です。

**特徴：** 二層手漉き紙 · 不規則な横長色域 · 深いマットな蝋クレヨン線 · 控えめな金線 · 小さな印章 · 越境する余白 · Risograph粒子

## クイック適性チェック

| 必要なこと | Panel 112 の答え |
|---|---|
| 静かで古風だが重くない紙本ポスター | 米白の手漉き紙、暗い蝋クレヨン線、少量の金線で記憶を支えます。 |
| 完全描写なしで主体を識別したい | 構造と気質を読み、中部の細い色域内の小さな印章へ圧縮します。 |
| 金色を派手にしたくない | 金線は重要輪郭だけ。上下の大余白と影の抑制で上品に保ちます。 |

## 変換ロジック

```text
構造と気質を読む → 不要な細部を削る → 中心形態を抽出 → 不規則な横長色域へ配置 → 暗い蝋クレヨン線・紙層・少量の金線で再構成 → 余白とRisograph粒子で完成
```

## 識別しやすい完成特徴

- 写真と二層紙デザインは一枚の完成画布に属し、比較モードは厳密な50:50で第三帯を作りません。
- 米白の粗い繊維紙を底に、中部へ細く不規則な横長综合色域と小さな印章主体を置きます。
- 深いマットな蝋クレヨン線はゆるく素朴。重要輪郭だけを極少量の金線で照らします。
- 主体は余白へ越境できますが、写実影や複雑装飾に頼らず、浅い古紙感とRisograph粒子を保ちます。
- 小さく柔らかな手書き英語が私的注記として入り、主役を奪いません。

## 機能と境界

4モード、複数比率／正確ピクセル、自動文案／正確文案／文字なし、ディレクトリ一括、連動／独立壁紙に対応します。ディレクトリは再帰的に数え、各画像を隔離して処理し、全PNGを一つの新規タスクフォルダー直下へ保存します。成果物は一回の完全画布生成で作り、中間画像・作例・別Panel作品を二次変換しません。`compose_panel.py` は最後の無劣化調整と監査だけに使います。

## 文字と言語

表示言語を明示します。`prompt` は原文の少量手書き英語、`exact` はユーザー文を逐語、`none` は全文字・数字・Logo・疑似文字を禁止します。人物、場所、ファイル名から言語を推測しません。

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

<!-- xxd-panel-catalog:start -->
## XXD Panel プロジェクト一覧

112個のPanelは、それぞれ独立した原文プロンプトと美学を保ちます。001〜112を連続して掲載し、現在のプロジェクトを太字で示します。

| Project | Style |
|---|---|
| [xxd-panel-001](https://github.com/nevertoday/xxd-panel-001) | 素朴な線 · レトロな紙肌 · 混合画材 · 気の利いた比喩 · 温かな余白 |
| [xxd-panel-002](https://github.com/nevertoday/xxd-panel-002) | 物語る輪郭 · ためらう線 · 類似色 · 部分拡大 · 版ずれ文字 |
| [xxd-panel-003](https://github.com/nevertoday/xxd-panel-003) | 連続する黒線 · 公共的主題 · 力点 · 沈黙の余白 · 解放 |
| [xxd-panel-004](https://github.com/nevertoday/xxd-panel-004) | 土地の現実 · 精密な単線 · 幾何学的遠近 · 主題色 · 都市ブランド文字 |
| [xxd-panel-005](https://github.com/nevertoday/xxd-panel-005) | 鈍い大形 · 暗い構造場 · 部分的な露出 · 三層の色秩序 · シルクスクリーン × パステル |
| [xxd-panel-006](https://github.com/nevertoday/xxd-panel-006) | 主体 10〜20% · 紙の余白 80〜90% · 細い手描き線 · 4色以内 · アクリル平塗り |
| [xxd-panel-007](https://github.com/nevertoday/xxd-panel-007) | 実物小図 · 接写／断面／反復 · ずれた余白 · 細い黒手書き · スキャン紙感 |
| [xxd-panel-008](https://github.com/nevertoday/xxd-panel-008) | 正投影アイソメトリック · 足場／階段／門 · 空間パラドックス · 動的パステル · マット 3D |
| [xxd-panel-009](https://github.com/nevertoday/xxd-panel-009) | 小さな主役 · 大きな余白 · 一つの空間関係 · 特色印刷 · ハーフトーン・シルクスクリーン |
| [xxd-panel-010](https://github.com/nevertoday/xxd-panel-010) | 粗い黒シルエット · 内側の白い特徴 · 乾式画材と紙目 · 最小限の環境記号 · 絵本の小文字 |
| [xxd-panel-011](https://github.com/nevertoday/xxd-panel-011) | 一つの核となる像 · 一組の関係 · 連続する黒線 · 能動的な余白 · 一点の記憶色 |
| [xxd-panel-012](https://github.com/nevertoday/xxd-panel-012) | 高密度の集積 · 外周への希薄化 · 幾何学的な制御 · 一つの生命色 · 黒灰のマイクロタイプ |
| [xxd-panel-013](https://github.com/nevertoday/xxd-panel-013) | 横長チケット一枚 · 74/26 分割 · 癒やし系水彩 · 象牙色の余白 · 現地語の情報スタブ |
| [xxd-panel-014](https://github.com/nevertoday/xxd-panel-014) | 折りと切面 · 重層と入れ子 · 元写真の重心 · 本物の紙繊維 · 読める紙文字 |
| [xxd-panel-015](https://github.com/nevertoday/xxd-panel-015) | 分解—選択—凝縮—再構成 · 少数の形 · 厳密な色役割 · 象牙色の余白 · アートブックの小文字 |
| [xxd-panel-016](https://github.com/nevertoday/xxd-panel-016) | ONE SUBJECT · ONE MOTION · A LARGE FIELD OF AIR |
| [xxd-panel-017](https://github.com/nevertoday/xxd-panel-017) | 丸い形 · 粗く途切れる線 · 純色の平塗り · 明るい色面 · 軽快な非対称 |
| [xxd-panel-018](https://github.com/nevertoday/xxd-panel-018) | 一つの視覚アンカー · 少数の前中後層 · 象牙色の余白 · マット紙 · 完全なマイクロタイプ |
| [xxd-panel-019](https://github.com/nevertoday/xxd-panel-019) | RECOGNISE FIRST · REDUCE WITH INTENT · COMPOSE WITH TYPE |
| [xxd-panel-020](https://github.com/nevertoday/xxd-panel-020) | 厚塗りの島 · 立体ミニチュア · 本物のナイフ跡 · 大きな紙面余白 · 抑制された編集文字 |
| [xxd-panel-021](https://github.com/nevertoday/xxd-panel-021) | 純黒矩形 · 主体の大半は内部 · 一つだけ越境 · 揺れるコピー線 · 白いネガ形と微小な灰色面 |
| [xxd-panel-022](https://github.com/nevertoday/xxd-panel-022) | 純黒矩形 · 主体の大半は内部 · 一つだけ越境 · 滑らかで安定した線 · 一点だけの色 |
| [xxd-panel-023](https://github.com/nevertoday/xxd-panel-023) | 元写真が選ぶ窓 · 淡く呼吸する背景 · 柔らかな色光 · スプレー粒子 · 虚実の投影と小文字 |
| [xxd-panel-024](https://github.com/nevertoday/xxd-panel-024) | 写真的な主体 · 細長い淡色窓 · 横／縦／斜めを元写真から選択 · 東洋の余白 · 高級編集 |
| [xxd-panel-025](https://github.com/nevertoday/xxd-panel-025) | 一目で主体 · 二目で隠れた像 · 図地反転 · 2〜4色のモランディ · 物理的なシルクスクリーン |
| [xxd-panel-026](https://github.com/nevertoday/xxd-panel-026) | RECOGNISE QUIETLY · REDUCE GENTLY · LET THE PAPER BREATHE |
| [xxd-panel-027](https://github.com/nevertoday/xxd-panel-027) | 厚い乳白紙 · 浅い凸凹 · 細い線刻 · 艶消し金の焦点 · 博物館の秩序 |
| [xxd-panel-028](https://github.com/nevertoday/xxd-panel-028) | 正投影アイソメトリック · 小さな紙の基台 · 元写真由来の色 · 細い墨線 · 編集的模型 |
| [xxd-panel-029](https://github.com/nevertoday/xxd-panel-029) | 横長の色面 · 淡いワックスパステル · 粗い手漉き紙 · リソグラフの粒子 · 力の抜けた手書き文字 |
| [xxd-panel-030](https://github.com/nevertoday/xxd-panel-030) | 本物の自然素材 · 矩形色面 · 自然な越境 · 最小限の黒線 · エディトリアルな余白 |
| [xxd-panel-031](https://github.com/nevertoday/xxd-panel-031) | 一つの核心モチーフ · 元写真由来の幾何母体 · 民俗図録 · 内部の粗い印痕 · 外部の精密な秩序 |
| [xxd-panel-032](https://github.com/nevertoday/xxd-panel-032) | 図文一体 · 文字体系に忠実な字形 · 元写真の特徴を埋め込む · 光学的字間 · 上質な余白 |
| [xxd-panel-033](https://github.com/nevertoday/xxd-panel-033) | 識別できるモチーフ · 平面コラージュ · 尺度対比 · 元写真由来の鮮色 · カバー組版 |
| [xxd-panel-034](https://github.com/nevertoday/xxd-panel-034) | 小さな印影 · 2〜4色の特色 · 手彫り線 · 温かな紙 · フィールド注記 |
| [xxd-panel-035](https://github.com/nevertoday/xxd-panel-035) | 一つのブロック主体 · 元写真由来の鮮色 · マットABS · 静かな背景 · モジュラー文字 |
| [xxd-panel-036](https://github.com/nevertoday/xxd-panel-036) | 一つの関係 · 細い連続線 · 2〜4色域 · 水彩の縁 · 呼吸する余白 |
| [xxd-panel-037](https://github.com/nevertoday/xxd-panel-037) | 一枚の徽章 · 元写真のエナメル色 · 白金属縁 · 流金の細部 · 実在する短い影 |
| [xxd-panel-038](https://github.com/nevertoday/xxd-panel-038) | 元写真の布色 · ほつれた縁 · 手縫い · 能動的余白 · 隠れた感情 |
| [xxd-panel-039](https://github.com/nevertoday/xxd-panel-039) | 一図一核 · 中国の絹糸 · 針方向の層 · 清潔な地 · 東洋の余白 |
| [xxd-panel-040](https://github.com/nevertoday/xxd-panel-040) | 実在する主役 · 黒い線画の小人 · ミクロな物語 · 大きな余白 |
| [xxd-panel-041](https://github.com/nevertoday/xxd-panel-041) | テーマ比喩 · 等距秩序 · 淡い手稿 · 和色の透明感 · 東洋の余白 |
| [xxd-panel-042](https://github.com/nevertoday/xxd-panel-042) | 元の視点 · 2〜5の真の層 · 安定した基点 · 透明水彩 · 編集注記 |
| [xxd-panel-043](https://github.com/nevertoday/xxd-panel-043) | 本物の泡 · 正面フラットレイ · 元写真由来の暗色地 · 微細気泡の縁 · 静かな空間 |
| [xxd-panel-044](https://github.com/nevertoday/xxd-panel-044) | 薄層の純金 · 正面平面 · 元写真由来の暗色地 · 鎚目 · 静かな秩序 |
| [xxd-panel-045](https://github.com/nevertoday/xxd-panel-045) | 丸いモジュール · 元写真の色 · 等距奥行 · マットな触感 · 編集ミクロ組版 |
| [xxd-panel-046](https://github.com/nevertoday/xxd-panel-046) | 明るい白地 · 鮮やかな厚塗り · 微縮の実体感 · 斜めの色面 · 温かな光 |
| [xxd-panel-047](https://github.com/nevertoday/xxd-panel-047) | 等距ミニチュア · 主題的厚塗り · 実在接触 · 暖白紙 · 明るい色 |
| [xxd-panel-048](https://github.com/nevertoday/xxd-panel-048) | 透明構造 · 科学図解 · 明澄な単色 · 精密注釈 · 編集的余白 |
| [xxd-panel-049](https://github.com/nevertoday/xxd-panel-049) | 限定色木版 · 手彫りの跡 · マットな重ね刷り · 暖かな紙 · 不完全な縁 |
| [xxd-panel-050](https://github.com/nevertoday/xxd-panel-050) | 専用トラベルシーン · エアリーブルー · ミニマルなフラットベクター · 編集的余白 · 一枚ごとの固有性 |
| [xxd-panel-051](https://github.com/nevertoday/xxd-panel-051) | ミニチュア紙工芸 · 横長の浮遊景観帯 · 手仕事の証拠 · エアリーブルー · 大きな余白 |
| [xxd-panel-052](https://github.com/nevertoday/xxd-panel-052) | ペーパークラフト · 横長の浮島 · 本物の手仕事 · 空気感のある寒色ブルー · 広い余白 |
| [xxd-panel-053](https://github.com/nevertoday/xxd-panel-053) | 観察ペン線 · 透明な淡彩 · 音楽的リズム · ほぼ白い紙 · 能動的な余白 |
| [xxd-panel-054](https://github.com/nevertoday/xxd-panel-054) | 選択的記憶 · 主役 · 六枚のステッカー · マット印刷 · 空気感のある青 |
| [xxd-panel-055](https://github.com/nevertoday/xxd-panel-055) | 主体の物語 · 癒やしのパステル · 淡い油彩筆触 · 空気感のある青 · 編集的余白 |
| [xxd-panel-056](https://github.com/nevertoday/xxd-panel-056) | 核心イメージ · 巨大な余白 · 暖冷の跳色 · 稚拙な手描き · 視覚的比喩 |
| [xxd-panel-057](https://github.com/nevertoday/xxd-panel-057) | 幾何構成 · インテリジェント・モザイク · 建築図解 · アートマップ · 暖冷の色面 |
| [xxd-panel-058](https://github.com/nevertoday/xxd-panel-058) | 潜台詞の読解 · 幾何学的ミニマリズム · コンセプト風景 · 柔らかな手仕事感 · 淡い余白 |
| [xxd-panel-059](https://github.com/nevertoday/xxd-panel-059) | 手描きの物語 · 童心の比喩 · 温かな紙感 · ほのかなユーモア · 詩的な傍白 |
| [xxd-panel-060](https://github.com/nevertoday/xxd-panel-060) | 黒い主形 · 巨大な余白 · 網点消散 · 禅的思考 · 思索の断片 |
| [xxd-panel-061](https://github.com/nevertoday/xxd-panel-061) | 選択的記憶 · 3–6断片 · 切り紙色面 · Risograph · 即興編集レイアウト |
| [xxd-panel-062](https://github.com/nevertoday/xxd-panel-062) | 極細黒線 · 単一強調色 · 賢い不器用さ · 淡い紙 · 専門的余白 |
| [xxd-panel-063](https://github.com/nevertoday/xxd-panel-063) | 中心Mask · ピクセル形体 · 負形の入れ子 · 軽いglitch · 限定色 |
| [xxd-panel-064](https://github.com/nevertoday/xxd-panel-064) | 手ちぎり紙 · 古紙コラージュ · 鉛筆と墨 · タイプライター小字 · 詩的アーカイブ |
| [xxd-panel-065](https://github.com/nevertoday/xxd-panel-065) | 黒い構造線 · 元画像由来の二色線 · 版ずれ · 旧印刷リズム · 微細組版 |
| [xxd-panel-066](https://github.com/nevertoday/xxd-panel-066) | 童真的物語 · 不器用な黒線 · 3–6色平塗り · 癒やし色 · 手書き観察 |
| [xxd-panel-067](https://github.com/nevertoday/xxd-panel-067) | 固定赤青 · 手描き二色墨 · 童真ユーモア · 日常観察 · 淡い紙 |
| [xxd-panel-068](https://github.com/nevertoday/xxd-panel-068) | 経営位置 · 計白当黒 · 墨線淡彩 · 東方題跋 · 現代編集 · 清雅な余白 |
| [xxd-panel-069](https://github.com/nevertoday/xxd-panel-069) | 粗筆ウィンドウ · 鮮活な元画像色 · 繊細な輪郭 · 越境関係 · 暖白の余白 |
| [xxd-panel-070](https://github.com/nevertoday/xxd-panel-070) | 手描き輪郭 · 明るい厚塗り／半透明色面 · ミニチュア主体 · 暖白の余白 · タイプライター風編集書体 |
| [xxd-panel-071](https://github.com/nevertoday/xxd-panel-071) | 柔らかなパステル · パステルクレヨン · 水溶性色鉛筆 · 白に近い紙面 · 浮遊する記憶 · 詩的な手書き文字 |
| [xxd-panel-072](https://github.com/nevertoday/xxd-panel-072) | 半透明すりガラス窓 · 領域差ソフトフォーカス · ミニマル幾何学 · 識別輪郭 · 現代編集文字 |
| [xxd-panel-073](https://github.com/nevertoday/xxd-panel-073) | 等角投影微縮建築 · 切断立方体 · 大陸棚断面 · 合理的足場 · 白いテクスチャ紙 |
| [xxd-panel-074](https://github.com/nevertoday/xxd-panel-074) | 標準角丸正方形 · 正面擬似3D／2.5D · 元写真の魂 · 連続遮蔽 · マット彫刻 · ブランドアイコン |
| [xxd-panel-075](https://github.com/nevertoday/xxd-panel-075) | 濃色クレヨン · アイボリー手工紙 · 柔らかな不定形色面 · リソグラフ粒子 · 大きな余白 · 私的注記 |
| [xxd-panel-076](https://github.com/nevertoday/xxd-panel-076) | 粗い濃色クレヨン · 木炭 · 明るいマカロン色面 · 45%連続余白 · 天然紙 · 観察注記 |
| [xxd-panel-077](https://github.com/nevertoday/xxd-panel-077) | ミニマル紙彫刻 · 明瞭な切り紙輪郭 · 前後レイヤー · 柔らかな影 · 人間的マカロン · 旅行誌組版 |
| [xxd-panel-078](https://github.com/nevertoday/xxd-panel-078) | アイボリーコットン紙 · 深い凹圧 · 凹溝シャンパン金箔 · 繊細線形標章 · 無インク空押し · 控えめな高級感 |
| [xxd-panel-079](https://github.com/nevertoday/xxd-panel-079) | 強い幾何直線 · 自由な有機曲線 · ペン淡彩 · 未完成感 · 広い紙白 · 編集的な図文構成 |
| [xxd-panel-080](https://github.com/nevertoday/xxd-panel-080) | 柔らかな有機幾何 · デジタルガッシュ · クレヨン粒子 · 植物系配色 · 自然な比喩 · 感情の余白 |
| [xxd-panel-081](https://github.com/nevertoday/xxd-panel-081) | 均一彩色モノライン · 開いた輪郭 · 密度階層 · 2–4色特色 · リソグラフ粒子 · 私的記念叙事 |
| [xxd-panel-082](https://github.com/nevertoday/xxd-panel-082) | 不規則水彩色域 · Naïve + Wonky · Isometric／2.5D · 素朴な輪郭 · 鮮やかな色 · 立体主役 |
| [xxd-panel-083](https://github.com/nevertoday/xxd-panel-083) | Ugly-cute 落書き · Wonky 輪郭 · 制御された不正確さ · 一人のユーモア主役 · 粗いクレヨン · 少・変・不器用・正確 |
| [xxd-panel-084](https://github.com/nevertoday/xxd-panel-084) | ミニマル都市線描 · 幾何学骨格 · 密度点描 · 透視リーディングライン · 限定色 · 詩的余白 |
| [xxd-panel-085](https://github.com/nevertoday/xxd-panel-085) | 手工微縮舞台 · コレクション向け立体表紙 · 粘土とフェルト · 切り紙と糸 · マットな触感 · 芸術的余白 |
| [xxd-panel-086](https://github.com/nevertoday/xxd-panel-086) | ミッドセンチュリー・モダニズム限定色シルクスクリーン · シルエット幾何 · 2–4色特色 · ドライブラシ · 一つの焦点 · 大きな余白 |
| [xxd-panel-087](https://github.com/nevertoday/xxd-panel-087) | 実体糸の関係システム地図 · ピンの節点 · 朱色の糸 · 関係写像 · 創発幾何 · 研究壁の余白 |
| [xxd-panel-088](https://github.com/nevertoday/xxd-panel-088) | 実験的文字画像構成 · 文字即画像 · 解体組版 · ドット輪郭 · 文字密度勾配 · 視覚詩 |
| [xxd-panel-089](https://github.com/nevertoday/xxd-panel-089) | 私的生活手帳スケッチ · 一人の主役 · 少数の日常断片 · 緩い手描き線 · 水彩と色鉛筆 · 成熟した余白 |
| [xxd-panel-090](https://github.com/nevertoday/xxd-panel-090) | 図式的ビジュアル思考マップ · 概念中心 · 文字ノード · 幾何骨格 · 軌跡矢印 · 視覚記譜 · 大きな余白 |
| [xxd-panel-091](https://github.com/nevertoday/xxd-panel-091) | 単色青ペン物語スケッチ · コバルト／ペンブルー／群青／藍 · 方向ハッチング · 探索線 · 自然な紙白 |
| [xxd-panel-092](https://github.com/nevertoday/xxd-panel-092) | Expressive pen · loose contours · geometric and scribble hatching · negative-space composition |
| [xxd-panel-093](https://github.com/nevertoday/xxd-panel-093) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-094](https://github.com/nevertoday/xxd-panel-094) | Fine pen-and-ink · selective solid black · source-derived spot colour · vast negative space · vintage book illustration |
| [xxd-panel-095](https://github.com/nevertoday/xxd-panel-095) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-096](https://github.com/nevertoday/xxd-panel-096) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-097](https://github.com/nevertoday/xxd-panel-097) | Mid-century vernacular commercial graphic · schematic line drawing · two-colour spot printing · functional humour |
| [xxd-panel-098](https://github.com/nevertoday/xxd-panel-098) | 擬素朴水彩絵本挿絵 · 緩い墨線 · 平面水彩／ガッシュ · 記号的造形 · 天真な遠近 · 成熟した物語構図 |
| [xxd-panel-099](https://github.com/nevertoday/xxd-panel-099) | ブランドマスコット平面ベクター · 太い黒輪郭 · 丸い幾何 · 誇張比率 · 2–4色ブランド配色 · 超大文字背景 |
| [xxd-panel-100](https://github.com/nevertoday/xxd-panel-100) | 稚拙な民藝感の平面物語 · primitive forms · 簡略シルエット · flattened perspective · クレヨン／オイルパステル粒子 · 暖白紙 · 鮮やかな限定色 |
| [xxd-panel-101](https://github.com/nevertoday/xxd-panel-101) | 3×3記憶アイコン · 個人手帳感 · 稚拙な落書き · レトロなキャンディ色 · 手書き注記 |
| [xxd-panel-102](https://github.com/nevertoday/xxd-panel-102) | 癒やしの幾何学 · 柔らかな形 · 平面構成 · 温かな色 · 軽やかな余白 |
| [xxd-panel-103](https://github.com/nevertoday/xxd-panel-103) | 鮮彩抽象コラージュ · 大きな色面 · 抽象的な分解と再結合 · 高明度配色 · 強いリズム |
| [xxd-panel-104](https://github.com/nevertoday/xxd-panel-104) | 網点印刷 · 彩色線の介入 · 一つの視覚的重心 · 禅的な余白 |
| [xxd-panel-105](https://github.com/nevertoday/xxd-panel-105) | 知的な審美選択 · 一つの視覚的重心 · 詩的ミニマル紙本コラージュ · モノプリント／シルクスクリーン／Risograph 肌理 · 柔らかな限定色 · 大きな余白 |
| [xxd-panel-106](https://github.com/nevertoday/xxd-panel-106) | 柔彩ピクセル記憶 · 2〜4個の視覚アンカー · 規則グリッド · モジュール色面 · 部分ディザリング · 一つの視覚的中心 · 大きな余白 |
| [xxd-panel-107](https://github.com/nevertoday/xxd-panel-107) | 画像ことば詩 · 読める判じ絵文 · 現代手描き画像語 · 明るく柔らかな色面 · 厳密な50:50二分 · 大きな余白 |
| [xxd-panel-108](https://github.com/nevertoday/xxd-panel-108) | 現代民芸切り紙 · 簡略シルエット · 手ちぎり端 · 元写真の鮮色 · 印刷肌理 · 大余白 |
| [xxd-panel-109](https://github.com/nevertoday/xxd-panel-109) | モダニズム幾何コラージュ · 大型モジュール · 柔色 · 紙粒子 · 抑制された編集秩序 |
| [xxd-panel-110](https://github.com/nevertoday/xxd-panel-110) | 日系生活シーン図鑑 · 4〜7個の実在断片 · アクリル収集品 · 動的経路 · 癒やしの余白 |
| [xxd-panel-111](https://github.com/nevertoday/xxd-panel-111) | テキスタイル・コラージュ誌 · 手縫いアップリケ · 見える針目 · 2〜4色の布 · 小さな印章 · 大余白 |
| **[xxd-panel-112](https://github.com/nevertoday/xxd-panel-112)** | 金線ペーパー誌 · 二層手漉き紙 · 横長の細い色域 · 暗い蝋クレヨン線 · 控えめな金線 · Risograph粒子 |
<!-- xxd-panel-catalog:end -->

## ライセンス

本プロジェクトは **PolyForm Noncommercial License 1.0.0** で提供されます。全文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

- 個人の学習・研究・実験・テスト・趣味・私的娯楽と、対象となる公益組織の利用が許可されます。
- 非営利目的なら使用・複製・改変・派生物作成・配布ができますが、ライセンスと通知を添付してください。
- 商用製品・サービス、対価を受ける納品、アクセス販売、商用利用予定には別途書面許可が必要です。
- 明記された著作権と限定的特許権だけを許諾し、商標・ブランド名・再許諾の権利は含みません。
- 書面の違反通知を受けた場合は32日以内に是正と実質的な補救を行わなければ、許諾が終了します。
- プロジェクトは「現状のまま」無保証で提供され、法の範囲内で利用者がリスクを負います。
