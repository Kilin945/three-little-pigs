# The Three Little Pigs — Interactive Bilingual Audio Storybook 🐷📖

**Live demo: https://kilin945.github.io/three-little-pigs/**

An interactive, self-paced audio storybook of *The Three Little Pigs*, fully AI-generated — illustrations, narration, and sound effects — and playable in any browser, on desktop or mobile.

## Features

- **8 illustrated pages** with a consistent picture-book art style (generated with Z-Image Turbo, prompted in Chinese)
- **Auto-playing narration** on every page — tap once on the cover and the story reads itself aloud as you flip
- **Reader-controlled pacing** — tap anywhere to turn the page; it never rushes ahead like a video
- **Bilingual (中文 / English)** — one button in the top-right corner switches subtitles *and* voice narration instantly, even mid-page
- **Expressive audio** — narration by Microsoft Edge TTS (zh: Yunjian / en: Guy), with hand-tuned onomatopoeia and a real synthesized impact SFX for the wolf's *BANG!*
- **Keyboard support** — `→` / `Space` next page, `←` previous page

## How to read

1. Open the [live demo](https://kilin945.github.io/three-little-pigs/)
2. Tap once to start — audio plays automatically from then on
3. Tap anywhere to turn the page; use the top-right button to switch language

## How it was made

Produced by a personal "comic factory" pipeline — an AI-agent-driven workflow (Claude Code) that turns a story script into finished pages:

```
story script → per-page Chinese prompts → Z-Image Turbo (local, ComfyUI)
→ agent visual review loop → Edge TTS narration (zh/en) → ffmpeg SFX
→ static HTML storybook
```

All images were generated locally on a MacBook (Apple M4), reviewed page by page against acceptance criteria, and iterated until approved.

## License

[MIT](LICENSE)

---

# 三隻小豬——互動式中英雙語有聲書 🐷📖

**線上閱讀：https://kilin945.github.io/three-little-pigs/**

一本互動式、自主節奏的《三隻小豬》有聲書，插圖、旁白、音效全部由 AI 生成，任何瀏覽器（電腦或手機）都能直接閱讀。

## 特色

- **8 頁插圖**，統一的童書繪本畫風（Z-Image Turbo 生成，中文 prompt 直接下）
- **每頁自動播放旁白**——封面點一下之後，翻到哪頁就唸哪頁
- **讀者掌控節奏**——點畫面任意處翻頁，不像影片會自己跑完
- **中英雙語**——右上角一顆按鈕，字幕與語音同時切換，看到一半也能切
- **有張力的配音**——旁白使用 Microsoft Edge TTS（中文：雲健／英文：Guy），狀聲詞逐一調校，大野狼撞木屋的「砰！」是真實合成音效
- **鍵盤操作**——`→`／空白鍵下一頁、`←` 上一頁

## 閱讀方式

1. 打開[線上閱讀](https://kilin945.github.io/three-little-pigs/)
2. 點一下開始——之後每頁自動播音
3. 點畫面任意處翻頁；右上角按鈕切換語言

## 製作方式

由個人「漫畫工廠」產線製作——以 AI Agent（Claude Code）驅動的工作流，把故事腳本變成成書：

```
故事腳本 → 每頁中文 prompt → Z-Image Turbo（本地 ComfyUI）
→ Agent 讀圖驗收迴圈 → Edge TTS 中英旁白 → ffmpeg 音效
→ 靜態 HTML 有聲書
```

所有圖片皆在 MacBook（Apple M4）本地生成，逐頁依驗收條件審查、迭代至通過。

## 授權

[MIT](LICENSE)
