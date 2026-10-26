<p align="center">
  <img src="docs/assets/editor.png" alt="Dark Channel Studio editor: media pool, viewers, multi-track timeline and inspector" width="100%" />
</p>

<h1 align="center">Dark Channel Studio</h1>
<h3 align="center">Find the best moment of a video, turn it into a vertical Short, and approve it before it goes anywhere.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/runs-locally-blueviolet.svg" alt="Runs locally" />
  <img src="https://img.shields.io/badge/cost-free%20%26%20open%20source%20tools-brightgreen.svg" alt="Built on free and open-source tools" />
  <img src="https://img.shields.io/badge/publishing-manual%20approval-orange.svg" alt="Manual approval before publishing" />
</p>

## About

Dark Channel Studio is a studio you run on your own computer for "faceless" short-video channels (TikTok, Instagram Reels, YouTube Shorts). It helps you find source videos, shows you the moments viewers replay the most, cuts them to 9:16, and lets you edit with AI narration, captions and music in a timeline editor. Every Short then waits in an approval queue until you say it can go out.

**Good for:** clip channels, podcast and interview clips, original AI story series, and anyone who wants to make many Shorts without losing control of each one.

This repository is a showcase of the app's screens and features. The source code is not public.

## ✨ Highlights

- 🔎 **Find the moment.** Search a topic, rank videos by views, likes and recency, and see the "Most replayed" peaks with a virality score.
- ✂️ **Long video in, clips out.** Auto clips turns an upload or a link into ranked clip suggestions with title, hook and reason.
- 🎬 **Edit like a video editor.** Multi-track timeline, media pool, source and timeline viewers, and an inspector for script, visuals, audio and finish.
- 🗣️ **Voice and captions.** AI narration, word-level animated captions, music with ducking.
- 🎨 **Ready-made looks.** Layouts for framing a Short (glass, gradient, cinema, poster, stacked, HUD, neon) and a cover maker.
- 📤 **Export your way.** 9:16, 1:1, 4:5 or 16:9, with an estimated file size before you render.
- ✅ **Approve before publishing.** Per-platform captions and hashtags, transformation checks and an AI-disclosure confirmation.
- 📺 **Many channels.** Each channel keeps its own accounts, settings and data.
- 📖 **Stories too.** Original AI story episodes: series bible, script, images and voices, then render.
- 🤖 **An expert in the app.** A chat agent that evaluates niches and operates the studio for you.

## 🧭 How a Short is made

1. 📥 **Source.** Search YouTube for a topic, or upload a video or paste a link. The studio ranks the results and remembers where each one came from.
2. 📈 **Moment.** It reads the "Most replayed" heatmap and suggests peak windows. No heatmap? Pick the moment yourself.
3. 🎛️ **Edit.** Open the clip in the editor: add narration, captions, music, text and a layout.
4. 🛡️ **Approve.** Export the Short and send it to the queue. It must pass the transformation checks and an AI-disclosure confirmation before you can approve it.
5. 🚀 **Publish.** Copy the per-platform captions and post, after your approval.

## 🎥 See it move

![Discover videos, find replay peaks, cut a clip](docs/assets/hero-discover.gif)

![Edit, export and queue a Short](docs/assets/hero-edit-export.gif)

## 👀 Take a look

**Discover.** Ranked videos, virality scores and replay peaks.

![Discover screen with ranked videos, virality scores and replay peaks](docs/assets/discover.png)

**Export.** Aspect ratio, size, frame rate and quality, with an estimated file size.

![Export dialog with aspect ratio, size, frames per second and quality options](docs/assets/export.png)

**Approval queue.** Per-platform captions, approval checks and the AI-disclosure toggle. A failed check blocks approval until the Short is fixed.

![Approval queue with TikTok and Instagram captions, approval checks and AI disclosure toggle](docs/assets/queue.png)

_Screenshots use "Big Buck Bunny" (c) Blender Foundation, www.bigbuckbunny.org, licensed CC-BY 3.0, as demo content._

## 🧩 And more

- Podcast clips: per-speaker caption colors and a guest name bar.
- Edit by text, filler-word removal and caption translation.

## 🤝 Responsible use

Reusing third-party video is the main risk of this kind of tool. The studio is built around transformation, not reposting:

- Every clip stores its source (video id, channel, URL) and music license.
- Transformation checks (original narration, added visual layers, on-screen text, short length, source credit) must pass before approval.
- AI-generated narration or visuals require a confirmed AI-disclosure label.
- Publishing requires manual approval by default.

## License

All rights reserved. The screenshots and GIFs are shared for showcase only.
