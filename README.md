# YouTube Subtitle Library

I started this project for myself because many YouTube videos are missing subtitles, and I wanted to be able to understand videos in languages I'm not fluent in.

# Contribution

Feel free to contribute to the project by making a PR for a subtitle.

# How to Quickly Create Subtitles

"AI bad, mkay", but in this case it is great, because unlike the mainstream anti-AI Karen will tell you, LLMs got pretty good at lots of things, including transcription of videos.

We can use this to let Gemini create great and accurate subtitles for us in any language!

Open https://aistudio.google.com/, select Gemini 3.7 Flash or a newer model, then paste the YouTube video URL and below, tell it the following:

```
Please generate English subtitles for this YouTube video. The whole video please, with correct timestamps. Output it as a ready-to-use subtitle format I can upload to YouTube. The language of the video is Japanese, so you need to translate what's being said.
```

You obviously need to replace `English` and `Japanese` with the correct languages for the YouTube video you want subtitles for, but yeah, that's basically all you need.
