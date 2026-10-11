# app-demo

Demo videos for apps from [OneClickTool Studio](https://oneclicktool.app). One folder per app, recorded in the real app.

| App | Folder | Page |
|---|---|---|
| Sweepy (Mac) | [`sweepy/`](sweepy/) | [oneclicktool.app/macos/sweepy](https://oneclicktool.app/macos/sweepy) |

## Layout

```
<app>/
  shorts/   vertical 9:16 (1080x1920) clips for TikTok, YouTube Shorts and Reels
```

File names end with the video size, e.g. `downloads-voice-1080x1920.mp4`.

## oneclicktool/ — media host for oneclicktool.app

Videos and screenshots used by the website, served from GitHub Pages so the site deploy stays small:

```
https://nvminhtu.github.io/app-demo/oneclicktool/<path>
```

`<path>` is the same path the file had under the site's `public/` folder, e.g.
`oneclicktool/products/sweepy/demo.mp4` → `https://nvminhtu.github.io/app-demo/oneclicktool/products/sweepy/demo.mp4`.
Icons and blog illustrations stay in the site repo.
