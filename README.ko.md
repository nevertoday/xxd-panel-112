<div align="center">

# XXD Panel 112｜금선 종이 기록

불규칙한 종이 색면 위에 조용히 빛나는 기억 하나를 담다.

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

## 샘플 작품

**16:9 가로 좌우 샘플**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 세로 상하 샘플**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

8장은 서로 다른 원본 참고 이미지에서 독립 생성했습니다. 가로는 원본 왼쪽·디자인 오른쪽, 세로는 원본 위·디자인 아래이며 영어 자동 문구와 엄격한 50:50 이중 영역 검사를 적용했습니다.

사진의 매력은 정보량보다 관계와 촉감, 멈춤에 있을 때가 많습니다. 이 Panel은 사진의 현실을 유지하고 다른 절반을 독립적인 종이 기반 시각 언어로 번역합니다. 아트 포스터, 출판, 전시, 소셜 콘텐츠와 디자인 전용 출력에 적합합니다.

사진과 디자인의 분리, 과도한 장식, 부족한 여백과 비율별 불안정한 결과를 해결합니다.

## 원본 프롬프트 · 5개 언어

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 네 가지 출력 모드

- `top-bottom`: 현실 사진을 위, Panel 112 디자인을 아래에 두고 각각 50%입니다.
- `left-right`: 현실 사진을 왼쪽, 디자인을 오른쪽에 두고 각각 50%이며 상하로 회전하지 않습니다.
- `design-only`: 전체 캔버스에는 이 Panel의 디자인만 보이고 사진은 참고로만 사용합니다.
- `wallpaper-pack`: 기기별로 완전한 캔버스를 생성합니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-112.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-112" ~/.codex/skills/xxd-panel-112
```

`npx skills`로도 바로 설치할 수 있습니다:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-112 --skill xxd-panel-112
```

GitHub에서 저장소를 가져와 같은 이름의 Skill을 설치합니다. 사용자 전역 Codex 설치는 `--global --agent codex --yes`를 추가하세요.

설치 후 Agent 세션을 다시 시작하고 호출하세요 `$xxd-panel-112`.

## 라이선스

이 프로젝트는 **PolyForm Noncommercial License 1.0.0**에 따라 제공됩니다. 전체 전문은 [LICENSE](LICENSE), 공식 페이지는 <https://polyformproject.org/licenses/noncommercial/1.0.0>에서 확인하세요.

- 개인 학습·연구·실험·테스트·취미·비공개 오락과 해당 공익기관의 사용을 허용합니다.
- 비상업적 목적이면 사용·복사·수정·2차 저작물 작성·배포가 가능하지만 라이선스와 고지문을 함께 제공해야 합니다.
- 상업 제품·서비스·유료 납품·접근권 판매·예상 상업 적용은 별도 서면 허가가 필요합니다.
